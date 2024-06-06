### Level 1: Hands-On Open Source Contribution Session - Detailed Notes for Students

---

**Welcome to Level 1 - Hands-On Session**

Today, we explored how to contribute to an open source project using GitHub. The primary goal was to understand how to create a new project, manage repositories, and contribute to our club's open source handbook. This session aimed to provide you with hands-on experience and a solid foundation in using GitHub for version control and collaboration.

---

**Recap of Level 0**

In our previous session, we introduced the concept of open source through the Chef analogy. We compared two types of chefs: one who keeps his recipes secret (closed source) and one who shares them openly (open source). This analogy helped illustrate the differences between closed and open source software and their respective benefits and drawbacks. If you missed this session, please watch the previous video on [YouTube](https://www.youtube.com/channel/UCvJH8tjhhPNfOFAn1uaN80g) and [Twitter](https://x.com/umunbeing) to catch up.

---

**Origin of Git and SVN**

**Git:** Git was developed by Linus Torvalds in 2005 for managing the development of the Linux kernel. Git is a distributed version control system known for its speed, efficiency, and ability to handle projects of all sizes. It allows multiple developers to work on the same project simultaneously without overwriting each other's changes. Git's distributed nature means that every user has a complete copy of the repository, making it resilient and flexible.

**SVN (Subversion):** Subversion, or SVN, is an older version control system that predates Git. It is a centralized version control system where the repository is stored in a single central server. Developers check out copies of the repository to work on, and changes are committed back to this central server. SVN was widely used before Git became popular and is still in use in many legacy projects.

**Linus Torvalds:** Linus Torvalds is best known as the creator of the Linux operating system and Git. His work on Git revolutionized the way developers collaborate on software projects, making version control more robust and accessible.

For more information, visit:
- [Git](https://git-scm.com/)
- [SVN](https://subversion.apache.org/)
- [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds)

---

**Open Sourcing Educational Content**

I believe that education should be free and accessible to everyone. Therefore, I am open sourcing all the notes, lecture materials, presentations, and other educational content from our sessions. This approach ensures that anyone interested in learning can benefit from these resources. 

**Call to Action:** I urge teachers and content creators to review these notes. If you find any discrepancies or have suggestions for improvement, please fork the repository and submit a pull request. Your contributions will help make this material even more valuable.

**Share and Use:** Feel free to use these notes for your own lectures and share detailed notes with your students. By making this content open source, we aim to foster a collaborative learning environment.

**MCQs:** I have also prepared multiple-choice questions (MCQs) for assessment purposes. However, deciding whether to make these open source is still under consideration.

---

**Introduction to GitHub**

GitHub is a web-based platform that provides hosting for software development and version control using Git. It allows developers to collaborate on projects from anywhere in the world. GitHub repositories can be public or private, depending on the visibility settings chosen by the user.

**Repositories:** A repository (often abbreviated as "repo") is a storage space where your project files and their revision history are stored. It serves as a central location where developers can collaborate, track changes, and manage project versions.

**Creating a New Project:** To create a new project on GitHub, follow these steps:
1. Sign in to your GitHub account.
2. Click on the "New Repository" button on the GitHub homepage.
3. Fill in the repository details such as name, description, and visibility (public or private).
4. Click "Create repository."

For more details, visit [GitHub](https://github.com/).

---

**Creating a New Repository with the Chef Example**

In this example, we created a new repository for a chef's recipes to illustrate the process. This project includes a README file to introduce the idea and two separate files for recipes.

**Adding a README:** The README file serves as an introduction to your project. It typically includes the project title, a brief description, and instructions on how to use the project. The README is often the first file a visitor to your repository will see.

**Creating Recipe Files:** We created two separate files for the recipes, for example, `recipe1.md` and `recipe2.md`. Each file contains the details of a specific recipe.

**Linking Files:** To link these recipe files in the README, we used Markdown. Markdown is a lightweight markup language with plain text formatting syntax. Here’s an example of how to link files in a README using Markdown:
```markdown
[Recipe 1](recipe1.md)
[Recipe 2](recipe2.md)
```

---

**Understanding Markdown Files**

Markdown is a simple and easy-to-use syntax for styling all forms of writing on the GitHub platform. It allows you to format text, create lists, and include links without having to write complex HTML.

**Basic Syntax:**
- **Headings:** Use `#` for headings. For example, `# Heading 1`, `## Heading 2`, etc.
- **Links:** To create a link, use `[Link text](URL)`. For example, `[GitHub](https://github.com/)`.
- **Lists:** Use `-` or `*` for unordered lists, and numbers for ordered lists.

Markdown is particularly useful for writing README files, documentation, and comments. For more details, visit the [Markdown Guide](https://www.markdownguide.org/).

---

**Example: Club's Open Source Handbook Project**

Our club's open source handbook is a collaborative project designed to document open source contributions and guidelines. This project is being prepared by club members and is open to contributions from anyone interested in participating.

**Join Us:** To join our club, you need an invitation and must win a bounty. Start by contributing to our handbook. Your first step can be writing yourself into our handbook forever by creating your own "resume"/profile.

---

**Starring and Forking the Project**

**Star the Project:** Starring a project on GitHub is a way to show your appreciation for the project. It helps you keep track of repositories that you find interesting.

**Fork the Project:** Forking a repository creates a personal copy of the repository under your GitHub account. This allows you to experiment with changes without affecting the original project. Forking is essential for contributing to open source projects because it provides you with a safe space to make and test changes.

For more information on forking, visit [Forking on GitHub](https://guides.github.com/activities/forking/).

---

**Making Changes to the Project**

**Edit Your Profile:** In your forked repository, you can create a new file or edit an existing one to add your "resume"/profile. For example, you could create a file named `profile.md`.

**Commit Changes:** Committing is the process of saving your changes to the repository. Each commit should have a descriptive message explaining what changes were made. This helps maintain a clear history of modifications. To commit changes:
1. Make your changes in the file.
2. Write a descriptive commit message explaining what you did.
3. Click the "Commit changes" button.

For more details on committing, visit [Committing on GitHub](https://docs.github.com/en/github/committing-changes-to-your-project).

---

**Creating a Pull Request**

**What is a Pull Request?**
A pull request (PR) is a method of submitting contributions to an open development project. It allows you to notify project maintainers about changes you’ve pushed to a fork of their repository. The maintainers can then review and discuss your changes before merging them into the main project.

**How to Create a PR:**
1. Navigate to your forked repository.
2. Click the "New Pull Request" button.
3. Compare your changes with the original repository.
4. Write a descriptive title and message for your PR.
5. Click "Create Pull Request".

For more information on creating pull requests, visit [Creating a Pull Request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

---

**Review and Merge**

**Maintainer Review:** Once you have created a pull request, a project maintainer will review your changes. They might provide feedback, ask for modifications, or approve the changes.

**Merge:** If your changes are approved, the maintainer will merge them into the original project repository. This means your contributions will become part of the project.

**Comments:** If there are issues with your pull request, the maintainer may add comments requesting modifications. You can then make the necessary changes and update the pull request.

For more information on merging pull requests, visit [Merging a Pull Request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/merging-a-pull-request).

---

**Explanation of Key Terms**

**Repository:** A storage space for project files and their revision history.

**Fork:** Creating a personal copy of someone else's repository.

**Commit:** Saving changes to the repository with a message explaining the changes.

**Pull Request:** Proposing changes to the original project repository.

**Maintainer:** A person responsible for reviewing and managing contributions to a repository.

**Merge:** Incorporating proposed changes into the original project.

**Comments:** Feedback provided by maintainers or collaborators on a pull request.

---



**Live Demo with Prakrati**

During the live demo, we walked through the entire process with Prakrati as the example student. Here are the steps we covered:
1. **Forking:** Prakrati forked the repository to her own GitHub account.
2. **Making Changes:** Prakrati added her profile to the project by creating a new file.
3. **Committing:** Prakrati committed her changes with a descriptive message.
4. **Creating a PR:** Prakrati created a pull request to propose her changes to the original repository.
5. **Review and Merge:** The maintainer reviewed and merged Prakrati’s pull request.

This interactive session was designed to provide hands-on experience and encourage students to ask questions and follow along.

---

**Version Control and Its Importance**

**Analogy:** Imagine three friends working on a school project:
- **Without Version Control:** Each friend works on their own copy, leading to confusion and multiple conflicting versions.
- **With Version Control:** All changes are tracked, merged systematically, and everyone is on the same page.

**Explanation:** Version control systems like Git track changes, facilitate collaboration, and manage versioning efficiently. They help teams work together more effectively by providing tools to merge changes, resolve conflicts, and maintain a history of modifications.

---

**Club's Own Application**

**Project Overview:** Our club is developing its own application to simplify the joining and bounty hunting process. This project aims to make the process easy and engaging.

**Tech Stack:** The application is built using full stack React, Supabase, and Tailwind. These technologies are popular for building scalable and responsive web applications.

**Call to Action:** If you want to learn full stack React development or already have the skills, we invite you to join our open source efforts and contribute to the project.

**Bounties:** We also offer bounties for addressing issues in the project. This means you can learn, work with mentors and squads, and earn while you learn.

**Mentors:** We are looking for mentors to guide and inspire curious minds. Join us as a maintainer or mentor and receive 40% of the bounty budget.

For more information on the technologies, visit:
- [React](https://reactjs.org/)
- [Supabase](https://supabase.io/)
- [Tailwind CSS](https://tailwindcss.com/)

---

**Preparing for the MCQ**

**Review Key Points:** Ensure you understand the following concepts:
- Forking a repository
- Committing changes
- Creating pull requests
- Reviewing and merging pull requests

**Practice Questions:** Reviewing these key points will help you prepare for the multiple-choice questions that assess your understanding of the material.

---

**Questions & Answers**

We concluded the session with an open floor for questions. This was an opportunity to clarify any doubts and provide additional assistance. Always feel free to reach out with questions or for further guidance.

**Example Questions:**

1. **What is the purpose of forking a repository on GitHub?**
   - A) To delete the original repository
   - B) To create a personal copy of someone else's repository for experimentation
   - C) To lock the repository
   - **Answer: B**

2. **What does committing changes mean in GitHub?**
   - A) Deleting files from the repository
   - B) Saving changes to the repository with a descriptive message
   - C) Sharing the repository publicly
   - **Answer: B**

3. **What is a pull request in GitHub?**
   - A) A request to delete a repository
   - B) A method to propose changes to the original repository
   - C) A way to star a repository
   - **Answer: B**

4. **Who is responsible for reviewing and merging pull requests?**
   - A) The original creator of the repository
   - B) A project maintainer
   - C) Any user who stars the repository
   - **Answer: B**

5. **What is the significance of a README file in a GitHub repository?**
   - A) It stores the main executable files
   - B) It provides an introduction and instructions for the project
   - C) It hides the source code
   - **Answer: B**

---

**Thank You & Next Steps**

Thank you for participating in this hands-on session. Your engagement and effort are greatly appreciated. We encourage you to continue contributing to open source projects and explore further learning tracks. Keep practicing, stay curious, and happy coding!

**Achievements:** Everyone whose pull request gets merged and scores 70% or more in the MCQs will receive the Level 1 badge and an open source contribution certificate.

---

**Stay Connected**

This lecture was prepared by Abhinav Singhal. You can watch this session later on:
- [Twitter](https://x.com/umunbeing)
- [YouTube](https://www.youtube.com/channel/UCvJH8tjhhPNfOFAn1uaN80g)

Please follow me on Twitter [@umunbeing](https://x.com/umunbeing) and subscribe to my YouTube channel. My GitHub profile is [github.com/iabhinav](https://github.com/iabhinav) — consider following me there as well.

Also, join the Dominate X Club's Discord server [here](https://discord.gg/cGAEvjcv) for more learning sessions, bounties, notes, and to find like-minded friends and future colleagues and co-founders.
