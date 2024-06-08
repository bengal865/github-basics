**Lesson Plan: Git & GitHub Basics**

**Time Allotment:** 45 minutes

**Michigan CS Standards:** CP.A2.2.2, CP.A3.2.2

**Key Terms & Concepts:**

- Version control system (VCS)
- Git
- Repository
- Local vs. Remote Repository
- GitHub (optional)
- GitHub Desktop app

**Introduction (Hook - 5 minutes)**

Imagine you're building a complex program, like a game. Yesterday you added a new feature, but today it broke something else. Wouldn't it be amazing if you could rewind your code back to a stable version? That's exactly what Version Control Systems (VCS) like Git allow you to do! Today, we'll become code time travelers!

**Mini Lesson (8 minutes)**

- Play a short game of "Code Telephone." Students whisper a line of code to each other, then the last person writes it on the board. **Discuss how errors accumulate and how frustrating it can be to debug changes.**
- Transition to VCS as a solution. Show a simple analogy of version control with physical files (e.g., saving different drafts of an essay in Google Docs and the revision history of a Google Doc).
- Briefly introduce Git and repositories as the tools for code version control.

**Resources:**

- [Version Control with Git - Atlassian](<https://www.atlassian.com/git/tutorials>)
- [Git, GitHub & GitHub Desktop for Beginners](<https://www.youtube.com/watch?v=8Dd7KRpKeaE&pp=ygUYZ2l0IGdpdGh1YiBmb3IgYmVnaW5uZXJz>)

**Guided Practice (15 minutes)**

- **5 minutes:** Introduce the concept of **local** vs. **remote repositories**. Explain local as on your computer and remote as a central location (like GitHub). Briefly mention GitHub as an option, but the focus here is the core Git functionality.
- **10 minutes:** Students follow along with a teacher-led demonstration of initializing a local Git repository for a new project directory using git init.

**Station Rotations (12 minutes, 3 stations - 4 minutes each)**

**Station 1: Git Status**

- Students use git status to check the status of their newly created repository (the repo should be empty).

**Station 2: Adding Files**

- Students create a new text file with some code (e.g., a simple "Hello World" program) and add it to the Git staging area using git add <filename>.
- They then use git status again to see the change reflected.

**Station 3: Making a Commit**

- Students write a short commit message describing their changes (e.g., "Initial commit - Hello World program").
- They use git commit -m "<message>" to create the first snapshot of their code.
- Finally, they use git status one last time to verify the working directory is clean.

**Activities (5 minutes)**

- Have students brainstorm real-world scenarios where version control would be beneficial (e.g., collaborative projects, bug fixes, etc.).

**Independent Practice (5 minutes)**

- Students practice using git status on their existing school projects or create a small new project to experiment with Git commands.

**Assessment:**

- Observe students during station rotations and guided practice.
- Briefly discuss common mistakes or questions that arose during the station rotations or the guided practice activities

**Differentiation:**

- **Advanced:** Students can explore additional Git commands like git log to view the commit history.
- **Struggling:** Provide a step-by-step handout with the commands and explanations for each station.

**Discussion Questions:**

1. Why is version control important for software development? (Answer: Allows recovering from mistakes, tracking changes, and collaboration.)
1. What is the difference between a local and remote repository? (Answer: Local is on your computer, remote is a central location like GitHub.)
1. What is the purpose of a commit message? (Answer: Briefly describes the changes made in that commit for future reference.)


