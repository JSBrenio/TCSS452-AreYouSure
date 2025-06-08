# Synchro Simplified
Enhancing Clarity for Future Traffic Engineers

<img src="images/logo.png" alt="Logo" width="300"/>

**TCSS 452 Team: Are You Sure?**
- Anthony Petrov
- Jennifer Huynh
- Jeremiah Brenio
- Liam Barragan
- Luke Chung

## Problem and Design Overview
  Synchro Studio, a transportation and traffic network application developed by Cubic, presents a steep learning curve in its current user interface (UI), challenging aspiring Civil Engineering students and users alike.
  
  This project attempts to address the initial friction of using Synchro as a beginner. From User Research, the most prominent issue arising from interacting with the software, as a new user, was the overload of different buttons, options, and settings within the interface.
  
  The new design laid out encapsulate the two most common tasks that users must perform within the software on a day-to-day basis:

### The Proposed Redesign 
![Redesign Image 1](images/digital-prototype-task-1-new-2.png)  
*Figure 1: Redesigned interface for adding links and lane data, highlighting simplified controls and improved layout.*

![Redesign Image 2](images/digital-prototype-task-2-new-2.png)  
*Figure 2: Enhanced map data import workflow, showing integration with third-party services for better usability.*

### Our Approach
Ultimately, these changes are designed to reduce decision fatigue caused by excessive interface clutter in the current software. By streamlining navigation and focusing on core workflows, our redesign helps users quickly access essential features and complete tasks more efficiently.

## Design Walkthrough

### 1: Completing Intersections with Traffic Data for Analysis

**Task Context:**
Adding data to roads & intersections is essential for analysis and simulation. For any given intersection, a user needs to navigate to more than one menu to complete their goal.

![Current Synchro UI lanes/volumes/timing Visuals](images/synchro-ui-menus-1.png)

This introduces navigation challenges to new users of Synchro, and it doesn't help that multiple of the same settings can be found in different menus, lacking distinction.
### Redesign Walkthrough

When an intersection is created, a button appears at the center. Clicking this button opens menus for each road, allowing users to access relevant settings directly.

![Task 1-1 Visual](images/digital-prototype-task-1-new-1.png)

Each menu pops up as an overlay, reducing the need to navigate through multiple menus and making it easier to focus on the current task.

![Task 1-2 Visual](images/digital-prototype-task-1-new-2.png)

Users can add new row settings for all menus using the plus icon at the bottom-left, streamlining the process of entering and editing data.

![Task 1-3 Visual](images/digital-prototype-task-1-new-3.png)

This holistic design aims to mitigate navigation issues by incorporating contextual popups for each road, helping users work more efficiently and with less confusion.

### 2: Importing Map Data into Synchro

**Task Context:**
Old experienced users of Synchro had to import map data from third-party services such as Google maps in order to scale their roads correctly onto the UI. The new version of Synchro tries to fix this by integrating Bing maps into Synchro. But we wanted to keep the familiarity and routine for new and old users by adding overlays and further integration with other third-party services.
### Redesign Walkthrough

The redesigned workflow for importing map data into Synchro focuses on clarity, integration, and ease of use for both new and experienced users.

We use an import button (directly in the top middle of the interface) for the user to begin the import process.
![Task 2-1 Visual](images/digital-prototype-task-2-new-1.png)

The import screen presents clear options for importing map data, reducing confusion and guiding users toward the most common actions.

Next, users can select from integrated third-party services, such as Google Maps or Bing Maps, to import their desired map data:

![Task 2-2 Visual](images/digital-prototype-task-2-new-2.png)

This integration maintains familiarity for experienced users while offering streamlined access for newcomers.

The user can then add roads (top left button) on the map overlay, which would then be transferred to Synchro after finalizing their links.

<div style="display: flex; gap: 16px;">
  <img src="images/digital-prototype-task-2-new-3.png" alt="Task 2-3 Visual" style="width: 48%;">
  <img src="images/digital-prototype-task-2-new-4.png" alt="Task 2-4 Visual" style="width: 48%;">
</div>

<br>

Once satisfied, users can confirm their selections and complete the import process:

![Task 2-5 Visual](images/digital-prototype-task-2-new-5.png)

This redesign addresses the previous challenges of fragmented workflows and providing visual guidance throughout the process. The result is a more approachable, efficient, and user-friendly experience that accommodates the needs of both novice and experienced Synchro users.


## Design Research and Key Insights

### Goals
Through our design research and collaboration with the TCE 327 Civil Engineering students, we aimed to gain insight and identify usability challenges using Synchro Studio.

### Methods and Rationale
For our design research methods, we intended to use **contextual inquiry** and conduct **focus groups**. We thought this was the most effective way of obtaining data for the project. **Contextual inquiry** involves observing and asking questions to users in their actual work environment to understand their workflows and challenges. **Focus groups** gather a small group (2 - 5) of participants to discuss their experiences and opinions, providing diverse perspectives and uncovering common issues.

But we’ve encountered **two** main challenges and had to adapt. 

**First**, the class structure consisted of the students following a walkthrough with an industry lecturer. This made it difficult to inquire and ask questions without disturbing the lecture, so we had to pivot to **Fly-on-the-wall** observations, where we observe the whole class without interruption and note emerging themes.

