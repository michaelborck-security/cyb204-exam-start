# CYB204 Ethical Hacking - Final Practical Exam

This repository contains the necessary files to start your practical exam environment.

## ⚠️ Prerequisites

Before you begin, you **must** have **Docker Desktop** (for Mac or Windows) or **Docker Engine** (for Linux) installed and running on your system.

## 🚀 Exam Start Instructions

Follow these steps exactly to begin your exam.

**1. Clone this Repository**
Open your terminal and clone this repository to your computer:

```bash
git clone [https://github.com/michaelborck-security/cyb204-exam-start.git](https://github.com/michaelborck-security/cyb204-exam-start.git
````

**2. Change Directory**
Move into the folder you just cloned:

```bash
cd cyb204-exam-start
```

**3. Start the Exam Environment**
Run the following command. This will download (pull) the necessary Docker images and start the isolated exam network in the background.

```bash
docker-compose up -d
```

*(This may take a few minutes the first time as it downloads the images.)*

**4. Enter the Attacker Machine**

To begin the exam, connect to your attacker machine's shell by running:

```bash
docker exec -it kali-attacker /bin/bash
```

You will be greeted with a welcome message. Follow the instructions on your screen to begin. Good luck.

-----

### 🛑 How to Stop the Environment

When you are finished with the exam, you can stop and remove the containers by running:

```bash
docker-compose down
```

```
