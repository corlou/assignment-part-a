## Question 1: Description of your website

#### Problem and Solution:

When it comes to yoga, there is a standard of move names. No matter where you are in the world, all students and teachers can identify the poses. However, when it comes to pole fitness, move names vary wildly from studio to studio (with the exception of famous moves). So transferring between studios, selecting a category for pole competitions, attending pole camps, and even remembering what was taught in class is next to impossible.

**Solution: Create a dictionary of pole moves with images and names.**

#### Target Audience:

This app will focus on a small studio in Brisbane, CSolta Pole Studio, that has mixed level classes. The target audience will be the teacher and students of CSolta. The teacher uses her phone to search for moves to teach but there is no history of moves she has taught. Furthermore, students can't remember what they have learned and aren't able to search online because of the different move names.

#### Functionality/Features:

##### Teacher

- Login as a teacher, who is also the administrator.
- Search for a move and view the list of moves.
- Add a move to a class.
- Delete a move from a class.

##### Student

- Login as a student.
- Search moves.
- View moves added to their class.

##### Nice to have:

- Allow students to mark moves as a 'favourite', and view the favourite moves under their profile.
- Add checkboxes for confidence level - a teacher can then use this information for future class planning.

#### Tech Stack:

- MongoDB
- Express
- React
- React Bootstrap for styling
- Node.js

