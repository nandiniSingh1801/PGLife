PG Life Web Application:-	 
--------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------

PG Life is a Full-Stack Web Application. This is a project that I was assigned to make during my
Internshala Full Stack Web Development Internship Training. I got the guidance, and following that
I made this web application with my own undertsnading and knowledge. It is customized according to
what I thought would be better functionalities in this app, from the user perspective.





Tech Stack:- HTML, CSS, Bootstrap 5, Javascript, PHP, MySQL.

This web app has the following functionalities:-

1. The home page:-
--------------------
	a. Search bar, where user can enter city name(in any case), and PGs listed in that city(if exists in database), will be shown as list.
	
<img width="1366" height="768" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/1bd2bf6b-fccc-4331-8db6-8d328e95ff33" />
b. Contains main cities in the form of circular sections, clicking upon which user can get the list of pgs existing in that city.

c. Shows the list(containg hyperlinks) to show the list of PGs in the most popular cities.
      Displays copywright information.
<img width="1366" height="768" alt="Screenshot (191)" src="https://github.com/user-attachments/assets/64b82943-dea5-4a73-9099-fa0cb7f069f7" />



2. The PG list page:-
----------------------
	a. Shows the list of all the PGs and their main features in the selected city, in the form of beautiful cards.
	b. Filter bar, using which the PGs can be sorted according to rent and rating, in ascending or descending order.
	c. User can see here which PG is being marked interested by how many users, to know popularity.
	d. After logging in, user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
	e. The heart icon toggles style in terms of fill color, when alternatively clicked to like or dislike the pg. Based upon click,           interested user's number remains updated dynamically.
	
3. The PG details page:-
-------------------------
	a. In the property list page, if any user clicks on "View" button, that pg's entire details is being displayed in the PG details page.
	b. Images of the selected PG is being viewed at top front as a beautiful carousel.
	c. The page shows all the details such as amenities, testimonials, address of the PG neatly.
	d. User can see the selected PG is being marked interested by how many users, to know popularity.
	e. After logging in, user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
	f. The heart icon toggles style in terms of fill color, when alternatively clicked to like or dislike the pg. Based upon click, interested user's number remains updated dynamically.

<img width="1366" height="768" alt="Screenshot (194)" src="https://github.com/user-attachments/assets/72b7e9f9-c5b2-44fa-8763-1b0a3c61f300" />
<img width="1366" height="768" alt="Screenshot (195)" src="https://github.com/user-attachments/assets/42c5b4c0-fb4b-44ac-a2f4-53a1bc2c56de" />
<img width="1366" height="768" alt="Screenshot (196)" src="https://github.com/user-attachments/assets/3376d434-74da-42e5-abc2-d858cc7dbe0a" />
<img width="1366" height="768" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/a9acd23c-f76e-49ae-8555-0b01823adacb" />



4. The dashboard:-
--------------------
	a. Appears only for the logged in users.
	b. Shows the account details of the logged in users.
	c. Below profile details, there is a section for Interested properties, which shows the cards of those PGs which the logged in user marked interested, accross any city.
	d. From this list, user can click the heart icon on any PG card, to remove that PG from interested list, and that specific page section gets dynamically changed according to user's action.
<img width="1366" height="768" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/c34201df-2f75-45d9-a369-786ddc27d30d" />

5.The Signup Modal

<img width="1366" height="768" alt="Screenshot (207)" src="https://github.com/user-attachments/assets/dcef5f72-b78a-4262-9245-1a93869938dc" />

6. The Login Modal

   <img width="1366" height="768" alt="Screenshot (208)" src="https://github.com/user-attachments/assets/6430efd1-3ba8-4bf2-a993-a2d5db4de02b" />

7. The Navbar:-
----------------
	a. Contains brand name.
	b. If NOT logged in, it shows option to Signup and Login.
	c. If logged in, it shows option to got to Dashboard and Logout. Also, it displays the user's first name who is being logged in currently, by using SESSION.	
	d. Totally responsive toggler navbar.
      
8. The Breadcrumb:-
--------------------
	a. Beautify shows the relative location of the user in the web app.
	b. Contains hyperlinks to easily navigate back and forth an endpoint.





8. Entire web app can be surfed without logging in for user's ease and attraction for new users. Only 	certain features such as dashboard, and marking interested are available upon log in.

9. Through the entire web app, each and every excetion is handled well using custom codes and UI,	such that they are easily managed, and user can get to know the fault.
