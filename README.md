# Milestone Project 4: Pound Dog

![site screenshot](documentation/)
 

# Click link to visit ["Pound Dog"]()

# Aim of the project

- The aim of this project is to provide access to a website informing the public of a fictional,  independant company whose sole purpose is to rescue, look after, and potentially re-house dogs.

- The second aim of the project is to encourage the user to register so as to contribute either through monetry donations or to offer their services on a voluntary level.


# This site should appeal to and be suited for : 

- Those who have a genuine interest in the welfare of dogs.
- Those who have the inclination to spare a limited sum of money in supporting charities such as these. 
- Those who feel that they have something to offer in relation to the everyday running of such a facility and have the ability to volunteer on a regular basis.
- Someone who knows of a circumstance relating to the welfare of an animal and is looking for advice on how to deal with the matter.
 

# User Story

- As a first time visitor to the site, I would want a clean, clear user interface, instantly outlining the purpose of the site. 
- As a first time visitor I would want to be able to navigate easily to the relevant areas of the site that are of interest to me.
- As a first time visitor I would want to know the benefits of creating an account and why it is being suggested to log in.
- As a visitor to the site I would expect responsiveness across all devices so the content would look and feel the same regardless of the device used.


- As a returning visitor to the site I would want to log in to my account to access my personal details and any interactivity I have taken part in.
- As a returning visitor I would want to access my profile to access, edit and delete any information previously submitted.

- User Conclusion
    - After visiting the site I would like to feel that I have benefited from a good user experience interacting with the site.
    - I have learnt something regarding the aims of the charity.
    - I have contributed to the whole experience by either donating, offering my time and/or services.
    - I would have gained enthusiasm and motivation to encourage others to visit the site, and become instrumental in the upkeep of the charity.



# The 5 planes of UX

- When planning out this site I thought it important to implement the same 5 planes of UX that I had used when designing my Milestone Project 1 and 2. Doing this makes the process an easier task.

## The Strategy

- In planning out this website I specifically wanted to target users who fell into these brackets:
    - Those who are familiar with charities such as Pound Dog and other animal welfare practices.
    - Those who are familiar with charities such as Pound Dog and wish to become active in their upkeep.
    - Those working within the same industry/environment and is wanting to reach out for support or to offer support.
    - Those who would use the site as a means to accessing information regarding caring for dogs.
    - Those who are looking to adopt a dog and are looking for an avenue to explore.

- As a developer I would want a site that was easily maintainable and easy to update with new content as the site progressed.

    
## The Scope

- Based on the strategy above I began to work on the scope of the site taking into consideration the following factors:
    - The user should be able to:
        - Navigate easily around the entire site in a clear and effective manner.
        - Have the navigation areas clearly marked with full text on larger screens and the standard familiar collapsible navigational button on smaller screens.
        - Find the site attractive with text elements easy to read and images to be clear, and interesting in appearance.
        - Feel interested enough to want to register with the site to participate in aspects of the upkeep of the charity.
        - Register with minimal fuss and only have to supply the absolute necessary information to create an account. 
        - Once registered, be content that the process was worthwhile.
        - Find aspects of the site appealing enough that they would want to return.
        - Become interested enough that they themselves would want to return to the site to view and review information relevant to themselves.

## The Structure

- I planned on using set elements throughout the project so as to keep the sense of familiarity running regardless of the content on the page. Therefore I incorporated:
    - A fixed Navbar, present on all screens, displaying the relevant options to the user at their point of the journey,

    ![openingnavbar](documentation/)
    ![loggedinnavbar](documentation/)
---

- A floating footer bar featuring.....

    ![pagefooter](documentation/)
---

- The opening page will welcome the user to the site, explain the sites purpose and encourage the user to login to access more content. The user should notice the option to log in has been highlighted in the body of welcoming text but failing that the option to log in is also displayed within the Nav bar.

    ![markedtext](documentation/)
    ![markedlogin](documentation/)