[View the app presentation on Vimeo](https://vimeo.com/844095208?share=copy)

<div style="page-break-after: always"></div>

## Question 2: Data flow Diagram

The Move Mentor data flow diagram maps out the flow of information between entities (students and teachers), database documents (students, teachers, classes, moves) and processes. The diagram uses Yourdon & DeMarco notation to represent entities, data stores, processes and flows (Chi 2021).

<img title="dataflow diagram" alt="" src="images/q2/dataflow_diagram.jpg">

<div style="page-break-after: always"></div>

## Question 3: Application Architecture Diagram

The application architecture diagram visually represents the structure of the Move Mentor app, the relationship between its components, and the flow of data. The Move Mentor app is made up of three components: a front-end, back-end and database.

Symbol representations:

- Vertical rectangle for components.
- Rounded horizontal rectangles for frameworks and languages.
- Hexagons for deployment platforms.
- Cylinders for databases.
- Arrows for data flows.

<img title="architecture of the app and the tools to be used" alt="" src="images/q3/app_architecture.jpg">

<div style="page-break-after: always"></div>

## Question 4: User Stories

We decided to develop the user personas and stories together; we knew it would be a fun task using our creative brains to identify each app user's goals, motivations and frustrations, and craft stories based on these elements. This involved several conversations about the pole studio and its users:

- What does the pole studio offer?
- Who is/are the teachers? What is their experience and background?
- How do teachers structure classes?
- Who are the students? How often do they attend?
- What are the specific challenges faced at the studio, and during classes?

Following on from our discovery phase, we decided to create three users and assigned users to a specific team member. We would then review each other's work in progress and provide feedback and suggestions on how to improve outputs.

The first user story focused on the teacher and what they would need from Move Mentor. Rafaela is the studio owner and main teacher at CSolta pole studio. She uses her phone to search for moves during class time. While this process doesn't take up a lot of class time, it does come across as slightly disorganised. It's also safe to assume that she spends a lot of time outside of class researching appropriate moves for different classes with varying student abilities.

Karla interviewed Corina about what it's like to be a pole teacher including lesson planning and compared it to what Rafaela is currently doing. Through the discovery process and after several iterations, Karla developed a user persona and three story points from the perspective of a teacher. Below is the card we used for the Teacher Story.

<div style="page-break-after: always"></div>

**Teacher:**

<img title="Persona card for user stories - Teacher" alt="" src="images/q4/user_persona_teacher.png">

Next came two different types of students: casual and dedicated. A casual student comes to class to have fun in a supportive social environment, while a dedicated student usually attends classes several times a week, researches new moves to try, and cares about technique.

<div style="page-break-after: always"></div>

**Casual Student:**

<img title="Persona card for user stories - Casual Student" alt="" src="images/q4/user_persona_casual_student.png">

Karla took on the challenge of creating a casual student persona. Thinking from the mindset of a working mum with little time to pursue leisure activities, some goals, motivations and frustrations were identified. From there, three casual student stories were developed.

<div style="page-break-after: always"></div>

**Dedicated Student:**

<img title="Persona card for user stories - Dedicated Student" alt="" src="images/q4/user_persona_dedicated_student.png">

Corina created a persona for the dedicated student. This wasn't too much of a challenge as she used to be one but there was a challenge of making the user stories short and specific. With the help of Karla's pattern of other user stories, Corina was able to get her user stories to the point which could then be used as inspiration for features in the app.

By taking an approach of discovery, and trying to identify the broader goals, motivations and frustrations of each user when it comes to pole dancing, we were able to craft user stories that helped us to identify key problems that the Move Mentor app can solve.

As with other parts of the project we used agile methodology effectively to plan our workflow - an initial collaboration, then assigning team members to develop each persona, and regularly reviewing each other's work in progress. This ensured the final user personas and stories were fit for use, and could help us further develop the Move Mentor app.

<div style="page-break-after: always"></div>

## Question 5: Wireframes for multiple standard screen sizes, created using industry standard software

#### Introduction

High-fidelity wireframes were created using Figma. With the short timeframe to design, test, develop and deploy a full stack app, high-fidelity wireframes have allowed us to go beyond placeholder text and images and capture the look and feel of the Move Mentor app including content, typefaces, colours and image dimensions (Moqups 2023). We took a mobile first approach to the wireframe designs, because most users will be using the app on their mobile phone, either in class or just prior to class for preparation purposes. Corina designed the wireframes in mobile and desktop sizes, and has also created a prototype on mobile. The prototype clearly shows the app flow, from initial login or sign up, through to viewing moves, and assigning and deleting moves (for teachers). The wireframes and prototype also clearly show intended actions and functions based on a user's click of a button or link.

[View all wireframes and the prototype in Figma](https://www.figma.com/file/BlgOBHzTnKIDA6QwaSd5eT/Full-Stack-App%3A-Part-A?type=design&node-id=0%3A1&mode=design&t=gClNEHdu0sEVweO8-1)

#### Discussion

The time spent on phones vs time spent dancing. Pole fitness can be an expensive sport, with participants wanting to maximise their class time. Therefore, this app has to be functional yet minimal. Careful consideration and thoughtful planning is essential. Intended actions, simple functions, relationships between screens, spacing and content prioritisation are all at the forefront when designing this app.

As Corina explains:

Since this is an off-shoot of an original app idea, I (Corina) had to make sure that everything was out of my head and clearly set out on paper for someone else to view, understand, and develop alongside me.

Using Figma, I threw together the initial wireframe design to get the ball rolling. It was an efficient way for my teammate, Karla, to grasp the idea of what we're building. I started to get caught up with the designs and colours, charging full steam ahead. However, I remembered earlier projects where I was the designer and someone else was building from my designs. They told me:

"Look at the documentation of the framework/language we're going to be implementing and use that to do the designs. If you need a button and we're using Bootstrap, find a Bootstrap button. Or if you need a table and we're using Tailwind, find that table in their docs. These will be the Lego pieces that I'll use for building and know exactly where to look."

I take this one step further in that this means we'll be working within the limitations of the framework too. Hopefully reducing hacks or tricky workarounds to implement something that shouldn't exist while keeping customer expectations and experience at the forefront. For example, if Bootstrap React doesn't have tables; then we won't use tables in the design. That way, the customer won't ask for a feature that was in the design but was not built into the actual product. It keeps our code cleaner and delivers what was agreed upon, which is good for reputation and contractual agreements.

**Here is an updated design using Bootstrap React pieces:**

<img title="button design" alt="" src="images/q5/buttons.png">

While the colours are the same, the rounded edges of the buttons are now reflective of the buttons found in React Bootstrap. Being a coder and/or designer, attention to detail is important. We're also operating on the mindset that whoever receives these designs can interpret and build them. Nothing will be left to assumption.

**Initial Wireframe Design:**

<img title="initial design" alt="" src="images/q5/design_initial.png">

The form buttons are mostly square with minimal rounding, there is a vague description of "maybe a drop-down selector instead of text-box?"" and a guess at mobile responsiveness.

**Using Bootstrap React Documentation:**

<img title="design using Bootstrap React" alt="" src="images/q5/design_bsr.png">

A specific component "Form Grid" is used, buttons are rounded, and there's a dropdown button to select student classes. There's no ambiguity and all \pieces exist in the documents. However, we can take some liberties with the styling. It would be nice to have "Name:" and the name input on the same line for aesthetic reasons but this can be fiddled with a bit later. Since the studio currently doesn't have a logo or colour theme, we had the freedom to choose. As it is bright and airy inside, we went with a similar look and feel for the app.

**Student Colours:**

<img title="colours for student login" alt="" src="images/q5/colours_student.png">

But, then we thought about what the teacher colours should look like so that it is distinctive from the student account but still keeps the same feel.

**Teacher Colours:**
<img title="colours for teacher login" alt="" src="images/q5/colours_teacher.png">

We changed the primary colour to purple and left the rest as is because a lot of the components will be reused to keep our code DRY while also giving a connected feel to the app i.e. same app but different levels of access.

Sticking to the agile methodology, I asked my team mate Karla for feedback on the designs before I continued. She suggested instead of two separate login/sign up pages (one for teachers and one for students), we have a single landing page where there are four options that take users to the relevant page. This will eliminate the need for multiple URLs and become a single entity.

<div style="page-break-after: always"></div>

**Original Landing Page for Students for either Login or Create New Account:**

<img title="landing pages for students" alt="" src="images/q5/landing_pages_student.png">

**Original Landing Page for Teachers for either Login or Create New Account:**

<img title="landing pages for teachers" alt="" src="images/q5/landing_pages_teacher.png">

**Completed Landing Page for all Users (mobile included):**

<img title="landing pages for both teachers and students combined" alt="" src="images/q5/landing_pages_both.png">

<div style="page-break-after: always"></div>

Since this is a mobile app, we decided to show the flow of the app by using bright green arrows and prototyping on the mobile designs. In Figma, I grouped together everything I could so that any changes based on feedback can be easily completed. However, a limitation of Figma is that elements can be grouped only so far and still work with prototyping. Therefore, clear labelling was essential.

The main functionality of the app is for a teacher to assign moves to a class and for students to view those moves. So, this was a priority and we had to make this as easy as possible. A teacher can either find moves in the different categories and add them to a class or they can look at the moves already in the class and add/remove moves from there. This dual way of editing content made for good user experience (UX).

Another point for UX was the spacing. The overall theme is "light and airy" to keep within the feel of the studio so there couldn't be too much functionality on each page. Furthermore, chalk covered fingers of teachers and students using the app meant we needed to be extra considerate of space. Therefore, we kept functionality minimal and avoided using side menus or nested navigation options. This may be an issue for future building if more pages are required. Menus are important for larger apps to make navigation simpler but we were happy to build this app without one due to its current size and size of the intended studio.

After many iterations and feedback from a few sources, the final designs are ready to be built.

<div style="page-break-after: always"></div>

## Question 6: Screenshots of Trello Board

We used the following platforms for project management and planning:

- Trello for agile planning, executing and evaluating cycles. We created a card for each task of the project and assigned a team member and due date. We used the Trello cards to share questions, feedback and important information and links. Tasks were assigned to lists that followed the workflow states of to do, in progress, in review, blocked and done. As we progressed with each task, we moved our task cards to the relevant workflow state. [View the Trello board](https://trello.com/b/FzbSu39R)
- Google Drive for sharing of documentation, dataflow and app architecture diagrams, images, and any other important pieces of information to help us successfully complete part A of the project.
- Discord chat for sharing quick updates of our progress, asking questions and providing feedback. We also scheduled formal meetings using video conferencing so we could share screens and our work in progress.

Throughout Part A, we used agile methodology by breaking the project down into phases. Specifically, each question of the assignment was considered a task that was moved into a specific phase of planning, executing and evaluating. We continually collaborated by sharing feedback and ideas, and were always looking at ways to improve the outcome or final output of each task. For example, the wireframes and dataflow diagram went through several review phases as we discovered gaps in our thinking, and new ways of solving each problem. We'll continue to use agile methodology for Part B, as it allows us to be flexible and focus on constant improvements in a fast-paced 3 weeks of development.

<img title="trello screenshot - before work started" alt="" src="images/trello/2023-06-29_a.png">
<img title="trello screenshot - work is in review" alt="" src="images/trello/2023-07-01_d.png">
<img title="trello screenshot - discussion and collaboration on Architecture" alt="" src="images/trello/2023-07-03_d.png">
<img title="trello screenshot - added more cards to Trello" alt="" src="images/trello/2023-07-03_i.png">
<img title="trello screenshot - added due dates to certain tasks" alt="" src="images/trello/2023-07-06_a.png">
<img title="trello screenshot - part B work started = Deploy to Netlify" alt="" src="images/trello/2023-07-07_g.png">

<div style="page-break-after: always"></div>

## References

Chi, C 2021, ‘A Beginner's Guide to Data Flow Diagrams’, _HubSpot_, web log post, 13 May, viewed 1 July 2023, https://blog.hubspot.com/marketing/data-flow-diagram

Moqups 2023, _'What is a high fidelity wireframe?'_, viewed 1 July 2023, https://moqups.com/templates/wireframes-mockups/high-fidelity-wireframe/
