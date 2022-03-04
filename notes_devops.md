# DevOps Basics - Containerization, CI/CD & Monitoring


## 1. DevOps - Intro

## 2. Docker - Intro

2.1 Terminology

- **Container Host** - a machine configured with a **container engine**
- **Container** - a runnable instance of **container image**. Containers are processes with much more isolation. 
- **Container image** - a read-only template of a container build from layers. Images provide a way for simpler software distribution.
- **Container OS image** - the first layer of potentially many layers that make up a container
- **Container Repository** - a collection of different versions of container image identified by tags.
- **Container Registry** - a collection of container repositories. 

2.2 Layers

2.3 Workflow


## 3. Docker - Advanced

## 4. Jenkins - Intro

4.1 Continuous  Integration & Delivery (CI/CD)
- **Continuous Delivery (CD)** - the ability to release at any time
- **Continuous Integration (CI)** - the practice of integrating or merging code changes frequently.
- **Stages of CD and CI**

Build => Deploy => Test => Release

4.2 Jenkins - Intro
- An open source automation server
- A platform for the **Software Development Life Cycle (SDLC)**
- Typically used to implement CI/CD
- Easy to use and highly adaptable
- Extensible and customizable
- Works on most common operating systems

4.2 Jenkins - Terms
- **Job** - Configured task in Jenkins. It is an old term
- **Project** - A task configured in Jenkins. It is the current term
- **Pipeline** - Special type of job created by a **Pipeline plugin**.

4.3 Jenkins - Plugins
- Default (minimal) set of plugins installed
- Grouped in categories by platform, purpose, etc.
- Dedicated Plugin Manager
- Automated or Manual installation

4.4 Jenkins - Scheduled Builds
- With plugin or native
- Two options
	- Execute once at a specific point in time
    - Regular execution
- Execution interval is set with a cron like syntaxis

4.5 Jenkins - Pipeline
- Old name is **workflows**
- Used for long running activity orchestration
- Can span on multiple nodes (slaves)
- It is a suite of plugins
- “Pipeline as code” is defined with a **Jenkinsfile**

4.6 Jenkinsfile
- It is **used to define continuous delivery pipeline**
- Stored together with our code
- Two styles are supported – **declarative** and **scripted**
- It is written in **Groovy**














