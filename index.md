# About Me

Hi! I'm Aarush Mehrotra, a computer science undergraduate at UC San Diego with a growing passion for **high performance computing (HPC)**, reproducible research, and building efficient systems.

Outside of programming, I’m an endurance athlete and triathlete in training. I started running just a few months ago and have since completed a sprint triathlon and a few runnign races. I've come to really appreciate the parallels between endurance training and deep work: both require patience, persistence, and a little bit of pain. *And both of them help keep me mentally and physically healthy!*

## My Philosophy

> **"I trust the process- but I still write logs."**  
> — *Aarush Mehrotra*


When I’m not writing code or logging miles ([follow me on Strava!](https://www.strava.com/athletes/154452286)), you’ll likely find me reading. You can check out what I’m currently reading or want to read next on [my Goodreads profile](https://www.goodreads.com/author/show/18552524.Aarush_Mehrotra). 

## HPC and Research Projects

As an **HPC Intern** at the San Diego Supercomputer Center, I work on adapting scientific Jupyter workflows to run efficiently on the [Expanse supercomputer](https://www.sdsc.edu/support/user_guides/expanse.html). I’m especially interested in the applications of HPC in fields like machine learning and finance.

Some highlights from my recent work and experiences:

- Member of the 2024 and 2025 UCSD Student Cluster Competition travel team.
- Fourth author on the ACM PEARC '24 paper “Preliminary Results of the MLPerf BERT Inference Benchmark on AMD Instinct GPUs”, which explores early benchmarking results for transformer-based NLP models on AMD’s MI250 architecture using MLPerf BERT Inference workloads.
- Helped build and scale a 16-node **Radxa Rock Pi cluster** using Ansible and other looks like OpenMPI and Spack.

Here's a picture of the corner of my work table, with my docked computer, headphones, and video games! [View image](./assets/img/desk-setup.jpeg)

## Tools & Workflow

Here’s a quick look at my development setup:

- Terminal tools: `vim`, `git`, `tmux`, `ssh`
- Editors: VSCode, Spyder, Jupyter Notebooks
- Platforms: GitHub, SDSC Expanse, local servers
> Believe it or not, I had access to ORNL's Frontier supercomputer for an internship last year! 
- Config management: Ansible

I enjoy building lightweight, reproducible workflows that can be scaled or migrated across platforms with minimal effort.

## Milestones and Goals

Below is a snapshot of my progress and roadmap:

### Completed
- [x] Built and deployed a 4-node Rock Pi cluster
- [x] Set up SSH and GitHub key-based workflows
- [x] Cloned and branched repos via CLI for coursework
Here are the commands I used for the above task: 
```bash
git clone https://github.com/iAarush/cse-110.git
cd cse-110 
git checkout -b add-read-me
vim README.md 
git add README.md 
git commit -m "Update readme file"
git push
git push --set-upstream origin add-read-me
git remote -v
git remote set-url origin git@github.com:iAarush/cse-110.git
git remote -v
git push --set-upstream origin add-read-me              
```

### In Progress
- [ ] Expand cluster to 16 nodes and improve Ansible playbooks (in progress)
- [ ] Improve my HPC setup documentation
- [ ] Write and present a follow-up research report based on all of the projects I've worked on the past year! 
- [ ] Restart my YouTube channel! 

### Academic & Professional Goals
1. Contribute to an open-source HPC project
2. Get a job after graduation (obviously, xD)
3. Build a public-facing HPC education resource

You can get a brief intro to this repository here: You can read more about my cluster setup [here](./readme.md) 

[Back to About Me](#about-me)
