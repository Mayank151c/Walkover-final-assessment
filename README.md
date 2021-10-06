
<hr> 
<p align="center">
<img  src="https://github.com/Mayank151c/walkover-final-assessment/blob/master/public/img/heading.gif?raw=true"  alt="MCQs Test Platform"> 

## <p align=center>Walkover-final-assignment</p>
</p>

#### <u>Intruduction</u>
This is a web application for hosting MCQs(Multiple choice question) based test online, which is made on top of Node.js and Express.js.<br><br>
 Application provides you to login as `Student` or as a `Admin`
> ##### Student-Login : `used by the candidate who will be giving the online test.` <br> Admin-Login &nbsp;&nbsp;: `used by host/examiner i.e who wants to conduct the MCQs test.` <br>

Admin has following rights :
- Can login after email OTP verification
- Create Unique test link
- Decide number of question to be present in test
- Create Questions pool (pool maybe greater than number of question in test.)
- Can see the ranks of candidates who has already completed their test
- Direct access link for test creation : [Link](https://mcqs1.herokuapp.com/create_test.html)
- Sample test ID - `id1633455558600&u4&q5&t60`
- Sample test [Link](https://mcqs1.herokuapp.com/teststart.html?testid=id1633455558600&u4&q5&t60)
<hr>

#### <u>Features Specification</u>
##### Assigned in Project
- [x] Assessment shall be MCQ pattern 
- [x] There must be a question pool for the assessment
- [x] The questions displayed in the assessment shall be only from that pool
- [x] Number of questions in the pool shall be more than questions displayed
- [x] Set a time limit for the assessment (individual timer for a question/optional)
- [x] Question order shall be shuffled for each candidate appearing
- [x] Assessment score shall be generated at the time of submission
##### Additional
- Easly understandable/accessable UI.
- Result are sorted by marks in Scoreboard.
<hr>

#### <u>Tech Stack</u>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)&emsp;![CSS](https://img.shields.io/badge/CSS3-1572D6?style=for-the-badge&logo=css3&logoColor=white)&emsp;![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)&emsp;![NodeJS](https://img.shields.io/badge/Node.js-4853D?style=for-the-badge&logo=node.js&logoColor=white)&emsp;![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

<hr>

#### <u>Contributors</u>
>[Mayank Choudhary](https://github.com/Mayank151c) <br>
>[Mohammad Tabish]()    <br>
<hr>

#### <u>Deployment</u>
Application is deployed on top of CI/CD pipeline of Heroku platform.

<img src="https://github.com/Mayank151c/walkover-final-assessment/blob/master/public/img/deploy.jpg?raw=true" width="100%">

| Web-page | Link | 
|   ----   | ---- |
| Live Project|[`Click here`](https://mcqs1.herokuapp.com/)| 
| Admin-Login |[`Click here`](https://mcqs1.herokuapp.com/adminLogin.html) |

<hr>

#### <u>Project Setup</u>
Steps to setup and run our project locally on your machine
>1. Install git on your machine if not installed already <br>
>To install [`click here`](https://git-scm.com/downloads) for Windows or <br>Run command `$ sudo apt-get install git` for Linux
>2. Clone the repository <br>
`git clone https://github.com/Mayank151c/MCQs_App.git`
>
>3. Go inside the cloned directory on the terminal.
>4. Install the required packages by command <br>
`npm install`
>
> &ensp;&ensp;**Note** : `comment line:57 & uncomment line:54 to run in local`

>5. Start local-server by command <br>
`npm start`
>
>6. Open any browser and access the web application by following link <br>    `http://localhost:3000/`
><br>


 
