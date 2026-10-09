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
| **Full Name** | [Write your full name here] |
| **Student ID** | [Write your student ID here] |
| **University Email** | [yourid]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - [October 5, 2026, 10:52 PM]
**What I did**:I used my student ID to customize the simulation.

**Details**:
- In SchedulerSimulation.java, set studentID to 446051847.
- This ID served as the initial Random generator's seed.
- 12 processes are displayed in the provided output.

**Challenges**:Adding new features while maintaining reproducibility in the simulation parameters is a challenge.


**Solution**:The original student-ID-based generator for the time quantum, number of processes, and burst times was retained as the solution.

**Time spent**:30 minutes

---

### Entry 2 - [October 7, 2026, 6:39 PM]
**What I did**:The process-priority feature was added.

**Details**:
- Added the setPriority() and getPriority() methods, as well as the priority field, to Process.
- A priority was established.Use the seed studentID + 1L at random.
- 1 + priorityRandom.nextInt(10) was used to assign priorities.
- Priority was printed each time a process joined the ready queue.
- FIFO ordering was maintained; scheduling order is not altered by priority. 

**Challenges**:Creating priorities without altering the Round-Robin queue order or current burst times is a challenge.


**Solution**:The solution was to keep the LinkedList-based FIFO queue while using a different random generator for priorities.


**Time spent**:45 minutes

---

### Entry 3 - [October 7, 2026, 10:08 PM]
**What I did**:To imitate context shifts, I added a counter.


**Details**:
- SchedulerSimulation now has a private static int contextSwitches = 0.
- It was promptly increased before to each current thread.call to start().
- After the simulation was finished, the counter was printed.
- The output that was provided reports 28, which corresponds to the 28 worker execution turns.

**Challenges**:Determining precisely which scheduling events the counter reflects is one of the challenges.

**Solution**:The solution was to count every worker dispatch, including the initial dispatch, and record this practice in the code comments.

**Time spent**:25 minutes

---

### Entry 4 - [October 8, 2026, 1:28 AM]
**What I did**:I added the final timing table and cumulative waiting-time tracking.

**Details**:
- CreationTime, queueEntryTime, waitingTime, and firstQueueEntry were added to Process.
- To determine the start of each waiting interval, recordQueueEntry() was utilized.
- Prior to initiating a worker, recordDispatch() was called in order to accumulate the worker's waiting interval.
- GetWaitingTime() and getTurnaroundTime() were added.
- One summary row was printed for each process, and each process was stored once in allProcesses.
  
**Challenges**:Waiting after re-queueing and preventing duplicate summary rows for processes that use multiple worker threads are two challenges.

**Solution**:The final table was created by adding up each queue-waiting interval and using allProcesses instead of the thread map.

**Time spent**:70 minutes

---

### Entry 5 - [October 8, 2026, 1:30 AM]
**What I did**:The modified simulation was run, and the final console output was obtained.

**Details**:
- Priorities, a final dispatch count of 28, and a timing table for each of the 12 processes are displayed in the output.
- P1 has a burst time of 10200 ms and a priority of 5.
- Following its initial insertion, P1 runs for 5000, 5000, and 200 ms with two re-queues.
- According to the table, P1 had a turnaround time of 99399 ms and was waiting for 89199 ms.
- Every process includes a completion message in the output that is provided.

**Challenges**:One of the challenges is separating measured waiting times, which can vary between runs, from reproducible simulation inputs.

**Solution**:The solution was to keep wall-clock measurements for waiting time and use the actual recorded output for numerical examples.

**Time spent**:25 minutes

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [3 hours 15 minutes]

**Most challenging part**:Confirm whether this matches your experience

**Most interesting learning**:Confirm whether this matches your experience

**What I would do differently next time**:Confirm whether this matches your experience

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

[I discovered that the work that a Java thread can perform is defined by implementing Runnable. The Process class in this simulation implements Runnable, and addProcessToQueue() uses new Thread(process) to create a worker. While calling run() directly would execute the method on the calling thread, calling start() schedules that worker to execute run(). In order for the main thread to wait for the current worker to finish before choosing another process, the scheduler calls join(). Instead of carrying out CPU-intensive tasks, Thread.sleep() inside run() simulates elapsed execution time. Additionally, I discovered that when a worker thread in a simulated process ends, another thread is created for the process's subsequent turn.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Differentiating between the simulated Process object and the Java thread that runs it was the idea that I found most difficult. In between scheduling turns, the Process object maintains its remainingTime. Nevertheless, each worker thread only calls run() once before ending. This indicates that there isn't a worker thread that runs continuously in an incomplete operation. P1 requires three execution turns in the given output, despite the fact that each turn makes use of a separate Java thread. Knowing this difference made it easier for me to understand why, each time a process is re-queued, addProcessToQueue() generates a new thread.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[By dividing the code into manageable chunks and attempting to comprehend each one independently, I was able to overcome the difficulties. I reviewed the assignment instructions and compared them with the code whenever something was unclear. To check what transpired after each move, I followed P1 in the output. This made it easier for me to understand why it went back to the line twice before it was done. I also reviewed the explanations against my code and requested for assistance with the bits I didn't understand. The assignment was simpler to comprehend when it was done step-by-step.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Applications that use multithreading can maintain a responsive user interface while background processing is ongoing. A background thread can be used by a music player to load audio while user input is handled by the interface. Multiple requests can be handled by a server using worker threads, albeit the server design determines the scheduling policy. Because distinct threads carry out specified tasks and may exchange application data, these instances relate to the assignment. A responsive interface, in contrast to this simulation, should call join() on its interface thread without waiting for each background process. When several threads access shared changeable data, real applications also require proper synchronization.]

### Optional: What would you like to learn more about?

[I want to know more about thread pools, locks, race situations, and synchronized blocks. Additionally, I want to look into how responsiveness and scheduling overhead are impacted by the time quantum and compare Round-Robin with priority scheduling.]

### Optional: How confident do you feel about multithreading concepts now?

[Intermediate, based on what I now understand. I am able to describe Runnable, join(), sleep(), and the distinction between a worker thread and a simulated process. I still need to practice synchronization and apps that require multiple workers to operate simultaneously.]

### Optional: Feedback on the assignment

[The simulation offers a helpful link between ideas of operating-system scheduling and Java threading. The scheduling sequence is simpler to follow thanks to the ready queue and remaining-time output. Before executing a larger simulation, students could verify waiting-time calculations using a tiny deterministic example.]

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

[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[Write your answer here.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When and why would a thread be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[Describe the real-world scenario.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

### Example 2: [Name of application/scenario]

**Description**:
[Describe the real-world scenario or application.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

## Summary

**Key concepts I understood through these questions:**
1.
2.
3.

**Concepts I need to study more:**
1.
2.

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
