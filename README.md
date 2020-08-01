# Budget-Tracker

## Description

This application will allow the user to maintain and update a budget while both online and offline.

___

## How it Works

This application begins with the user using the npm command to kickoff the application. From here the user will need to open localhost:3000 in the browser.

When the application opens the user will see the budget tracker application.

<br><br>

![BUGET TRACKER APP](public/images/budgetHomepage.png)

<br><br>

The application gives the user the opportunity to enter a new transaction name, a transation amount, and also decide whether to add or subtract funds from the overall total. Once these values are entered into the tracker, the graph will display the trend of the data. The y-axis indicates the total and the x-axis displays the date in which the transaction was added.

The next feature of this application is its ability to be used while offline.  In order to go into an offline status, the user will need to open up the inspector tools, select "service worker", and check the "Offline" box on the screen. 

<br><br>

![SERVICE WORKER OFFLINE](public/images/offlineStatus.png)

<br><br>

When the tracker is used offline the indexedDB holds that information in a pending state in the cached area. Any transaction done during this time will appear as below:

<br><br>

![CREATE BURGER](public/assets/img/makeBurger.png)

<br><br>

Once clicked, the created burger will be appear on the left side of the page. Along with the newly created burger, there will be a button labeled "Eat Me!" that appears to the right of the burger name.
<br><br>

![SAVING NOTES](public/assets/img/addedBurger.png)

<br><br>

Once the burger is added, the user will click the "Eat Me!" button. Doing this will move the burger from the "Make the Burger" column on the left side of the page to the "DEVOUR THE BURGER!!" column on the right side of the page.
<br><br>

![PICTURE DEVOURED BURGERS](public/assets/img/devouredBurgers.png)

<br><br>

If the user wants to view the totality of the information within the application, he/she can got to localhost:8080/api/allburgers to view the details of each added burger by I.D.

<br><br>

![PICTURE OF BURGER ARRAY](public/assets/img/burgerArray.png)

<br><br>
___

### Links for Heroku Deployment and GitHubDeployment
<br>
Heroku: https://node-burgers.herokuapp.com/
<br><br>
GitHub:  https://ccraig7321.github.io/Node-Express-Handlebars/
<br><br>
Portfolio Link: https://ccraig7321.github.io/Responsive-Portfolio/


### License

Copyright 2020 CHELSEY CRAIG

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


___