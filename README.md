- 👋 Hi, I’m @KiNGxMiDAS, Welcome to my GitHub
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
KhaosxHacker/KhaosxHacker is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# Project 5

## Objective
Program is designed to simulate the producer/consumer problem. The idea behind the project is to familiarise oneself with the basics of the POSIX thread library.

### POSIX thread library .. ?
The POSIX thread libraries are a standards based thread API for C/C++. It allows one to spawn a new concurrent process flow. It is most effective on multi-processor or multi-core systems where the process flow can be scheduled to run on another processor thus gaining speed through parallel or distributed processing.

### Producer and Consumer Model
The producer and consumer model is to schedule how concurrent processes and threads access the resources. It contains:
1. **Producer:** One or multiple processes/threads that produce data or release hardware resource.
2. **Consumer:** The one process/thread that takes in data or uses hardware resource to do computations.
 * A producer could also be relatively a consumer to the output of another producer and vice versa.
3. **Buffer:** The destination to store the output from producers or resources and later accessed by another consumer.
* **Other concepts involved in our project:**
4. **POSIX thread:** Threads mechanism that satisfy POSIX standard (most operating system).
5. **Mutex:** A "lock" that guarantee that only one person has the access.



In this project we use POSIX threads. The "pthread" is a POSIX thread library written in C++ and provides the basic functions.

To simplify our simulation, we assume there are only 2 POSIX threads. One is the consumer, the other is the producer. The producer generates 1 unit data each time to the buffer, and the
consumer takes 1 unit data from the buffer each time. The size of the buffer is 1. One unit data is
just one integer. The producer generates integers 7, 14, 21 .... into the buffer and consumer read
them out from the buffer.
# Software-Construction

# Objectives
Software Construction (COMP 2710) is both a course on managing the complexity of large systems and an applied programming class. Managing software complexity requires some knowledge of software process. Applied programming means that you will be required to critically analyze real-world types of problems, design algorithms, and then implement those algorithms in high-level code to solve problems.
## Project Overview
### Project 1
A flow of control program that determines how many months it will take to pay of a loan given the loan amount and the interest rate.

### Project 2
Given three "players", the program will determine the winner of a duel between them based on individual probablities of a player landing a hit on another.

### Project 3
Program merges two lists from files and sorts them in numerical order. Program will then export the final sorted list into an output with the name of choice chosen by the user.

### Project 4
An implementation of a simple trivia game. It allows the user to come up with their questions and answers and can assigned points depending on the difficulty of the question. Players can win points by answering the questions correctly. Lastly, the program is organized and managed using a linked data structure.

### Project 5
Program is designed to simulate the producer/consumer problem -- (concurrency). The idea behind the project is to familiarise oneself with the basics of the POSIX thread library.

