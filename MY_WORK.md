# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [layan wesam alaghbar] |
| **Student ID** | [446052621] |
| **University Email** | [446052621]@std.psau.edu.sa |
| **GitHub Username** | [Layan1234-wq] |
| **Repository Link** | (https://github.com/Layan1234-wq/OS-Assignment1-Layan-alaghbar)|
 
---

## 🎥 Video Link

**Video Link**: [[Paste your video link here](https://drive.google.com/file/d/1G7IShUSKFNk9Wdonzq_51CUWIrwFu2wN/view?usp=drivesdk)

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [october 7,2026]
**What I did**:I updated my student ID in the project.

**Details**: I opened SchedulerSimulation.java, changed the student ID, and committed the change to GitHub.

**Challenges**:I needed to make sure I was editing the correct student ID value.

**Solution**: I checked the code and updated the student ID in the correct place.

**Time spent**:5 minutes

---

### Entry 2 - [october 7,2026]
**What I did**:I worked on the Process Priority feature.

**Details**: I added a priority value for each process, from 1 to 10. I also made the priority appear when a process enters the ready queue. I tested the feature to check that it worked.

**Challenges**: I had difficulty finding the correct place in the code to make the changes.

**Solution**: I looked through the code to find where the changes needed to be made.

**Time spent**:30 minutes

---

### Entry 3 - [october 8,2026]
**What I did**:I implemented and tested the Context Switch Counter feature.

**Details**:I added a counter to track context switches during the scheduling simulation. The program displays the final count when the simulation ends. I ran the program and checked that the counter appeared in the output.

**Challenges**:I had difficulty understanding how the counter should work and when its value should increase.

**Solution**: I reviewed the code to understand when a new process starts running and how the counter should be updated.

**Time spent**:Less than 30 minutes.

---

### Entry 4 - [october 9,2026]
**What I did**:I implemented the Waiting Time Tracking feature.

**Details**: Added variables to track the process creation time and waiting time.

**Challenges**:I had difficulty deciding where to add the waiting time calculations in the existing code.

**Solution**: I reviewed the scheduler loop and the addProcessToQueue() method to place the calculations in the appropriate locations.

**Time spent**:2 hours

---

### Entry 5 - [10 October 2026]
**What I did**:I tested my program and checked the results.

**Details**:I checked if the priorities, context switch counter, and waiting times were working. I also checked the final table to make sure it showed the correct information

**Challenges**: I had some difficulty making sure all the features worked together\.

**Solution**: I ran the program a few times and checked the output to see if everything was working as expected

**Time spent**: 30 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [9 hours]

**Most challenging part**:The most challenging part was adding the new features and making sure they worked correctly with the existing code.

**Most interesting learning**: I learned how threads work in a scheduling simulation and how to calculate waiting time and turnaround time.

**What I would do differently next time**:I would organize my work better and test each feature after adding it instead of waiting until the end.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned that multithreading allows a program to do different tasks using threads. In my project, each simulated process is connected to a Java thread. The start() method starts a thread, and sleep() pauses it for some time.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part was calculating the waiting time. I was confused about where to add the new code. I needed to know when a process enters the ready queue and when it starts running. I used System.currentTimeMillis() to measure the waiting time. I also had to fix a variable naming problem in the code. After making the changes, I ran the program and checked the final table.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I worked on the assignment step by step. I looked at the existing code to understand how the scheduler works. I added the waiting time variables and methods to the Process class. I also checked where the process enters and leaves the ready queue.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is useful in many programs. For example, an operating system can share CPU time between different tasks. A web browser can use threads to handle different jobs at the same time. Round-Robin gives each ready process a turn to use the CPU. The time quantum limits the time given to each turn.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is a program in execution, while a thread is a unit of execution within a process. Each process has its own memory, but threads can share memory and resources. Creating a process usually requires more time and resources than creating a thread. We used threads in this assignment to simulate process execution in the CPU scheduler. In SchedulerSimulation.java, addProcessToQueue() creates a thread using new Thread(process), and currentThread.start() starts its execution.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[n Round Robin scheduling, a process returns to the ready queue if it does not finish during its time quantum. This allows other processes to use the CPU before getting another turn. In my project, P1 returned to the ready queue with 2769 ms remaining after its first turn.]

Example from my output:P1 completed quantum 2000ms ? Overall progress: [????????????????????] 41%
     Remaining time: 2769ms
  ? P1 yields CPU for context switch

  ? P1 added to ready queue ? Burst time: 4769ms ? Priority: 3
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[P1 was added back to the ready queue after its first and second turns because it still had time remaining. It finished during its third turn, so it was re-queued 2 times before completion.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 enters the New state when new Thread(process) creates its thread inside addProcessToQueue().]

2. **Runnable**: [P1 becomes Runnable when currentThread.start() is called in the scheduler loop, allowing the thread to be scheduled for execution.]

3. **Running**: [P1 executes the run() method, where it simulates CPU execution using Thread.sleep(stepTime).]

4. **Waiting**: [The main thread waits for P1 to finish its time quantum when currentThread.join() is called, while P1 enters the Timed Waiting state during Thread.sleep(stepTime).]

5. **Terminated**: [P1 enters the Terminated state when its run() method finishes executing.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling in an Operating System
]

**Description**:
[An operating system uses CPU scheduling to share CPU time among multiple processes. In Round-Robin scheduling, each process gets a small time quantum to execute. If a process does not finish, it returns to the ready queue so another process can run.]

**Why Round-Robin works well here**:
[Round-Robin provides fairness because each process gets a chance to use the CPU. It improves responsiveness because one process cannot keep the CPU for too long. In our simulation, the process represents a program, the time quantum represents the allowed CPU time, and the context switch represents moving CPU execution to another process.]

### Example 2: [A Multitasking Application]

**Description**:
[A multitasking application may use multiple threads to perform different tasks, such as updating the user interface, downloading data, and processing information. A scheduling system can give each task a short period to execute before allowing another task to run. This helps prevent one task from occupying the CPU for too long.]

**Why Round-Robin works well here**:
[Round-Robin can improve fairness by giving tasks opportunities to execute. It can also improve responsiveness by allowing other tasks to run regularly. In our simulation, each process represents a task, the time quantum is the time allowed for execution, and a context switch occurs when execution moves to another task]

## Summary

**Key concepts I understood through these questions:**
1.Threads have different lifecycle states, from New to Terminated.
2.Round-Robin scheduling gives each process a time quantum and re-queues unfinished processes.
3.Threads can share CPU time, and start(), join(), and sleep() have different roles.

**Concepts I need to study more:**
1.The differences between thread states and how thread methods affect them.
2.How time quantum size affects fairness and responsiveness in CPU scheduling.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
