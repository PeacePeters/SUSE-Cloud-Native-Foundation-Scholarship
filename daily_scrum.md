# Daily Scrum

## Sprint #2

__Day 1: 05/07/2021__

1. Yesterday, reviewed some exercises in lesson 3 & 5 and read some articles on [Python wheels](https://realpython.com/python-wheels/). I got to know they allow for faster installations and more stability in the package distribution. 
2. Today, played around with docker and kubernetes commands
3. Blockers: None

---

**Day 2: 06/07/2021**

1. Yesterday, played around with some docker and Kubernetes commands like 
   * `docker container stop <container-id` - stops a running container 
   * `docker rmi <repo_name/tag>` - removes image referenced in multiple repositories
   * `docker system prune` - cleans up any resources that are dangling not associated with a container like images, containers, etc
   * `docker system prune -a` - removes any stopped containers and all unused images
2. Today, reviewed lesson 2 and an amazing learning session during #crack-itTuesday in #l2_architecture_consideration channel
3. Key learning points:

---

**Day 3: 07/07/2021**

1. Yesterday, I had a refresher on lesson 2
2. Today, I reviewed the lessons on Kubernetes resources and an insightful SmartyWednesday session where we dived deep into API Versioning
3. Key learning points:
   * It is important to put much thought in API design and evolution or you'll lose customers fast!
   * If there are new features to be added then reuse the older version.
   * If there are breaking changes then we API version and commit to providing support for both.
   * All that matters at the end is $$ which comes from keeping your consumers satisfied.

---

**Day 4: 08/07/2021**

1. Yesterday, I reviewed lessons on Kubernetes resources and dived deep into [API versioning](https://blog.container-solutions.com/api-versioning-what-is-it-why-so-hard)
2. Today, I got an insight from a question asked by fellow scholar on [ingress & ingress controller](https://www.devopsschool.com/tutorial/kubernetes/kubernetes-ingress-tutorial.html).
Key learning points:
   * Ingress is an object that acts as gateway allowing access to Kubernetes services from outside the Kubernetes cluster by providing routing rules.
   * Ingress Controller is basically a pod which is also exposed using service (but in real word scenario it will be exposed using load balancer) which will give a static public ip.

---

**Day 5: 09/07/2021**

* Yesterday, read about API versioning.
* Today, worked on project
* Blockers: None

---

**Day 6: 10/07/2021**

1. Yesterday, worked on some projects
2. Today, attended an amazing ChocolateySaturday session anchored by @Verdoso and got to see how all the concepts learned in this Course come together in a real world project
3. Blocker: None

---

**Day 7: 11/07/2021**

1. Yesterday, attended ChocolateySaturday session and got to see how all the concepts learned in this Course come together in a real world project
2. Today, I unwind and relax with some EURO 2020 footballing actions:soccer: and got to celebrate with my Italian friends!:it::champagnepop:
3. Blockers: None

---

**Day 8: 12/07/2021**

* Yesterday: I rested and unwind with some footballing actions in EURO 2020
* Today, I reviewed lesson 3.1 - 3.8 on application packaging using Docker.
* Blockers: None

---

**Day 9: 12/07/2021**

---

**Day 10: 12/07/2021**

**Day 11/12: 12/07/2021**
1. Yesterday, I participated in #OpenSourceDay2021 and contributed to openSUSE project. I got to fix issues in some packages to enabled them for the s390x architecture.
2. Today, continued with #OpenSourceDay2021 and had an interesting & fun time working on Mainframe (LinuxOne) by building and resolving container images like httpd and tomcat.
3. Blockers: None
