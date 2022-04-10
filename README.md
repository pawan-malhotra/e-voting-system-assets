> # **E-Voting System**
> ## **Vote4Change**

India is regionally divided into States (and Union Territories) and each State has a Chief Minister who is the leader of the party or political alliance that has won a majority in the regional elections otherwise known as State Assembly Elections that exercises executive powers in that State. The respective State's Chief Minister has executive powers within the State and works jointly with the Prime Minister of India or their ministers on matters that require both State and Central attention. Some Union Territories also elect an Assembly and have a territorial government and other (mainly smaller) Union Territories are governed by a person appointed by the President of India.

The President of India monitors the rule of law through their appointed governors in each State and on their recommendation can take over the executive powers from the Chief Minister of the State, temporarily when the elected representatives of the State government has failed to create a peaceful environment and has deteriorated into chaos. The President of India dissolves the existing State government if necessary, and a new election is conducted.

**Our Task**

Our task is to automate the offline election process to online and bring the election process on the cloud. we have given a challenge to bring the offline mode election to online mode by making a web-application. further we can also move to different systems like andriod apps, mac os apps. 

> ## **Team Members**

- **Back-end**
    - Pawan Kumar [Know More](https://pawanmalhotra.netlify.app)
    - Pavithra
    - Pawan Kumar Baldewa

- **Front-end** 
    - Poorvi
    - Ponshankar
    - Partha
    - Pooja

- **Database**
    - Dheeraj
    - Parthib
    - Pinki

> ## **Requirements**

<br>

> **Software Requirement**

- JDK-11
- Eclipse-IDE
- Oracle 11g database
- Adobe XD or Gravit Designer (UI/UX Designer Tool)

>  **Technologies & Skills Requirements**

- **Back-end**
    - Java EE
    - Spring Framework
        - Spring Security
        - Lombok
        - Spring Validation
    - Hibernate
        - JPA
        - HQL
    - Thymeleaf

- **Front-end**
    - HTML
    - CSS
    - JS

- **Database**
    - Oracle 11g

> ## **Modules**

The project is divided into 4 modules

- Login/Register Modules
- Admin Module
- Electoral Officer Module
- Voter Module

<br>

> **Login/Register Module**

- **Database**
    - Table [`user_details`]
        - user_id (`varchar(10)`)
        - voter_id (`Number(5)`)
        - password (`varchar(200)`)
        - first_name (`varchar(45)`)
        - last_name (`varchar(45)`)
        - dob (`Date`)
        - age (`Number(3)`)
        - gender (`varchar(7)`)
        - religion (`varchar(25)`)
        - address (`varchar(100)`)
        - phone_no (`varchar(10)`)
        - constituency (`varchar(15)`)
        - district (`varchar(15)`)
    - Table [`role`]
        - role_id (`Number(3)`)
        - role_name (`varchar(15)`)
    - Table [`login_credential`]
        - user_id (`varchar(10)`)
        - password  (`varchar(200)`)
        - user_type (`varchar(15)`)

<br>

- **Front-end**
    - Page [`login.html`]
        - contains a form with 2 fields [`userid` & `password`]
        - show your creativity, how will you show the login form to users. make a page which motivates the user to vote for nations.
    - Page [`register.html`]
        - make a form as per the columns in `user_details` table in database except `voter_id` column.
        - gender should have the following options [`Male`, `Female`, `Others`]
        - religion should have the following options [`Muslims`, `Christians`, `Sikhs`, `Buddhists`, `Jains`, `Others`]
        - constituency should have proper options according to states. [reference](https://en.wikipedia.org/wiki/List_of_constituencies_of_the_Lok_Sabha)
        - state should have proper option [reference](https://en.wikipedia.org/wiki/List_of_constituencies_of_the_Lok_Sabha)
        - district must be listed according to state choosen. [reference](https://en.wikipedia.org/wiki/List_of_districts_in_India)
