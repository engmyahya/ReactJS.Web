**Description**

Sample project to demonistrate the usage of compoents in React. <br>
I used to manage childs components' status, actions, rendering and fecthing info.<br>
<br>
News retrived from NY times web site using an authenticated API.<br>
The retrived news is the most populare news (master). When any of them has been clicked by the end user it will show the <br>
news' details (like master details).<br>
The ability to search on this list is also availble there.<br>
<br>
<br>
**Structure** <br>
M => (API) I get the data from the web api.<br>
V => (components) folder<br>
C => (code) folder will handle all the required code.<br>
<br>
<br>
**Running steps** <br>
You need to install those packages to be able to run the project :<br>
1-I used axios library as a promise based library to Ajax a request :<br>
```>npm install axios --save-dev```<br><br>
2-I used bootstap to stylize my components:<br>
```>npm install --save-dev bootstrap jquery popper.js ```<br><br>
3-I used enzyme,chai and Mocha to author test cases, execute them and get a results:<br>
```>npm install --save-dev enzyme react-test-renderer chai hai-enzyme enzyme-adapter-react-16 ```<br><br>
4-We can run the project using the following cli :<br>
```>npm start```<br><br>


Open (http://localhost:3000) to view it in the browser.<br>
<br>
**Running the Test cases' steps** <br>
You created multiple test cases with assertion scenarioes which we may try to check by running the following program : <br>
```>npm test```
