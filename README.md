# **Comcom**: Online Program Synthesis Tool for Everyone
**Designer: Hanxin Chen, Yan-Cheng Hsu**
## 1. Overview and Motivation
&emsp;&emsp;Currently, our team already had a website  ([Comcom: command line tool on the web](http://comcom.csail.mit.edu/comcom/#welcome)) that can provide the online program synthesis service to users. However, the website was built on ancient JAVA frameworks 10 years ago and we've already lost the acess to code base. Hence, in this project, we aim to create an website with same functionalities on the most up-to-date frameworks, like <i>React.js and Flask</i> in the hope that the newer version of the codes would be more **flexible, readable, testable and maintainable**. 
## 2. Problem Statement 
&emsp;&emsp; As we mentioned in the previous section, our goal is to re-create the website [Comcom](http://comcom.csail.mit.edu/comcom/#welcome) and build it upon latest frameworks.  
### 2.1 User Stories
<ul>
    <li>
        Users should be able to access website through URL mapped with DNS and use our online program systhesizers smoothly. 
    </li>
</ul>

### 2.2 Project Requirements 
**In Scope**
<ul>
    <li><i>Frontend</i></li> 
    <li><i>Backend</i></li>
</ul>

**Out of Scope**
<ul>
    <li><i>Frontend</i></li>
    <li><i>Backend</i></li>
</ul>

## 3. Methods and System Design
&emsp;&emsp; The high-level component diagram is shown in Figure 1 and the main flow of the proposed system and how components communicate with each other are illustrated in Figure 2, which is composed of Comcom Backend, Comcom Frontend and communication encryption services provided by AWS. In this section, a detailed explanation about each part is presented, with a summary introduced as follows:


![Figure 1 v1](https://github.com/Yan-Cheng-Hsu/ComCom-SystemDesignDocuments/blob/master/docs/Figure1_v1.png)
![Figure 1 v2](https://github.com/Yan-Cheng-Hsu/ComCom-SystemDesignDocuments/blob/master/docs/Figure2_v2.png)

<p align="center">Figure 1 Component diagram of Comcom project</p>