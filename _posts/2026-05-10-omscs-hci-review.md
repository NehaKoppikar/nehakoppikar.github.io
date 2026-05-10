---
layout: post
title: "OMSCS Course Review: CS 6750 Human-Computer Interaction"
date: 2026-05-10
tags: [omscs, hci, review]
description: "A deep dive into CS 6750 (Spring 2026), focusing on the journey from technical AI architecture to user-centered design."
---

### Background and Motivation
My journey into HCI began with a wake-up call during a project showcase for **Patchmomma**. I had recently built a complex multi-agent system using the Google Agent Development Kit (ADK), focusing heavily on technical architecture and scalability. While the backend logic was robust, the feedback was clear: I needed to work on my UI/UX skills. I realized then that even the most advanced AI system is only as effective as a user's ability to interact with it. To bridge the gap between backend data science and the end-user experience, I chose **CS 6750** as my very first course in the OMSCS program during the **Spring 2026** semester.

### What is HCI?
HCI is the study of how to design interfaces so well that humans don't even notice they are using them. It moves beyond "making things look pretty" and dives into the psychology of how people perceive, process, and act upon information.

### The Course Journey: A Deep Dive into Design
The course is a marathon of writing and iteration. Unlike other OMSCS classes that focus primarily on code, this is an exercise in industrial design and psychological frameworks. The curriculum is organized into distinct phases:

* **Pre-Course Phase:** Getting started with essentials like CITI training and syllabus comprehension.
* **Content Phase (Weeks 2–5):** Focused on lectures and homework assignments that apply HCI theory to real-world scenarios.
* **Practice Phase (Weeks 6–11):** A deep dive into readings, proctored quizzes, and the semester-long individual project.
* **Application Phase (Weeks 12–16):** Shifting focus to a collaborative team project, culminating in a final exam.
* **Victory Lap:** Final surveys and peer reviews.

**Rigor and Deliverables:**
* **4 Homework Assignments:** Rigorous deep dives into applying HCI theory.
* **4 Proctored Quizzes:** High-stakes, closed-resource exams testing fundamental principles.
* **2 Proctored Tests:** Open-resource exams (Ed Discussion and Canvas allowed) that require synthesizing a semester's worth of material under time pressure.
* **Project Milestones:** Both the Individual and Team projects follow a full design lifecycle from introduction and needfinding to prototyping and final evaluation results.

> **Pro-Tip:** Pay close attention to **Week 9**. It is particularly rigorous, requiring simultaneous completion of Test 1, Quiz 3, an individual project check-in, and a survey. Planning your time ahead is crucial here!

### The Learning Curve: From Theory to Practice
I used the course assignments as a playground to link abstract concepts to daily life. For instance, I explored the transition of an interface from "opaque" to "invisible" by analyzing the learning experience of the guitar. Initially, cognitive load is high as you consciously process finger placement and rhythm. Over time, this becomes procedural knowledge, and the guitar becomes an extension of your body.

I also tackled the **Gulf of Evaluation** in AI-assisted data analysis. My research into moving away from "black box" monolithic blocks toward **Stepwise interfaces** showed how users can externalize and verify an AI’s hidden assumptions, building higher levels of trust and agency.

### Individual Project Spotlight: Curing the "Mobile App Hack"
For my individual project, I focused on a universal frustration: **Queue Curation on the JioHotstar Set-Top Box (STB)**.

* **The Problem:** The STB lacked a native "Remove from Recently Viewed" function. This created a significant **Gulf of Execution**: users had a clear goal but no intuitive way to achieve it. This led to the **"Mobile App Hack,"** in which users would abandon their TV to delete items on their smartphone app just to trigger a cloud sync.
* **The Solution:** I designed a **Medium-Fidelity "Edit Mode" Toggle** prototype.
    * **Edit Mode Toggle:** A persistent pencil icon that allows users to enter a management state.
    * **Batch Processing:** Once in "Edit Mode," users can quickly navigate and remove multiple items using a "Red Circular Minus Icon" overlay on thumbnails.
    * **Timed Undo Toast:** A 5-second "Undo" notification serves as a safety net, providing user control and freedom.
* **Links:** [Video Demo](https://www.loom.com/share/b80e6e13fdb247b698278f8dcf0b4e89) | [Prototype](https://quote-hero-22379968.figma.site)

### Team Project (SNARK): Revolutionary Tab Management
My team focused on **browser tab overload**, a problem 82% of our surveyed users identified as a source of cognitive overload. We developed a **Visual-Recovery Hybrid** prototype that integrated hover-based previews for quick recognition and a recovery strip to undo accidental closures.

**Trivia:** Our team project was actually highlighted in the **Exemplary Team Project Submissions!**
* **Links:** [Video Demo](https://drive.google.com/file/d/1Jp2QxVKDnFlfQKDFWjak7LAsErfujHb9/view) | [Prototype](https://garb-coin-69107369.figma.site/)

### Tips for Success
* **Problem over Solution:** When choosing a project topic, focus on the problem first. The goal is to design based on research—using heuristic evaluations, surveys, and interviews—rather than starting with a pre-conceived solution.
* **You are not your user!** This is the course's golden rule. Never assume your mental model matches your user's.
* **Leverage Announcements:** Dr. Joyner's "Start of Week Announcements" are incredibly helpful for keeping up with the pace and knowing what to prioritize.
* **Iterate Early:** Use low-fidelity prototypes to get feedback before committing hours to high-fidelity designs.

### Concluding Thoughts
Choosing CS 6750 as my first OMSCS course was a rewarding decision. It shifted my perspective from being purely data-centric to being human-centric. While I cannot share full papers, the work within them—from prototypes to evaluations—has fundamentally changed how I build technical systems. I now have the framework to ensure the AI and multi-agent systems I build are not just powerful, but actually usable.