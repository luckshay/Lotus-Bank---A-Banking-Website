# Lotus-Bank---A-Banking-Website

This was a project I created in 2nd Semester of B.Tech. for Advanced Web Technology Subject.

------------------HIGHER LEVEL OF APPROACH--------------------

1)	The basic aim of this website is to make Net-Banking easy for customers all over the country.
2)	Different Modules are made for different purposes –
i.	First it shows top navigation bar which has many list-in-list navigations and buttons to shift to other modules.
•	When screen size is small, all the buttons and navigations are wrapped which will be shown when three-lines-button is clicked present on top-right corner.

ii.	Personal Module to attract Individual Customers.
•	There is a Carousal of 6 pictures which change automatically after certain time.
•	Then there is a section of flexes which informs customers about features & facilities of our Bank and also attracts the users.
•	The Rates and Charges flex informs rates of  interest when user clicks on the desired element of list.

iii.	Business Module to attract Entrepreneurs, Start-Ups, etc.
•	This Module is welcomed by a Motivational Quotation with a background picture of a team depicting team-work.
•	Then there is section of animated bubbles which on hover animates and tells the benefits and features of our bank and also attracts them.
•	Last on page is an advertisement which is a facility of the bank.

iv.	Contact Us Module is made to take queries from customers.
•	On the left section of this page is the section to inform customers about our Customer Care E-mail Id’s, Phone Numbers and also the Locations of branches of our Bank on a Map.
•	On the right side there is a form which can be filled by customers and can ask their Queries.
•	There are certain form-validations which ensures form isn’t blank and user-inputs are in correct format.

v.	Login and OTP Module connect to Dashboard Module further connected to Transfer of Funds Module i.e. to transfer funds to other user’s account.
•	By clicking on Login Button positioned on navigation bar, it will re-direct to the login page.
•	On submission, if the login credentials are correct it will re-direct to the OTP page after an alert.
•	If the OTP entered is correct, the user will be re-directed to Dashboard, else, return back to the login page. 
•	On Dashboard in navigation Bar there are list-in-list navigations and the photo of user with user’s name is displayed which on hover will give Log-Out option.
•	On clicking Log-Out button, user will be re-directed to Personal Module.
•	The Transfer Funds button, in Make Payments on the navigation bar will redirect to the Transfer of Funds Module which has a form.
•	If all the account details given by user are valid to the dummy database created for the operation, on submit, the funds will be transferred and there will be appropriate alerts displayed in process.
•	 To go back to dashboard an appropriate button is given beside submit button.

3)	The website has Two-Factor-Authentication to login and transfer funds which make it safe and secure for customers.


-----------------LOWER LEVEL OF APPROACH---------------------------

1)	HTML attributes are used to link Personal, Business, Contact-Us, Login Modules to each other and Dashboard to Personal Module while logging out.
2)	JS attributes and coding is used to link Dashboard page with OTP page with Login Page.
3)	CSS Properties and Media Queries are used to make all Modules Responsive to almost all screen sizes possible.
4)	The buttons and lists-in-list on navigation bar have unique hover effects.
5)	Proper sections have been made for content in every module.
6)	JQuery is used for active user response in Rates-and-charges flex in Personal Module.
7)	All the input fields of forms are required to be filled in Contact-Us Module (to send queries) as well as in Transfer Of Funds Module (to transfer funds).
8)	JS coding is widely used to perform the dummy operation of funds transfer.



---------------- CREDENTIALS THAT WERE USED ---------------------

--Log In --

-username - luckshay
-password - 2010991610

-OTP - 24052

-Account Details for which it will work

-Account Number - 20109915911
-Beneficiary Name - KASHISH VATSH

-for account 20109916101 balance is 100000
-for account 20109916102 balance is 1000
