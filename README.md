
<!-- [中文](https://github.com/ArweaveOasis/Arweave-AO-Dev-Learning/blob/main/README_CN.md) / English -->


# School of DumDum
<div>
  <p>
   Your one-stop journey to mastering Arweave AO development, organized by ArweaveOasis.
  </p>
  <p>
    <a href="https://x.com/ArweaveEco"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/ArweaveEco"></a>
    <a href="https://x.com/aoTheComputer"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/AO"></a>
    <a href="https://x.com/fwdresearch"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/fwdresearch"></a>
    <a href="https://x.com/ArweaveOasis"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/ArweaveOasis"></a>
  </p>
  <img src="https://github.com/ArweaveOasis/Arweave-Academy/blob/main/doc/image/school%20of%20dumdum.jpg" style="margin: 0 auto 40px;" />
</div>


## Overview
The School of DumDum is a part of Arweave Academy developer education program's. We offer developers free, high-quality courses and practical tasks to help them start building applications on Arweave and AO from scratch.

After completing the learning program, capable developers can participate in the Best Practices Contest.

We divided this event into two parts: one for beginners and one for advanced developers.
- Developers who are new to the Arweave and AO ecosystems can enter the Learning section, where they will complete their learning by studying courses and submitting tasks.
- For advanced developers, they can directly participate in the Practice section, which is a competition. You can choose a topic of your interest from the challange list and complete the practice by developing and writing tutorials. The best practices will be selected by judges and rewarded. 

The specific process is shown in the diagram below:

```mermaid
flowchart LR
    
    B[Developer Registration] --> C{Join the Event}
    
    C -->| Learning | D[Learn the Courses] --> E[Submit Tasks]
    C -->| Practice | F[Practice Contest]

    B:::clickableLink
      class B clickableLink;
      click B "https://github.com/ArweaveOasis/Arweave-Academy#registration" "Go to Registration Step"

    D:::clickableLink
      class D clickableLink;
      click D "https://github.com/ArweaveOasis/Arweave-Academy#course-guideline" "Go to Course Guideline Step"
    
    E:::clickableLink
      class E clickableLink;
      click E "https://github.com/ArweaveOasis/Arweave-Academy#task-submission" "Go to Course Guideline Step"

    style C fill:#FFF9C4,color:#000000,stroke:#000000

```
<br>

## Preparation
Before participating in the event, here’s what you need to prepare:
- Please prepare your AR wallet -- [Arconnect](https://www.arconnect.io/)
- An all-in-one Arweave AO relevant documentation list -- [awesome-ao](https://github.com/ArweaveOasis/awesome-ao)
- Arweave block explorer -- [viewblock](https://viewblock.io/arweave)
- AO explorer -- [aolink](https://www.ao.link/)

<br>

## Registration
Developers need to complete GitHub registration by following these steps:

1. `Star` and `Fork` this repository and `clone` it to your local.
2. Navigate to the `submissions` folder and create a new folder named after your GitHub username: `YourName`.
3. Copy the [Template.md](./template.md) file into the newly created folder and rename it to your name: `YourName.md`.
4. Open the `submissions/YourName/YourName.md` file, fill in your information as instructed, and save it.
5. Submit a `PR` to this repository. Once your PR is merged, your GitHub registration is complete. 

   👉 Here is the tutorial about [How to Submitting a PR on Github](./doc/How%20to%20Submitting%20a%20PR%20on%20Github.md)
6. After you complete the registration process, please join in the [Discord channel](https://discord.gg/Z7R7Az6T).

<br>


## Task Submission
After each course, there will be a series of tasks. These tasks are the primary way to assess whether you have mastered the course content. 

For example, to submit `task1`, follow these steps:

1. Create a `task1` folder under `submissions/YourName`.
2. Place your task files inside the `task1` folder. You can also create a `readme.md` file to organize your task content. (Submission of learning notes and reflections is encouraged.)
3. Submit a `PR` (Pull Request) to this repository. Once the `PR` is merged, `task1` will be considered complete.

⚠️ Each **Task** must be submitted separately. A single `PR` containing multiple **Tasks** will be closed directly.

<br>

## Course Guideline
The specific course details will be announced on **January 8, 2025**.

### Level 1 Introduction to Arweave and AO
**Module 1: Understanding Arweave**

1. Intro to Arweave | [Learn](https://academy.developerdao.com/tracks/arweave-101/1)
    - What is Arweave?
    - How does Arweave Work?
    - Permanent Storage Through Consensus and The Endowment
    - Arweave Transactions
    - Smart Contracts as Add-Ons

2. Storing Data on Arweave | [Learn](https://academy.developerdao.com/tracks/arweave-101/3)
    - How to Store Small Files on Arweave?
    - What are Popular Arweave Bundling Services and SDKs?
    - What are Popular Arweave Wallets?

3. Why should developers care about Arweave？| [Learn]()

| Task | Topic | Status |
|-------|-------|-------|
| [task1](./task/task1.md) | 6 Quizs for "Intro to Arweave" | Not Start |
| [task2](./task/task2.md) | 8 Quizs for "Intro to Arweave" | Not Start | 
| [task3](./task/task3.md) | 9 Quizs for "Storing Data on Arweave" | Not Start |

<br>

**Module 2: Basic development on Arweave**

1. Access Data on Arweave | [Learn](https://academy.developerdao.com/tracks/arweave-101/2)
    - How to Access Files on Arweave?
    - How to Access Directories on Arweave?
    - How to Find Files on Arweave With GraphQL?
    - How to Find Files on Arweave With Subdomains?

2. Building a static website on Arweave | [Learn](https://academy.developerdao.com/tracks/arweave-101/4)
    - Creating Your Website
    - Deploying Your Website to Arweave
    - Creating a Human-Friendly Name For Your Website

3. Build a Dapp on Arweave | [Learn](https://academy.developerdao.com/tracks/arweave-101/5)
    - Creating the DApp
    - Deploying the DApp
    - Creating a Human-Friendly Name for the DApp


| Task | Topic | Status |
|-------|-------|-------|
| [task4](./task/task4.md) | 6 Quizs for "Access Data on Arweave" | Not Start |
| [task5](./task/task5.md) | 6 Quizs for "Access Data on Arweave" | Not Start | 
| [task6](./task/task6.md) | 6 Quizs for "Building a static website on Arweave" | Not Start |
| [task7](./task/task7.md) | 6 Quizs for "Building a static website on Arweave" | Not Start |
| [task8](./task/task8.md) | 6 Quizs for "Build a Dapp on Arweave" | Not Start |
| [task9](./task/task9.md) | 6 Quizs for "Build a Dapp on Arweave" | Not Start |
| [task10](./task/task10.md) | 6 Quizs for "Build a Dapp on Arweave" | Not Start |

<br>

**Module 3: TBD**  
**Module 4: TBD**


<br>


## Tasks
Developers who complete all the courses and submit the tasks for this session will receive a Level 1 NFT. If you collect all 4 Levels of NFTs in the future, you will be awarded a final graduation certificate and become a priority candidate in our talent pool, gaining access to more ecosystem job opportunities.
| Level | Module | Task | Topic | Status |
|-------|--------|-------|-------|-------|
|   1   |    1   | [task1](./task/task1.md) | --- | Not Start |
|       |        | [task2](./task/task2.md) | --- | Not Start | 
|       |        | [task3](./task/task3.md) | --- | Not Start |
|       |    2   | [task4](./task/task4.md) | --- | Not Start |
|       |        | [task]() | --- | Not Start |
|       |        | [task]() | --- | Not Start |

<br>
