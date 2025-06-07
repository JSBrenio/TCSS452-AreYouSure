# Synchro Simplified
Enhancing Clarity for Future Traffic Engineers

<img src="images/logo.png" alt="Logo" width="300"/>

**Team: TCSS452-AreYouSure?**
- Anthony Petrov
- Jennifer Huynh
- Jeremiah Brenio
- Liam Barragan
- Luke Chung

## Problem and Design Overview
  Synchro Studio, a transportation and traffic network application created by Cubic, has a steep learning curve and its current user interface (UI) challenges aspiring Civil Engineering students and users alike.
  
  This project attempts to address the initial friction of using Synchro as a beginner. From User Research, the most prominent issue arising from interacting with the software, as a new user, was the overload of different buttons, options, and settings within the interface.
  
  The new design laid out encapsulate the two most common tasks that users must perform within the software on a day-to-day basis:
  
### Adding Links and Lane data

#### The proposed redesign 

<img src="images/digital-prototype-task-1-new-2.png">

#### The current design

<div style="display: flex; gap: 16px;">
  <img src="images/digital-prototype-task-1-new-2.png" style="width: 48%;">
  <img src="images/synchro-lane-settings.png" style="width: 48%;">
</div>

  Ultimately, these changes aim to alleviate the decision fatigue from too much "clutter" within the current iteration of the software, while streamlining the process of getting to the "meat" of the workflow.

[Brief overview of your design and approach to solving the problem]

![Introductory Image](images/digital-prototype-task-2-new-4.png) <!-- Your logo or initial prototype photo -->

## Design Walkthrough

### 1: Completing Intersections with Traffic Data for Analysis

**Task Context:**
Adding data to roads & intersections is essential for analysis and simulation. For any given intersection, a user needs to navigate to more than one menu to complete their goal.

![Current Synchro UI lanes/volumes/timing Visuals](images/synchro-ui-menus-1.png)

This introduces navigation challenges to new users of Synchro, and it doesn't help that multiple of the same settings can be found in different menus, lacking distinction.

**Redesign**:
![Task 1-1 Visual](images/digital-prototype-task-1-new-1.png)

![Task 1-2 Visual](images/digital-prototype-task-1-new-2.png)

![Task 1-3 Visual](images/digital-prototype-task-1-new-3.png)

This holistic design hopes to mitigate the navigation issue by incoporating popups for each road to be worked on.

When an intersection is made, a button will appear at the center. When the user clicks on the button, menus for each road will popup with relevant the settings - there's also the option to add new row settings for all menus via the plus icon at the bottom-left.

### 2: Importing Map Data into Synchro

**Task Context:**
Old experienced users of Synchro had to import map data from third-party services such as Google maps in order to scale their roads correctly onto the UI. The new version of Synchro tries to fix this by integrating Bing maps into Synchro. But we wanted to keep the familiarity and routine for new and old users by adding overlays and further integration with other third-party services.

**Redesign**:
![Task 2-1 Visual](images/digital-prototype-task-2-new-1.png)

![Task 2-2 Visual](images/digital-prototype-task-2-new-2.png)

<div style="display: flex; gap: 16px;">
  <img src="images/digital-prototype-task-2-new-3.png" alt="Task 2-3 Visual" style="width: 48%;">
  <img src="images/digital-prototype-task-2-new-4.png" alt="Task 2-4 Visual" style="width: 48%;">
</div>

<br>

![Task 2-5 Visual](images/digital-prototype-task-2-new-5.png)


[Narrative walkthrough for Task 2 - provide enough detail for an outside reader to understand the design]


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
- **Digital Mockups → Heuristic Testing**
- **Rationale/Reflections:** [What this process revealed]

### Paper Prototype
![image](https://github.com/user-attachments/assets/0c97c5d1-b4c7-4fa4-a889-010f48f42cc9)
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

