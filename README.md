# Personal Portfolio Blog (Activity 12)

**Live Portfolio URL:** [https://gandharvak312.github.io](https://gandharvak312.github.io)

This repository contains my AI-generated personal portfolio website, created as part of the Portfolio Building course (B25CS0311).

---

## 1. Portfolio Brief
**Name:** Gandharva C Kulkarni
**Semester/Branch:** 3rd Semester, B.Tech CSE

**Bio:** 
I am a 3rd-semester Computer Science and Engineering student passionate about software development and algorithmic problem-solving. I am currently building my foundational skills in C, Python, and Git/GitHub.

**Projects (Activities 1-4):**
1. **Hello World:** My first version-controlled repository to understand the basics of Git, commits, and pushing to a remote server.
2. **Pair Programming:** A collaborative session where I used GitLens and VS Code Live Share to write code synchronously with a peer, managing merge conflicts and branch workflows.
3. **LeetCode Solutions:** A structured, documented repository tracking my problem-solving progress across data structures like arrays, strings, and linked lists, complete with time/space complexity analysis.

**Skills:** C, Python, Git/GitHub, HTML/CSS, Data Structures & Algorithms.

**Goal:** I am looking for a summer internship where I can apply my programming skills to a real-world codebase and learn from experienced backend engineers.

---

## 2. Prompt Log

| Prompt Type | The Prompt Used | What Changed (Before / After) |
| :--- | :--- | :--- |
| **Initial** | "Act as an expert web developer. Create a single-page personal portfolio blog in HTML and inline CSS based on this brief: [Inserted Brief above]. It should have a modern, clean, dark-mode design with sections for About, Skills, Projects, and Contact. Include links to my GitHub projects." | **Before:** No code existed. <br>**After:** The AI generated a complete HTML structure with a dark mode theme, but the About section was too long and the project links were dead placeholders. |
| **Refinement 1** | "The About section is too long. Shorten it to exactly three sentences focusing on my major, my current learning focus, and my internship goal." | **Before:** The bio was a massive, hallucinated block of filler text. <br>**After:** The text was successfully condensed into three punchy, accurate sentences. |
| **Refinement 2** | "Update the Projects section to include these exact links: 'https://github.com/gandharvak312/hello-world' and 'https://github.com/gandharvak312/leetcode-solutions'. Style these links to look like clickable buttons." | **Before:** Standard blue hyperlinks pointing to nowhere. <br>**After:** Accurate URLs were injected, and the AI added CSS padding and hover effects to make them look like professional UI buttons. |

---

## 3. Reflection
The follow-up prompt that produced the biggest improvement was asking the AI to style the raw text links into visual buttons, which immediately made the page look and feel like a real portfolio rather than a standard text document. One thing the AI got wrong initially was inventing a lot of generic "filler" text for my bio that wasn't in my original brief; I had to explicitly constrain it to three sentences to fix the hallucination.