- If the user chooses not to log in then the options are limited to the basic ideals of the site. 
- If the user chooses to log in to the site they will be redirected to a log in page. If the user has never visited the site before then they will be required to register with the site. This is suggested at the bottom of the log in page.

    ![markedregistration](documentation/)

- For the registration aspect I will have created a collection in a database within Django where the information regarding the users name, email, and password will be safely stored. The password will be encrypted using the Werkzeug security password hash method.
- After registering, the user will be directed to a new screen with the new content made available to them.
    ![markeduserscreen](documentation/)

---

- In the event that the user should encounter an error whilst navigating the site, I have created a simple 404 error page that features all the correct navigational elements of the main page along with an additional 'Home' button to ensure that the user is returned back to a functioning section of the site.

    ![404errorscreen](documentation/)


---

## From the Skeleton to the Surface

The idea of the bare bones of the project were sketched out in wireframes using Balsamiq. Laid out below is the realization of each main structure into its actual state.

- Page 1  
*# Actual screen grab does not indicate full content of screen*  


![homepagedesktopview](documentation/)
![actualhomepage](documentation/)


- Page 2 
*# Actual screen grab does not indicate full content of screen*  


![historypagedesktopview](documentation/wireframes/historypagedesktop.png)
![actualhistorypage](documentation/readmeimages/historygrab.png)


- The Log In Page is where the visitor has the option to log in or register to access more content within the site. There is a link at the bottom of the page alerting the visitor that if not currently registered then the link will take them to the necessary registration page.  


![loginpagedesktopview](documentation/)
![actualloginpage](documentation/)


- The Registration Page is where the visitor to the site can give minimal details to become a user of the site and have access to extra content within the site. 


![registrationpagedesktopview](documentation/)
![actualregistrationpage](documentation/)


- Once registered / logged in the user will be greeted by a revision of the home page but this time there will be more information regarding the new content available to them. 


![loggedinpagedesktopview](documentation/)
![actualregisteredpage](documentation/)


- The User Profile page is where users can go back to access their personal information. If they so wish, the option to edit or delete information is also presented to them as well.


![userprofilepagedesktopview](documentation/)
![actualprofilepage](documentation/)


- The final option available to the user is to log out of the site. Upon doing so the user will be returned back to the generic home page with a flash message that they have been logged out and to come back soon.  
*# Actual screen grab does not indicate full content of screen* 


![actualloggedoutpage](documentation/)

---

## Django

---

# Early Stages

## Wireframes

- A wireframe summary of the home page on desktop, tablet, and mobile view.

![homepagedesktopview](documentation/)
![homepagetabletview](documentation/)
![homepagemobileview](documentation/)
![homepagesidenavmobileview](documentation/)

- A wireframe summary of the .... on desktop, tablet, and mobile view.

![historypagedesktopview](documentation/wireframes/)
![historypagetabletview](documentation/wireframes/)
![historypagemobileview](documentation/wireframes/)
![historypagesidenavmobileview](documentation/wireframes/)

- A wireframe summary of the .... page on desktop, tablet, and mobile view.

