# izwithci
A demo of iziToast running in Codeigniter.
ROAD MAP
1- We included the iztoast and bootstrap cdns in the view file (welcome_message.php)
2- We created the alert.php file and included it in the view file.
3- We added a table from bootstrap's website and 3 buttons below it to the view page.
4- We turned these buttons into a tag and added an href. We directed these hrefs to the relevant method in the Welcome controller using route.
5- We created 3 methods in the welcome controller. with the names success, error and warning.
6- In these controllers, we have created a flashdata named alert. Flash Data is actually a session.
7- We added an array to this session. We sent the data in the format that iziToast wanted inside the Array.
When you press any button, that button will take us to the route. route will send us to the method in the corresponding controller. Finally, a flashdata will be created in the controller and we will return to our homepage with redirect. alert.php that we include on the homepage will capture this flashdata. session that will read the array of which button is pressed.
