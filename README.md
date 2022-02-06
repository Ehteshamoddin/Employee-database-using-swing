# Employee-database-using-swing
## About this project:
This is java swing application for creating database of employees. The database used in it is MySql

## Built With:

- Java
- swing GUI widget toolkit
- MySql database
- JDBC driver
## Usage
### Clone or Download this repository
``` https://github.com/Ehteshamoddin/Employee-database-using-swing.git ```
### Prerequisites
- Install JDK and Intellij Idea
- MySql Database

### Usage Guide
``` 
public void connect() {
        try {
            Class.forName("com.mysql.cj.jdbc.Driver");
            con = DriverManager.getConnection("jdbc:mysql://localhost:3306/Name of database/Table created", "Database username", "Write here password for your database");
            System.out.println("Successs");
        } catch (ClassNotFoundException ex) {
            ex.printStackTrace();

        }
        catch (SQLException ex) {
            ex.printStackTrace();
        }
    }
 ```
### Changes to be applied in the above code section
- In place of ``` Name of database ``` write name of ``` <Your own MySql Database> ```
- In place of ``` Database username ``` write username ``` <MySql Database Username> ```
- In place of ``` Write here password for your database ``` write password ``` <Password of MySql Database> ```


## Contribution guide
- Fork the repository.
- Clone ``` git clone https://github.com/Ehteshamoddin/learn_Java ``` or Download the Zip.
- Make Code changes or Documentation (README.md) changes.
- Add new branch if neccessary ``` git branch <branch-name> ``` and Push the Code changes.
- Generate new 'Pull request'.
- Briefly specify the changes you have made and submit the request.

## Author & Creator of Repository [Ehteshamoddin Shafioddin Siddiqui](https://github.com/Ehteshamoddin)
### Love or Appreciate My Efforts ?
##### Please make sure to star the repo and share to as many people as you can.
#### Having Problem? 
Always Feel free to raise and issue or directly contact me on social media handles as well as in git chat.
#### Follow the profile to get to know more about me
## Connect with me:
<p align="left">
<a href = "https://www.linkedin.com/in/ehteshamoddin-siddiqui-b719b9206/"><img src="https://img.icons8.com/fluent/48/000000/linkedin.png"/></a>
<a href = "https://twitter.com/ehteshamoddinss"><img src="https://img.icons8.com/fluent/48/000000/twitter.png"/></a>
<a href = "https://www.instagram.com/ehteshamoddin/"><img src="https://img.icons8.com/fluent/48/000000/instagram-new.png"/></a>
</p>
<a href="https://github.com/Meghna-DAS/github-profile-views-counter">
    <img src="https://komarev.com/ghpvc/?username=Ehteshamoddin">
</a>
<a href="https://github.com/Ehteshamoddin?tab=followers"><img src="https://img.shields.io/github/followers/Ehteshamoddin?label=Followers&style=social" alt="GitHub Badge"></a>