**Second**, we had difficulties with scheduling with the TCE students and getting more than one participant for a given day for our focus group. So we had to switch to **interviews** instead, which set us behind a few weeks for the project. 

But despite that, we were still able to obtain valuable data and insight.

### Key Insights

#### **[Insight 1 Title/Statement]**
- **How it emerged:** [From users, critique, testing, etc.]
- **Evidence:** [Visuals, evidence, or stories]
- **Design influence:** [How this influenced your final design]

#### **[Insight 2 Title/Statement]**
- **How it emerged:** [From users, critique, testing, etc.]
- **Evidence:** [Visuals, evidence, or stories]
- **Design influence:** [How this influenced your final design]

#### **[Insight 3 Title/Statement]**
- **How it emerged:** [From users, critique, testing, etc.]
- **Evidence:** [Visuals, evidence, or stories]
- **Design influence:** [How this influenced your final design]

## Iterative Design and Key Insights

### Design Process Summary
- **Paper Prototyping → Usability Testing**
When we started working on paper prototype we tried our best to focus on simplifying the lane parameters and making it easy for the user to be able to not feel overwhelmed with the parameters. We also kept in mind that we were also trying to make adding lanes more easy and simplified for the users. Also during the making of our paper prototype we tried making the icons drawings as distiguishable as we could so the user did not need to question what certain icons did. During our usability testing, we found that the participants found it difficult to know what certain buttons did and they thought adding a description should be necessary so that things would not be confusing. We did find that the particpants did find making intersections easier, however adding lanes button was not clear to the particpant. We also found that the participants were having a hard time when lane parameter menu was selected.
- **Digital Mockups → Heuristic Testing**
- **Rationale/Reflections:** 
What this process revealed is that it is not easy to design a product, as users could find it difficult to know what certain things do. Where we thought the user would have an easier time to do a certain task, was actually difficult for them to do. This type of feedback helped us fix our designs so that users have an easier time doing tasks. This iterative process also revealed users like simplicity, descriptions to help understand what certain buttons do, and also visual clarity. These types of feedback helped us make our final design more easier to use. 

### Paper Prototype
![image](https://github.com/user-attachments/assets/ce0e5cf5-f11d-44cf-a683-947ad28048a3)
![image](https://github.com/user-attachments/assets/ec550d7a-fd00-433f-8765-462d19061a10)
![image](https://github.com/user-attachments/assets/35bafd76-9d50-4fff-9e10-3f63f0c91250)



### Design Insights from Iteration

#### **Adding Lane Button Clear**
- **How it emerged:** One of the groups reviewed our Digital Prototype using the Heuristic Evaulation and found it difficult to identify
the add lane button.
- **Evidence:** The group typed up, "Adding actual lanes is slightly unclear due
to language used (i.e basic symbols).
Because the lane adding was unclear, the
exit button was also a little unclear."
- **Design changes:** Before: ![image](https://github.com/user-attachments/assets/d41c8006-f061-446a-9f61-bace0dda8db8)
 After: ![image](https://github.com/user-attachments/assets/80ddde5e-5af8-43f6-8c86-fdf096d4efd4)


#### **Making Each Road Selectable**
- **How it emerged:** Heuristic Evaulation from the group evulation had a hard time trying to have the individual roads be selected. 
- **Evidence:** The group said, "The selection is based around
intersections, so if I am working on a road
I have to find the nearest intersection in
order to select the road. This makes
knowing when roads are able to be
selected confusing."
- **Design changes:** Before: ![image](https://github.com/user-attachments/assets/44173767-b30f-4b44-a293-33bf9cfc9fa2)
After: ![image](https://github.com/user-attachments/assets/fff70eb7-2b4f-4982-b1fa-731ac51bb62b)


#### **Add Description For Buttons**
- **How it emerged:** During our usability testing for our Paper Prototype, the participants had difficulty figuring out what certain buttons did.
- **Evidence:** From our observations during our usability testing, the participant mentioned they couldn't understand what the button does as there was not description.
- **Design changes:** Before: ![image](https://github.com/user-attachments/assets/f1f8cdce-1633-4153-b9db-ce9e67b56e9c)
After: ![image](https://github.com/user-attachments/assets/a41da2b1-9990-4f8f-9101-3e222e07c65f)


## Technical and Soft Skills Gained

### Technical Skills
- Design Principles
  - Learnability
  - Efficiency
  - Safety
- Low-Fidelity Prototyping
  - Rapid prototyping
  - Design sketches
  - Paper prototypes
- High-Fidelity Prototyping
  - Figma
  - Digital mockups
- Evaluation Methods
  - Usability testing
  - Heuristic evaluating


### Soft Skills
- Team Collaboration
  - Cross-functional coordination
  - Task delegation
  - Conflict resolution
  - Remote collaboration
- Communication
  - Active listening
  - Presenting concepts
  - Technical documentation
  - Facilitating discussions
- Feedback Integration
  - Processing criticism
  - Peer review incorporation
- Adaptability
  - Method pivoting
  - Schedule adjustments
- Time Management
  - Deadline coordination
  - Priority setting
  - Milestone tracking
- Research Skills
  - User interviewing
  - Pattern identification
  - Insight translation

