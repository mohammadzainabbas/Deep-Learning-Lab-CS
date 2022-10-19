## Lab Work @ Deep Learning at CentraleSupélec 👨🏻‍💻

#
### Table of contents

- [Introduction](#introduction)
- [About the course](#about-course)
  * [Main Topics](#main-topics)
- [Labs](#labs)
  * [Lab 01 - NetworkX](#lab-1)
- [Setup](#setup)
  * [Create new enviornment](#create-new-env)
  * [Setup `pre-commit` hooks](#setup-pre-commit)


#

<a id="introduction" />

### 1. Introduction

The main goal of this course is to present the basics of `Deep Learning` and some of its _applications_. It is based on several widely known courses that has proven effective such as the [Deep Learning Book]() and Dive into Deep Learning website.

We will take interest in various domains of Deep Learning such as Computer Vision, Generative Models, and Natural Language Processing, To put into application what you will learn, various practical sessions will be performed along with a small project on a specific task.

#

<a id="about-course" />

### 2. About the course

Data we produce or consume has increasingly networked structures which have grown in complexity in different domains such as `biology`, `social networks`, `economy`, `communication` and `transport networks`. The need to process and to analyze such data carries out the emergence of network science research community to define algorithms which allow to characterize such complex structures, to understand their topology, their evolution and to interpret the underlying phenomena. 

Besides, the distributed storage and parallel computation technologies offer specific tools for networks based on large-scale graph processing paradigms such as `MapReduce` and `Pregel` of Google.

The purpose of this course is to study the main algorithms and their implementation on artificial and real data in a distributed environment.

<a id="main-topics" />

#### 2.1. Main Topics

- [x] Preliminaries, Typology of graphs, Graph analytics measures
- [x] Basic algorithms: Random walk and Page Rank
- [x] Label propagation, Community detection, Influence maximisation
- [x] Graph analytics & Deep Learning

#

<a id="labs" />

### 3. Labs

The main aim of this repository is to keep track of the work we have done in __Massive Graph Management and Analytics (MGMA)__ labs. During this course, we will focus on some basic graph algorithms and see how we can utilise these algorithms to efficiently analyse our data. Since, there exist many similarities between graph theory and network science, you will see us using network science related packages as well.

#

<a id="lab-1" />

#### 3.1. Lab 01 - NetworkX

[NetworkX](https://networkx.org/) is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.

Please checkout lab's details [here](https://github.com/mohammadzainabbas/MGMA-Lab/tree/main/src/lab1) 

#

<a id="setup" />

### 4. Setup

If you want to follow along with the lab exercises, make sure to clone and `cd` to the relevant lab's directory:

```bash
git clone https://github.com/mohammadzainabbas/MGMA-Lab.git
cd MGMA-Lab/src/<lab-of-your-choice>
```

> For e.g: if you want to practice lab # 1, then you should do `cd MGMA-Lab/src/lab1`.

<a id="create-new-env" />

#### 4.1. Create new enviornment

Before starting, you may have to create new enviornment for the lab. Kindly, checkout the [documentation](https://github.com/mohammadzainabbas/MGMA-Lab/blob/main/docs/SETUP_ENV.md) for creating an new environment.

#

Once, you have activated your new enviornment, we may have to install all the dependencies for a given lab (kindly check if `requirements.txt` file exists for a given lab before running the below command):

```bash
pip install -r requirements.txt
```

<a id="setup-pre-commit" />

#### 4.2. Setup `pre-commit` hooks

In order to setup `pre-commit` hooks, please refer to the [documentation](https://github.com/mohammadzainabbas/MGMA-Lab/blob/main/docs/SETUP_PRE-COMMIT_HOOKS.md).

#