![loginpagedesktopview](documentation/wireframes/)
![loginpagetabletview](documentation/wireframes/)
![loginpagemobileview](documentation/wireframes/)
![loginpagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the Registration page on desktop, tablet, and mobile view.

![registrationpagedesktopview](documentation/wireframes/)
![registrationpagetabletview](documentation/wireframes/)
![registrationpagemobileview](documentation/wireframes/)
![registrationpagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the Logged In / Registered page on desktop, tablet, and mobile view.

![loggedinpagedesktopview](documentation/wireframes/loggedinpagedesktop.png)
![loggedinpagetabletview](documentation/wireframes/loggedinpagetablet.png)
![loggedinpagemobileview](documentation/wireframes/loggedinpagemobile.png)
![loggedinpagemobilesidenavview](documentation/wireframes/loggedinpagemobilesidenav.png)

- A wireframe summary of the User Profile page on desktop, tablet, and mobile view.

![userprofilepagedesktopview](documentation/wireframes/)
![userprofilepagetabletview](documentation/wireframes/)
![userprofilepagemobileview](documentation/wireframes/)
![userprofilepagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the .... page on desktop, tablet, and mobile view.

![fablespagedesktopview](documentation/wireframes/)
![fablespagetabletview](documentation/wireframes/)
![fablespagemobileview](documentation/wireframes/)
![fablespagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the ..... page on desktop, tablet, and mobile view.

![quiztimepagedesktopview](documentation/wireframes/)
![quiztimepagetabletview](documentation/wireframes/)
![quiztimepagemobileview](documentation/wireframes/)
![quiztimepagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the ..... page on desktop, tablet, and mobile view.

![competitionpagedesktopview](documentation/wireframes/)
![competitionpagetabletview](documentation/wireframes/)
![competitionpagemobileview](documentation/wireframes/)
![competitionpagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the ..... page on desktop, tablet, and mobile view.

![usereditpagedesktopview](documentation/wireframes/)
![usereditpagetabletview](documentation/wireframes/)
![usereditpagemobileview](documentation/wireframes/)
![usereditpagemobilesidenavview](documentation/wireframes/)

- A wireframe summary of the ..... page on desktop, tablet, and mobile view.

![storydeletepagedesktopview](documentation/wireframes/)
![storydeletepagetabletview](documentation/wireframes/)
![storydeletepagemobileview](documentation/wireframes/)
![storydeletepagemobilesidenavview](documentation/wireframes/)

- Various Flash Messages Featured Throughout Site

![flashmessages](documentation/wireframes/)

---

# Colour Schemes

For the colour scheme I decided to keep things as simple as possible so as not to distract from the content.  
MAIN COLORS
![colorscheme](documentation/readmeimages/)  

## Breakdown Of Use Of Colours

![colorscheme](documentation/readmeimages/)  
TEXT

![colorscheme](documentation/readmeimages/)  
BACKGROUND COLOR

![colorscheme](documentation/readmeimages/)  
TEXT

![colorscheme](documentation/readmeimages/)  
TEXT


![colorscheme](documentation/readmeimages/)  
TEXT

![colorscheme](documentation/readmeimages/)  
ICONS
  
To ensure good, consistant readability throughout the site I ran a contrast check on my text to background color ratio and was pleased with the results.

![contrastcheck1](documentation/readmeimages/)
![contrastcheck2](documentation/readmeimages/) 
  
---

## Fonts

For the textual elements I imported in two font family variants from Google Fonts.

![Main Font](documentation/readmeimages/) ![Secondary font](documentation/readmeimages/)

---

# The Website Features

- ## As Submitted

       
- ## Features I would include in the future
   
---

# User Interaction

- The following aspects can be interacted with:


# The Coding Languages and Techniques Used

- This site was constructed using:
    - HTML5
    - CSS3
    - Javascript
    - Jinja
    - jQuery
    - [Materialize](https://materializecss.com/)
    - [MongoDB](https://www.mongodb.com/)
    - [Heroku](https://www.heroku.com/)
    - [Fontawesome](https://fontawesome.com/)
    - [Balsamiq](https://balsamiq.com/) was used for creating the wireframes for this project.

## Using MongoDB in the site.

- Listed below is the method for initiating and using MongoDB to store site data in a collection within MongoDB.
    - Firstly, navigate to www.MongoDB.com.
    - Click on either 'Try Free' or 'Start Free'  

    ![mongopt1](documentation/readmeimages/mongodbpt1.png)

    - Once selected you will need to fill out your personal details.

    ![mongopt2](documentation/readmeimages/mongodbpt2.png)

    - Once filled out you will be prompted to verify your email address.

    - Then select 'Build a Database'

     ![mongopt3](documentation/readmeimages/mongodbpt3.png)

    - Next you need to choose which option is best suited for your purposes to deploy your cloud database. For the purposes of this site I chose the shared option which is free.

    ![mongopt4](documentation/readmeimages/mongodbpt4.png)

    - Next you want to select your cloud provider and the region applicable to you. In this case I selected AWS and because I live in Ireland, I'd select Ireland.

    ![mongopt5](documentation/readmeimages/mongodbpt5.png)

    - Next, select a cluster tier. This is similar to buying cloud storage. Price depends on the size of the storage needed. In this instance select M0 which is 'Free Forever'.

    ![mongopt6](documentation/readmeimages/mongodbpt6.png)

    - Lastly in this section, give the cluster a name, (this can only be done once), and select 'Create Cluster'. This may take 1-3 minutes to complete.

    ![mongopt7](documentation/readmeimages/mongodbpt7.png)

    - Inside of the main cluster workspace, under Security select 'Database Access'. This will bring you to the next step of adding a database user. Select 'Add New Database User'.

    ![mongopt8](documentation/readmeimages/mongodbpt8.png)

    - Within the new database user form make sure that the Authentication Method is set to Password, create a username and password. Under the 'Database User Privileges' make sure that 'Read and write to any database' is selected and finally select 'Add User'. Remember to never share or include your username and /or password in any capacity. Doing so will give someone full access and potentially jeopardize the database. 

    ![mongopt9](documentation/readmeimages/mongodbpt9.png)

    - With the new user added, select 'Network Access' from the menu on the left titled 'Security' and then select 'Add IP Address'.

    ![mongopt10](documentation/readmeimages/mongodbpt10.png)

    - It's here that we can 'whitelist' our IP address, basically letting MongoDB know that our IP address is safe to access the database. Ideally, for extra security the user should select 'Add Current IP Address' and specify certain IP addresses. For the purpose of this demonstration I have selected 'Allow Access From Anywhere'

    ![mongopt11](documentation/readmeimages/mongodbpt11.png)

    - With that done, head back to Databases under the 'Deployment' heading and select 'Browse Collections'. In the following screen, select 'Add My Own Data'.

    ![mongopt12](documentation/readmeimages/mongodbpt12.png)

    - Here now, you can name your own database using no spaces and incorporating camelcase for more than one word in the title, and within that, name your first collection.

    ![mongopt13](documentation/readmeimages/mongodbpt13.png)

    - As you can see here, once the database and collection has been named, you return back to the main screen and you can see the new database and collection ready to use.

    ![mongopt14](documentation/readmeimages/mongodbpt14.png)

    - From this point on you can insert documents into the collection via the 'Insert Document' within the cluster page or generate documents programmatically. You will notice also that each document comes with a unique ID code which contains a timestamp of when the document was created.

    ![mongopt15](documentation/readmeimages/mongodbpt15.png)

# Method of Deployment

- My two previous Milestone projects were deployed on GitHub pages due them being more frontend, static sites. This current project is a data-centric, back-end project and therefore I had to use a host that is suited to my needs, ie: Heroku, Elastic Beanstalk, Firebase.

- To fully test the site on multiple 'real-world' devices I wanted to create a live link to the site relatively early on that could be accessed universally. To do this, I opted to deploy the site using Heroku. To do similar the user should: 

- Firstly, make sure that a requirements.txt file has been created and that it contains the details of the necessary packages/modules used within the program code. If extra packages/modules are introduced throughout the development of the site then it is important to update their existence within the requirements.txt file so that they are utilised by Heroku.  

![requirementsgrab](documentation/readmeimages/requirementsgrab.png)  

- Secondly a Procfile must be created with the name of the application file (app.py) so Heroku knows which file to access first. This is only a short one line file but ultimately very important!!  

![procfilegrab](documentation/readmeimages/procfilegrab.png)  

- Lastly these files must be pushed to GitHub in preparation for deploying the site through Heroku.  


- Once the above steps have been followed the user should follow the next steps:

    - Step 1: Open Heroku.com and sign in.
    - Step 2: Once signed in the user should see a list of apps previously created (if any) in chronological order. In the top right corner click on new and select 'Create new app'.
    
    ![herokupt1](documentation/readmeimages/herokupt1.png)  

    - Here the user will now name the app you wish to create. This must be written in lowercase and replace any spaces with the minus/dash character. As the user writes the name of the app, a guidance note will appear displaying if the name is available or not. Following this the user must select a region between United States and Europe.  

    ![herokupt2](documentation/readmeimages/herokupt2.png)  

    - The next step brings the user the options for how to deploy their app, basically how to access the code written. For this example we will presume the user has the code in GitHub so select 'Connect to Github' and type the name of the repository you wish to have deployed.

    ![herokupt3](documentation/readmeimages/herokupt3.png)  

    - Once Heroku has found the repository it will be displayed below and the user simply has to click select.
    - If the user has stored the environment variables within a hidden env.py file (which is common,  safe practise), Heroku won't be able to read those variables. To make the variables accessible to Heroku, click on the 'Settings' tab for your app, and then click on 'Reveal Config Vars', where the user can securely tell Heroku which variables are required and their subsequent values.  

    ![herokupt4](documentation/readmeimages/herokupt4.png)  

    - Presuming that the user has the Procfile and all other relevant files added and pushed through to GitHub then the user should then select 'Enable Automatic Deployment'. If the user has the main branch for deploying then select 'Deploy Branch'.
    - Once these options have been selected, Heroku will have gained access to the site and start building the app based on the required files. Once completed, Heroku will display the message 'Your app was successfully deployed'. Click 'View' to launch the app.
    - In the settings page, the user can find the url for accessing the site on all devices and browsers.  

    ![herokupt5](documentation/readmeimages/herokupt5.png)

    - From this point on, all new code pushed to GitHub will be read and displayed through the app. It is important to deploy early in the apps development so as to making the testing stages a longer, more thorough investigation into the overall working of the code.  
    - From this point on you can type in and access your site on any device with an internet browser which is ideal for testing purposes.

## For those wishing to develop the site further using a repository clone:
- You must first ensure that you have a current Github account.
- Be running the most up to date version of Google Chrome with the Gitpod browser extension installed.
- Login to Github with your own github account.
- Navigate to the Project Github Repository page.
- Click the New button, this will trigger a new workspace.
- Under Create a new Repository select Import a Repository
- Now, in the Your Old Repository Clone URL field, type in "git clone https://github.com/JamieWilson2000/.git"
- Enter in a new relevant repository name and click Begin Import.
- After a short while you'll recieve a message saying that the new repository is ready with a link to take you to it.
- Open gitpod.
- To ensure that all packages/modules are in place type 'pip install -r requirements.txt' in the terminal. As long as the requirements file is up to date, this will install all elements for running the site.  

# Methods of Testing

- Throughout the development stage I used a handful of methods to ensure the site looked and acted appropriately.  

- These included:

    - Chrome Dev Tools - for testing stylings, sizing, and responsiveness

    - Mozilla Dev Tools - for testing stylings, sizing, and responsiveness

    - http://ami.responsivedesign.is/ - for general look and feel of the site.

    - https://coolors.co/ - for picking color schemes and testing contrast colors -- **[See Results](#colour-schemes)**

    - Heroku.com - to access the live site across different devices

    - Google Lighthouse - to test perfomance -- **[See Results](#lighthouse-testing)**

---  
# Summary of User Testing

# User Story Recap

- As a first time visitor to the site, I would want a clean, clear user interface, instantly outlining the purpose of the site. -- **[See Test 1](#test-1)**
- As a first time visitor I would want to be able to navigate easily to the relevant areas of the site that are of interest to me. -- **[See Test 2](#test-2)**
- As a first time visitor I would want to know the benefits of creating an account and why it is being suggested to log in. -- **[See Test 1](#test-1)**
- As a visitor to the site I would expect responsiveness across all devices so the content would look and feel the same regardless of the device used. -- **Checked across all tests**


- As a returning visitor to the site I would want to log in to my account to access my personal details and any interactivity I have taken part in. -- **[See Test 4](#test-4)**
- As a returning visitor I would want to access my profile to access, edit and delete any stories I have submitted. -- **[See Test 8](#test-8)**

## Test 1  
### Accessing the site.

As a first time visitor to the site, I would want a clean, clear user interface, instantly outlining the purpose of the site.  

Test Description: This is to test that the visitor will be greeted with the above.

Steps Taken 

- Navigate to http://aesops-fables-ms3.herokuapp.com/  

Image of Test Result  

![testgrab1](documentation/readmeimages/testgrab1.png)  ![testgrab1tab](documentation/readmeimages/testgrab1tab.png)

The text should reflect the purpose of the site and the benefit to the visitor of registering / logging in.  

![testgrab1text](documentation/readmeimages/testgrab1text.png)

Considered Pass/Fail: Pass  

## Test 2  
### Identifying the Navigational elements.

As a first time visitor to the site, I want a clean clear navigational system in place.

Test Description: This is to test that the visitor will know how to navigate around the site.

Steps Taken

- On desktop, the user should notice the options available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button, familiar in todays web applications and be able to access the options available.  

Image of Test Result  
![testgrab1](documentation/readmeimages/testgrab2.png)  ![testgrab1tab](documentation/readmeimages/testgrab2tab.png)
    
Considered Pass/Fail: Pass  

## Test 3
### Accessing the 'History' page.

As a first time visitor to the site, I want to access content available to me at this point.

Test Description: This is to test that the visitor can access the content available to them at this stage..

Steps Taken   
    
- On desktop, the user should select the history option available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button, familiar in todays web applications and be able to access the history option available.  

Image of Test Result  
![testgrab3](documentation/readmeimages/testgrab3.png)  ![testgrab3tab](documentation/readmeimages/testgrab3tab.png)

When reaching the bottom of the page there is a 'Back to top' link that should return the user to the top of the page.  

![testgrab3](documentation/readmeimages/testgrab4.png)  ![testgrab3tab](documentation/readmeimages/testgrab4tab.png)  

Considered Pass/Fail: Pass  

## Test 4
### Accessing the 'Log In' page.

Test Description: This is to test that after viewing the opening content, the visitor can access the extra content available via registering / logging in.

Steps Taken  
    
- On desktop, the user should select the 'Log In' option available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button, familiar in todays web applications and be able to access the 'Log In' option available.  

Images of Test Results   

![testgrab5](documentation/readmeimages/testgrab5.png)  ![testgrab5tab](documentation/readmeimages/testgrab5tab.png)

The user should be presented with the log in form.  

The user should note that if not previously registered on the site then a navigational link is available to them underneath the log in form.  

![testgrab6](documentation/readmeimages/testgrab6.png)  ![testgrab6tab](documentation/readmeimages/testgrab6tab.png) 

Upon clicking the 'Register Here' link, the user should be taken to the registration page.  

![testgrab7](documentation/readmeimages/testgrab7.png)  ![testgrab7tab](documentation/readmeimages/testgrab7tab.png)  

Upon filling out the requested form, the user should be presented with the extra content as promised in the opening page.  

![testgrab8](documentation/readmeimages/testgrab8.png)  ![testgrab8tab](documentation/readmeimages/testgrab8tab.png) 

Considered Pass/Fail: Pass  

## Test 5  
### Accessing the 'Most Loved Fables' page.

As a first time visitor to the site, I want to access the extra content available to me.

Test Description: This is to test that the visitor can access the content and that the videos all play.

Steps Taken  
    
- On desktop, the user could select the 'Most Loved Fables' option available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button, familiar in todays web applications and be able to access the 'Most Loved Fables' option available.  

Image of Test Result  
![testgrab9](documentation/readmeimages/testgrab9.png)  ![testgrab9tab](documentation/readmeimages/testgrab9tab.png)  

To watch each video, the user has to either click the main play button or choose to 'Watch on Youtube'

When reaching the bottom of the page there is a 'Back to top' link that should return the user to the top of the page.  

![testgrab10](documentation/readmeimages/testgrab10.png)  ![testgrab10tab](documentation/readmeimages/testgrab10tab.png)  

Considered Pass/Fail: Pass 

## Test 6
### Accessing the 'Quiz Time' page.

As a first time visitor to the site, I want to access the extra content available to me.

Test Description: This is to test that the visitor can access the 'Quiz Time' page and participate in the quiz understanding how the game works.

Steps Taken  
    
- On desktop, the user could select the 'Quiz Time' option available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button, familiar in todays web applications and be able to access the 'Quiz Time' option available.  

Images of Test Results  

![testgrab11](documentation/readmeimages/testgrab11.png)  ![testgrab11tab](documentation/readmeimages/testgrab11tab.png)

Questions are placed on cards with the user prompted to 'Click to reveal the answer' wherein once selected the answer will become visible. To close the card again, users will notice a close symbol on the right of the card.  

![testgrab12](documentation/readmeimages/testgrab12close.png)  ![testgrab12tab](documentation/readmeimages/testgrab12open.png)

When reaching the bottom of the page there is a 'Back to top' link that should return the user to the top of the page.  

![testgrab13](documentation/readmeimages/testgrab13.png)  ![testgrab13tab](documentation/readmeimages/testgrab13tab.png)  

Considered Pass/Fail: Pass 

## Test 7
### Accessing the 'Competition' page for submitting a story.

As a first time visitor to the site, I want to access the extra content available to me.

Test Description: This is to test that the visitor can access the 'Competiton' page

Steps Taken  
    
- On desktop, the user could select the 'Competition' option available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button, familiar in todays web applications and be able to access the 'Competition' option available.  

Images of Test Results  

![testgrab14](documentation/readmeimages/testgrab14.png)  ![testgrab14tab](documentation/readmeimages/testgrab14tab.png)

After completing the required fields, the user should be redirected to their 'Your Stories' page. Here they will be presented with a collapsible element displaying their submitted story.  

Considered Pass/Fail: Pass 

## Test 8
### Accessing the users 'Your Stories' page.

As a first time visitor to the site, I want to access the extra content available to me.

Test Description: This is to test that the visitor can access the exclusive content available to them at this stage..

Steps Taken  
    
- On desktop, the user could select the 'Your Stories' option available placed clearly in the top right hand corner.  
- On mobile devices, the user should notice a collapsible menu button familiar in todays web applications and be able to access the 'Your Stories' option available.  

Images of Test Results  

![testgrab16](documentation/readmeimages/testgrab16.png)  ![testgrab16tab](documentation/readmeimages/testgrab16tab.png)

The user should notice that here, the option to click to read their submitted story. When clicked on should reveal the story in it's entirity.  

Before:  
![testgrab17](documentation/readmeimages/testgrab17before.png)

After:  
![testgrab17tab](documentation/readmeimages/testgrab17after.png)

In the event that the user hasn't submitted a story before accessing this page then he/she should be greeted with the flash message informing them of this and a prompt on where to go to do so.  

![testgrab17flash](documentation/readmeimages/testgrab17flash.png)

Considered Pass/Fail: Pass  

## Test 9
### Editing the Users Stories.

Test Description: This is to test that the visitor can access and edit their submitted story.

Steps Taken  
    
- Within the 'Your Stories' page, the option to edit and delete the stories are available to the user.
- Upon selecting the 'Edit' button, the user is taken to the page for editing their story.  
- The story title field should be pre-populated with the users story title and the story field should be pre-populated with the users story.  

Images of Test Results  

![testgrab18](documentation/readmeimages/testgrab18.png)  ![testgrab18tab](documentation/readmeimages/testgrab18tab.png)

Here the user can make changes to both the title of the story and the main body of the story if he/she so wishes to. Once satisfied with the changes made the user should select the 'Save Changes' button to submit the changes to the database and therefore to the users 'Your Stories' page.  

![testgrab19](documentation/readmeimages/testgrab19.png)  

And once 'Save Changes' has been selected the user should see that the changes have been saved. 

![testgrab19tab](documentation/readmeimages/testgrab19full.png)

Considered Pass/Fail: Pass  

## Test 10
### Deleting the Users Story.

Test Description: This is to test that the visitor can access and delete their story if they so wish.

Steps Taken  
    
- Within the 'Your Stories' page, the option to edit and delete the stories are available to the user.
- Upon selecting the 'Delete' button, the user is presented with a second option. Here the user is given the option to change their mind and keep the story or continue with their choice to delete the story.   
 
Images of Test Results  

![testgrab20](documentation/readmeimages/testgrab20.png) 

Once selected this modal appears: 

![testgrab20sure](documentation/readmeimages/testgrab20sure.png)  

If 'No!!!' is selected then the user will be redirected back to the stories page but if the 'Delete' button is selected again then the user is presented with this flash message.  

![testgrab20deleted](documentation/readmeimages/testgrab20deleted.png)

Considered Pass/Fail: Pass 

## Test 11  
### Logging Out.

Test Description: This is to test that the visitor can log out of the site.

Steps Taken  
    
- The user should note that after finishing his/her time on the site then in the top right hand corner the option is there to log out.
- Upon selecting the 'Log Out' option the user should be greeted with the home page again and a flash message informing the user that he/she has been logged out.
- Further confirmation that the user has been logged out should be the navigational items in the Nav bar and the mobile side Nav bar returning back to the limited content again.
 
Images of Test Results  

![testgrab21](documentation/readmeimages/testgrab21.png)  ![testgrab21tab](documentation/readmeimages/testgrab21tab.png)  

Considered Pass/Fail: Pass 

## Test 12
### Accessing Social Icons.

Test Description: This is to test that the social icons redirect the user to the relevant site, opening in a new tab.

Steps Taken 
    
- Should the user wish to explore one of the social icon options then by clicking on one should redirect them to the relevant page in a new tab.  

Images of Test Results  

- Firstly to test the LinkedIn social icon:

![testgrab22b](documentation/readmeimages/testgrab22b.png)  ![testgrab22a](documentation/readmeimages/testgrab22a.png) 
 
Considered Pass/Fail: Pass 

- Next to test the GitHub social icon:

![testgrab23a](documentation/readmeimages/testgrab23a.png)  ![testgrab23b](documentation/readmeimages/testgrab23b.png) 
 
Considered Pass/Fail: Pass

- Lastly to test the Wikipedia social icon:

![testgrab24a](documentation/readmeimages/testgrab24a.png)  ![testgrab24b](documentation/readmeimages/testgrab24b.png) 
 
Considered Pass/Fail: Pass

- CONCLUSIONS
    - After extensive testing across various devices, I was satisfied with the overall look and feel of the site. 
    - I am satisfied that each of the users needs have been addressed.
    - I am satisfied with the content and the presentation of the content.

## Problems and bugs experienced along the way

# Code Validations

## HTML Validator

## Python Validator

I ran my app.py code through the online PEP8 check and was happy with the results.

- This is the result for the PEP8 Online check:
![pythonpep8check](documentation/readmeimages/)



## CSS Validator

I ran my CSS file through the W3C CSS Validator and was pleased with the results.  
Results shown below:  
![cssvalidation](documentation/readmeimages/)

## Javascript Validator

I ran my limited script file through the JSHint Validator and was pleased with the result. 
Results shown below:  
![scriptvalidation](documentation/readmeimages/)

# Lighthouse Testing

I ran the site through Google Lighthouse to check general performance and accessibilities and was reasonably content with the results on both desktop and mobile.  
Results shown below:  

![lighthousetestdesktop](documentation/readmeimages/)
![lighthousetestmobile](documentation/readmeimages/)


# Credits

## Imagery used in the site

## Video used in the site

## Throughout the creation of this project I have referred to the following for assistance and guidance:

- https://codeinstitute.net/  
- https://stackoverflow.com/  
- https://www.geeksforgeeks.org/


# Acknowledgement  