# **Welcome to my ePortfolio**

## **Johnna Evans**
**Former Senior Project Analyst** | **Former Software Tester** | **Residential Contracting Business Owner**  
Bachelor of Science in Computer Science - Southern New Hampshire University  
Concentration: Project Management for STEM  
Associate in Business Administration - Southeast Technical Institute  

---
## About this Portfolio
A showcase of key projects and ehnacements developed throughout my Computer Science degree program with a concentration in Project Management for STEM. I bring a multidisciplinary perspective that blends technical proficiency with leadership and analytical thinking. Drawing from my experience as a Senior Project Analyst, software tester, and current residential contracting business owner, I apply real-world insight into the design, development, and management of software solutions. 

---
## Project Artifacts & Enhancements  

### Software Engineering and Design  
> *Enhanced 3D OpenGL scenc featuring texture toggling, lighting configuration, and interactive camera control.*

### Algorithms and Data Structures  
> *Interactive 2D breakout-style game enhanced with physic-based behavior, merging logic, and hit-based brick states.*

### Databases 
> *Normalized SQL-based inventory system, enhanced with JOIN queriers and a trigger for logging customer email updates.*
 
---

### Code Review 
**[View ScreenPal Code Review](https://go.screenpal.com/watch/cTQtYpnDuTP)** 

---

### Enhancement One: Software Design and Engineering 
The selected artifact for this milestone is a 3D OpenGL cosmetic scene that was developed during my CS-330 Computer Graphics and Visualization course in May 2025. The scene was designed to replicate a real-life cosmetic display which included 3D representation of items such as a perfume bottle, mascara tube, lotion container, and eyeshadow palette. The scene also included a vertical backdrop plane and a floor plane to complete the display environment. Each object was created using basic geometric primitives such as cones, cylinders, spheres, and boxes.  To enhance realism, loaded custom shader textures were applied to the objects and enhanced using a texture UV scale and shader material.  The scene used directional and point lights for realistic illumination and included full camera navigation using mouse and keyboard inputs to allow interactive exploration of the 3D environment. 
	This artifact was selected for my ePortfolio because it demonstrates a broad range of software engineering and design skills, including 3D modeling, texture mapping, shader application, lighting configuration, and interactive camera control.  This project reflects my ability to use OpenGL and C++ to build a visually rich and interactive 3D environment that adheres to core design principles such as realism, modularity, and visual hierarchy. 
	
This artifact showcases my ability to: 

•	Apply graphics programming techniques such as UV scaling and texture mapping to dynamically load and display surface materials. 

•	Configure lighting systems using directional and point light sources to simulate realistic scene illumination through program shaders. 

•	Implement real-time user input handling to enable camera control navigation following event-driven design. 

•	Design and organize modular code architecture by encapsulating rendering, transformation, and interaction logic into reusable object-oriented classes. 

This artifact was improved by adding functionality to toggle between two backdrop textures using keyboard input.  While I was able to implement the conditional logic, the enhancement had some limitations due to the fact that SNHU-provided starter files did not include access to the fragment shader, which would normally allow full runtime texture changes. Despite the limitation, the enhancement adds interactivity and demonstrates how user input can be applied to influence rendering behavior. 
This artifact aligns with the course outcomes identified in my Module One plan, particularly Course Outcomes Two and Four. The enhancement work required designing, coding, and testing additional runtime interactivity that supports texture switching based on user input.  This directly reflects Course Outcome Two, as I applied professional, quality C++ and OpenGL practices to deliver a technically sound and visually coherent solution.  My attention to modular design, clarity of logic, and effective documentation supports communication of both technical and visual intent. 

The project also demonstrates Course Four by integrating well-founded software engineering techniques such as shader management, keyboard input handling, and scene rendering logic.  I implemented runtime conditions, updated scene logic to react dynamically to user interaction, and thoroughly tested these changes in a controlled environment.  These are skills aligned with real-world development workflows and industry-specific practices. 
While there was difficulty with the toggle feature displaying visibly during runtime due to rendering constraints in the school’s preloaded code, the supporting structure was successfully integrated into the codebase.  The enhancement strengthened the system’s design and demonstrated iterative development, thoughtful debugging, and implementation planning consistent with professional standards. No updates are needed to my original outcome coverage plan. 
Enhancing this artifact provided a valuable opportunity to apply iterative development, code review, and debugging practices within a familiar but expanded codebase. While the original project demonstrated static rendering and navigation, the enhancement introduced a new layer of interactivity and runtime logic, deepening my understanding of how user input can dynamically influence scene behavior. 

A key lesson I learned was the importance of planning enhancements that integrate cleanly into existing architecture.  I carefully reviewed the original object initialization, rendering functionality, and input handling system to determine the most efficient way to implement the texture logic without disrupting other features.  This reinforced my skills in modular design and scene management, as I structured the toggle feature using conditionals and flags that remained isolated from unrelated systems. Throughout the process, I encountered challenges in verifying rendering behavior, particularly when the texture toggle would not visibly update as expected.  Rather than rewriting core rendering logic, I focused on confirming that all toggle conditions and function calls executed correctly.  This process emphasized the importance of debugging, where success is measured by logic and execution.  Ultimately, the enhancement process sharpened my ability to reason through unfamiliar rendering behavior, isolate potential problem areas, and implement changes in a structured, testable manner.  These are essential skills for real-world software development. 

**[Enhancement One Repository Link](https://github.com/JEvans79/EnhancementOne_Software_Design_and_Engineering)**

--- 
### Enhancement Two: Algorithms and Data Structure 
The selected artifact is a 2D breakout-style game created in C++ using OpenGL in Visual Studio.  It was originally developed during my CS-330 Computer Graphics and Visualization course in May 2025. The game includes interactive elements such as a player-controlled paddle, balls that bounce with physics-based logic, and both destructible and reflective bricks.  Each destructible brick was initially designed to darken and crack in color with each hit of the ball and disappear after three hits. This version of the project was created during an earlier module and served as a foundation for implementing data structure logic (vectors, objects) and algorithms (collision detection, velocity adjustment, hit tracking).
	This artifact was selected for my ePortfolio because it showcases my understanding and application of key computer science concepts in algorithms and data structures, including: 
	
•	Dynamic memory management and use of the C++ Standard Template Library, specifically std::vector, to store and update dynamic collection of circle and brick objects in real time. 

•	Object-oriented programming (OOP) principles to encapsulate game object attributes (e.g., position, size, color, type, and hit count) and behaviors within reusable class structures. 

•	Collision detection algorithms implemented using axis-aligned bounding box techniques, to determine when a circle (ball) intersects with a rectangular brick. 

•	State-based logic to track and update brick durability across multiple hits by incrementing a counter and adjusting object properties conditionally by color and width. 

The enhancement involved adding logic so that destructible bricks dim in color as well as shrink in width after each collision.  This modification added a progressing state change, requiring each brick to store and update its hitCount.  It involved modifying the rendering logic to scale brick width while preserving alignment and interactivity across multiple frames.  This visual feedback loop reinforced the use of iterative conditionals, mathematical operations, and real-time geometry manipulation.  All of which are fundamental to both game development and algorithm design. 

I did meet the planned course outcome (Course Outcome 3) which focuses on designing and evaluating computing solutions that use algorithmic principles and computer science practices.  The updated functionality required me to evaluate the limitations of the original implementation, where destructible bricks simply disappeared after a hit, and designed an improved behavior using conditional logic and mathematical calculations.  By introducing a shrinking mechanic based on hit count, I developed a solution that better represents state-based object behavior.  This enhancement required the use of control structures, memory management (via vector storage of objects), and dynamic rendering principles to ensure game stability with changing object dimensions. 

In addition, the enhancement supports Course Outcome 4, as it applied reliable techniques such as collision detection, geometric transformation, and frame-by-frame rendering logic, using OpenGL and C++ standards.  The project was grounded in real-time updates and user interaction, demonstrating practical problem-solving and iterative improvement which are important principles of software engineering and algorithmic design. 
There are no changes needed to the outcome coverage plans made in Module One.  The enhancement was implemented exactly as planned and demonstrates my skills in algorithmic control, object state management, and real-time graphics programming. 

Throughout the enhancement process, I gained deeper insight into how small algorithmic changes can significantly impact program behavior and user experience.  Implementing a shrinking mechanic required more than simply modifying visual output, it necessitated understanding how changes to object dimensions would affect collision detection, rendering accuracy, and game logic consistency.  A key challenge I encountered was ensuring that the shrinking brick still properly interacted with the ball after each hit.  Since the width of the brick was decreasing, the bounding box for collision detection had to be recalculated every frame to avoid false positives or missed collisions.  Debugging this required careful observation and incremental testing to ensure both visual and logical alignment between game objects. 
	I also experimented with different width reduction values and ultimately settled on 0.4f, which produced the clearest visual feedback and best gameplay balance.  This iterative process emphasized the importance of tuning and testing algorithms in real-world applications to achieve the desired outcome.  The experience reinforced my understanding of how data structures and conditional logic work together in real-time environments to create flexible and interactive programs. 
	This enhancement taught me to think more critically about object states, reuse existing logic effectively, and improve gameplay without overcomplicating the codebase.  It also reaffirmed the value of small, well targeted enhancements in demonstrating core competencies in computer science.  	




