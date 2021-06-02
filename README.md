# Banking Kata

Develop an application that can deposit funds, withdraw funds and print a statement of a customer’s
bank account activity.

Here's the specification for an acceptance test that expresses the desired behaviour for this:

***Given a client makes a deposit of 1000 on 10/01/2021***  
***And a deposit of 2000 on 13/01/2021***  
***And a withdrawal of 500 on 14/01/2021***  
***When they print their bank statement***  

Then they would see:
```
Date || Amount || Balance  
14/01/2021 || -500 || 2500  
13/01/2021 || 2000 || 3000  
10/01/2021 || 1000 || 1000
```

### **Further Guidance**  
- Writing your tests first may help steer you in your design, you can use a testing framework
such as Mocha.  
- Don't worry about spacing and indentation in the statement output. (You could instruct your
acceptance test to ignore whitespace if you wanted to.)  
- Use the acceptance test to guide your progress towards the solution.  
- When in doubt, go for the simplest solution!  
- You can Google syntax.  

You may want to start with a *deposit(amount)* function and go from there…



### **Download**  
If you have git installed then you can run the following commands in your terminal:

```sh
git init
git clone https://github.com/robinjmc/BankingKataTemplate.git
```

*Alternatively download and unzip the folder from github*  

### **Setup** 

```sh
npm init
npm install
```
Run `npm test` in the console to ensure that the jest framework is working correctly. Happy coding!"# banking-kata" 
