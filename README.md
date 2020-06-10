# Manager and Trainee

* **Objective** - To create an `Employee` abstraction of a `Manager` and `Trainee`
* **Purpose** - To gain familiarity with:
    * the keyword `super`
    * the notion of polymorphism
    * the notion of inheritance
    * the notion of implementing an interface
    * the notion of extending a class  
* **Description**
    * In a company there are employees with two designations `Manager` and `Trainee`.
    * Both employees share the same set of attributes and basic salary calculation logic is same but the basic salary of trainee and manager are different.
    * The `Manager` has a travel allowance equal to 15% of the basic salary, whereas all the other employees the travel allowance is 10% of the basic salary.
    * Write a program to enforce each of these relationships. 
    * Ensure that all test cases in `src.test.com.github.perscholas` pass with 100% success rate. 
    * The original document can be found [here](./original-readme.pdf)




## How to Download

#### Part 1 - Forking the Project
* To _fork_ the project, click the `Fork` button located at the top right of the project.


#### Part 2 - Navigating to _forked_ Repository
* Navigate to your github profile to find the _newly forked repository_.
* Copy the URL of the project to the clipboard.

#### Part 3 - Cloning _forked_ repository
* Clone the repository from **your account** into the `~/dev` directory.
  * if you do not have a `~/dev` directory, make one by executing the following command:
    * `mkdir ~/dev`
  * navigate to the `~/dev` directory by executing the following command:
    * `cd ~/dev`
  * clone the project by executing the following command:
    * `git clone https://github.com/${MYUSERNAME}/${NAMEOFPROJECT}`

#### Part 4 - Check Build
* Ensure that the tests run upon opening the project.
    * You should see `Tests Failed: ${no_tests} of ${no_tests} tests`







## How to Submit

#### Part 1 -  _Pushing_ local changes to remote repository
* from a _terminal_ navigate to the root directory of the _cloned_ project.
* from the root directory of the project, execute the following commands:
    * add all changes
      * `git add .`
    * commit changes to be pushed
      * `git commit -m 'I have added changes'`
    * push changes to your repository
      * `git push -u origin master`

#### Part 2 - Submitting assignment
* from the browser, navigate to the _forked_ project from **your** github account.
* click the `Pull Requests` tab.
* select `New Pull Request`
