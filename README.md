# CS 6316 Machine Learning
  

## 1. Basic Information

- Instructor: [Yangfeng Ji](http://yangfengji.net)
- Semester: Spring 2020
- Location: Olsson Hall 011
- Time: Tuesday and Thursday 5:00 PM - 6:15 AM
- TA: Hanjie Chen, Kai Lin
- Office Hours: 
	- Yangfeng Ji: Wednesday 11:00 AM - 12:00 PM, Rice 510
	- Hanjie Chen: Tuesday/Thursday 1:00 PM - 2:00 PM, Rice 442

## 2. Highlights

- [Information for Online Lectures](online.md)
- [Course schedule](schedule.md)
- [Grading policy](grade.md)
- [Piazza](https://piazza.com/class/k4cu3bz7fvt1xy)
- [Homework submission template](https://www.overleaf.com/read/scbvjzqsxcpx)

**Final Project**

- [Final Project Requirements](project.md)
- [Final Project Signup Form](https://docs.google.com/spreadsheets/d/1N7ApHiRLkeWxplnTj2ODHgxCQxhrk0-VkjFKm_0lEKA/edit?usp=sharing)
- [Final Project Proposal Template](https://www.overleaf.com/latex/templates/neurips-2019/tprktwxmqmgk)

## 3. Course Description

- The goal of this course is to understand basic concepts and models in machine learning. Coding or implementing a machine learning model in detail will **not** be an emphasis of this course.
- Deep learning (or neural network modeling) will only be a small part of this course: two lectures in one week.

### 3.1 Topics 

Most of the course materials (and assignments) are adopted from [Shalev-Shwartz and Ben-David's textbook on machine learning](https://www.cse.huji.ac.il/~shais/UnderstandingMachineLearning/). Particularly, the topics overed in this course are:

- Introduction to learning theory
- Linear classification and regression
- Support vector machines and kernel methods
- Model selection and validation
- Regularization and stability
- Unsupervised learning: clustering and dimensionality reduction
- Introduction to neural networks

For more information about this course, please checkout the [schedule](schedule.md).

Some related graduate-level courses offered by the CS department in Spring 2020

- [Deep Learning for Visual Recognition](http://vicenteordonez.com/deeplearning/) by Vicente Ordonez-Roman, with more emphasis on deep learning
- [Statistical Learning and Graphical Models](http://ips.lab.virginia.edu/teaching/slgm/) by Farzad Hassanzadeh, with more emphasis on statistical aspects of machine learning


### 3.2 Prerequisites

- **Calculus and Linear Algebra**<br> Multivariable derivatives, matrix/vector notations and operations; singular value decomposition, etc.
- **Probability and Statistics**<br> Mean and variance, multinomial distribution, conditional dependence, maximum likelihood estimation, Bayes theorem, etc.
- **Proficiency in Python**<br> This course requires some programming in both homeworks and the final project. The preference of programming language for this course is Python (with some additional packages like Scipy, Sklearn, Tensorflow, and PyTorch), but it is also fine to use other programming languages (e.g., C/C++/Java), if you have lots of experience of it.


### 3.3 Textbook

- [UML] Shalev-Shwartz and Ben-David. [Understanding Machine Learning: From Theory to Algorithms](https://www.cse.huji.ac.il/~shais/UnderstandingMachineLearning/). 2014

**Additional**

- [PRML] Bishop. [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/). 2006
- [MRT] Mohri, Rostamizadeh, and Talwalkar. [Foundations of Machine Learning](). 2nd Edition. 2018

### 3.4 Reference Courses

If you would like to extend the scope of the materials covered by this course, I recommend to study the lecture notes from these following two courses:

- Shalev-Shwartz. [Understanding Machine Learning](https://www.cse.huji.ac.il/~shais/IML2014.html). 2014
- Mohri. [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/ml18/). Fall 2018

## 4. Assignments and Final Project

- **Homework (75%)**:
	- There will be **five** homeworks and each of them is worth 15%. 
	- Although collaboration on homework is *not* encouraged, students are allowed to discuss with their classmates. But, directly copying answers from others is definitely considered as plagiarism.
- **Project (22%)**:<br> There is only one course project and the credit breaks down to four parts
    - Project proposal: 5%
    - Midterm report: 5%
    - Final project presentation: 6%
    - Final project report: 6%
    - Other than using the machine learning libraries including Sklearn, PyTorch, Tensorflow, students need to implemented the rest of the proposed model by themselves. Copying code from any resources (e.g., Github, Bitbucket, and Gitlab) is prohibited and will be considered as plagiarism.
    - Students should team up for this project, each group can have up to four students.
- **Class participation (3%)**:<br> At *three* randomly-selected lectures in this semester, we will take attendance. Each is worth 1%.

### 4.1 Grading Policy

- [General information](grade.md)

## 5. Other Related Statements

### 5.1 Honor code

We are pround of our [honor system](https://en.wikipedia.org/wiki/Honor_system_at_the_University_of_Virginia) and I trust every student in this course to fully comply with all of the provisions of the University’s Honor Code. By enrolling in this course, you have agreed to abide by and uphold the Honor System of the University of Virginia, as well as the following policies specific to this course.

- All graded assignments must be pledged.
- All suspected violations will be forwarded to the Honor Committee, and you may, at my discretion, receive an immediate zero on that assignment regardless of any action taken by the Honor Committee.

Please let me know if you have any questions regarding the course Honor policy. If you believe you may have committed an Honor Offense, you may wish to file a Conscientious Retraction by calling the Honor Offices at (434) 924-7602. For your retraction to be considered valid, it must, among other things, be filed with the Honor Committee before you are aware that the act in question has come under suspicion by anyone. More information can be found at [http://honor.virginia.edu](http://honor.virginia.edu). Your Honor representatives can be found at: [http://honor.virginia.edu/representatives](http://honor.virginia.edu/representatives). 

*Adapted from [Honor Syllabus Example Statement](https://honor.virginia.edu/statement) on the UVa Honor Committee website*

### 5.2 Students with disabilities or learning needs

It is my goal to create a learning experience that is as accessible as possible. If you anticipate any issues related to the format, materials, or requirements of this course, please meet with me outside of class so we can explore potential options. Students with disabilities may also wish to work with the Student Disability Access Center to discuss a range of options to removing barriers in this course, including official accommodations. Please visit their website for information on this process and to apply for services online: [sdac.studenthealth.virginia.edu](sdac.studenthealth.virginia.edu). If you have already been approved for accommodations through SDAC, please send me your accommodation letter and meet with me so we can develop an implementation plan together.

### 5.3 Discrimination and power-based violence

The University of Virginia is dedicated to providing a safe and equitable learning environment for all students. To that end, it is vital that you know two values that I and the University hold as critically important

1.	Power-based personal violence will not be tolerated.
2.	Everyone has a responsibility to do their part to maintain a safe community on Grounds.

If you or someone you know has been affected by power-based personal violence, more information can be found on the UVA Sexual Violence website that describes reporting options and resources available - [www.virginia.edu/sexualviolence](www.virginia.edu/sexualviolence).

As your professor and as a person, know that I care about you and your well-being and stand ready to provide support and resources as I can. As a faculty member, I am a responsible employee, which means that I am required by University policy and federal law to report what you tell me to the University's Title IX Coordinator. The Title IX Coordinator's job is to ensure that the reporting student receives the resources and support that they need, while also reviewing the information presented to determine whether further action is necessary to ensure survivor safety and the safety of the University community. If you wish to report something that you have seen, you can do so at the [Just Report It portal](http://justreportit.virginia.edu). **The worst possible situation would be for you or your friend to remain silent when there are so many here willing and able to help**.

### 5.4 Religious accommodations

It is the University's long-standing policy and practice to reasonably accommodate students so that they do not experience an adverse academic consequence when sincerely held religious beliefs or observances conflict with academic requirements.

Students who wish to request academic accommodation for a religious observance should submit their request in writing directly to me via Email (*yangfeng@virginia.edu*) or post it on [Piazza](https://piazza.com/virginia/fall2019/cs6501005/home) as far in advance as possible. Students who have questions or concerns about academic accommodations for religious observance or religious beliefs may contact the University’s Office for Equal Opportunity and Civil Rights (EOCR) at *UVAEOCR@virginia.edu* or 434-924-3200.

*Section 5.1 - 5.4 are adapted from a SEAS-wide example*

**Last updated on 01/13/2019**
