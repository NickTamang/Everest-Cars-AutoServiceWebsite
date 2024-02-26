
Thing-S@ulster.ac.uk
Site Live at (https://nicktamang.github.io/Everest-Cars-AutoServiceWebsite/)
 
Contents
COM458 (34885 ) - Dynamic Web Authoring. 2022-23.	1
1.	Introduction:	3
2.	Justification of the selected technology:	4
3.	Dom Figure	5
4.	Site map of Everest Cars	6
5.	Implementation:	7
6.	W3C Validator:	24
7.	Form validation	29
























1.	Introduction:
Hypertext Markup Language, or HTML. For creating and organising material for the internet, it is a common markup language. The layout and material of a webpage, comprising text, photos, connections, and other multimedia components, may be outlined with HTML. The many components of a webpage, including headers, paragraphs, pictures, links, and forms, are defined by a set of tags in HTML. (Schools, 2023)
Together, HTML for structure, CSS for style, and JS for behaviour helps developing the core building blocks of web development, enabling developers to create engaging, responsive, and user-friendly web applications. With these tools, developers can create a wide range of web projects, from simple websites to complex web applications, and enhance user experience with interactive features, animations and intuitive design.
On this assignment, we have built the dynamic website with the business name Everest Cars which deals with the selling the cars using the HTML for structure, CSS for style, and JS for behaviour of website but  using the existing front-end frameworks.
What are front-end frameworks?
A frontend framework is a pre-built set of tools, libraries, and technologies that help developers build the user interface of a web application. Frontend frameworks typically include pre-built UI components, such as buttons, forms, and navigation menus, as well as stylesheets, JavaScript libraries, and other tools that help developers build a responsive and interactive user interface. (Simform, 2022 Novemver 8)

 

https://learning.ulster.ac.uk/bbcswebdav/pid-7138157-dt-content-rid-31995660_1/xid-31995660_1

On week 5 of our lecture seminar,  we can find the PowerPoint presentation which gave idea to our team on using the existing frameworks and build intuitive, and powerful mobile first front-end framework for faster and easier web development. 
After detail researching on the frameworks our team found out the use of frontend frameworks can greatly simplify the development process, reduce development time and improve the quality of the application. Frameworks provide a consistent structure and set of conventions that make it easier for developers to build complex user interfaces. The various frameworks currently in the market like React, Angular, Vue.js, Bootstrap.
2.	Justification of the selected technology:
Among all the front-end frameworks that are available on the market, Our team found the bootstrap powerful and widely used front-end framework that can help developers build high-quality, responsive web applications more quickly and efficiently.. The bootstrap was originally developed by Twitter and is now maintained by the Bootstrap Core Team.

 
https://learning.ulster.ac.uk/bbcswebdav/pid-7138157-dt-content-rid-31995660_1/xid-31995660_1

On our Coursework 2, we have built the dynamic website using the  Getbootstrap.com frameworks that simplify the process of developing responsive and mobile-first web applications by using existing pre-built codes. These frameworks are designed to be user-friendly and customizable, allowing our team to effectively build functional websites with consistent design patterns. Bootstrap's components, such as alerts, badges, and cards, enable developers to create engaging user interfaces without extensive coding. These framework also includes pre-designed templates and themes, which we easily adapted to fit our project's needs. By using the frameworks provided by getbootstrap.com, Our Team saved the time and got to learn about the real life industry knowledge and create high-quality web projects efficiently. https://getbootstrap.com/docs/4.3/getting-started/download/
 
Figure from: https://getbootstrap.com/docs/4.0/components/navbar/

On this assignment, By learning the bootstrap framework we have built the dynamic website with the business name Everest Cars which deals with the selling the cars. 
Everest Cars is a well-known auto dealer with a focus on selling high-quality vehicles. The UK-based firm has a few years of experience in the industry and offers users a selection of dependable cars at reasonable costs. Everest Cars' dedication to guaranteeing client happiness is one of its distinguishing characteristics. They take great pride in their customer service and are always available to assist customers in finding the ideal car to suit their requirements. Visitors may start by browsing the inventory of Everest Cars online, where they can narrow their search based on criteria like make, model, price range, and certain features. One advantage of buying a vehicle from Everest Cars is that many of their models come with a variety of options that may be adjusted to the buyer's preferences. Customers may select their preferred engines, gearboxes, and safety features, for instance, to guarantee they obtain a car that suits their needs. All things considered; Everest Cars is a fantastic alternative for anyone searching for a extending dependable garage auto selling business to easily accessible trustworthy website.

3.	Dom Figure 

Document Object Model, sometimes known as DOM, is a programming interface for online pages. In other words, it is a method for developers to use JavaScript to access and modify the HTML and XML components of a webpage. A tree-like structure known as the DOM effectively depicts the web content as a hierarchy of nodes. The DOM API offers several methods and attributes that may be used to access and edit each node, which represents an element, property, or section of text inside the page. (Schools, 2023)


 
Fig 1 < https://lucid.app/lucidchart/b5205182-ad16-4736-91d3-9cdb6463e937/edit?page=0_0&invitationId=inv_199dd761-0143-4462-a9c8-3d0cee45ee30#>

Our document (docthtml) is divided into two sections in the provided Dom figure, the head, and the body. The head contains the Meta, title, and style. In contrast, the body has a div id that is then classified into two separate SEO sections, div class (content) and divclass (btns). There are headings 1 through 2 and headings 3 through 4 and a paragraph at divclass (content). On the other hand, it has the heref (contact) and index for the div class (btns).

4.	Site map of Everest Cars
Site map of is the structure representation of our website it contains the linkage, relationships of the pages with each other and goals of our website. (Central, 2021) Here, we have listed different pages and their relationships. They are given below:
Homepage
•	Navigation menu
•	Login/signup
•	Featured cars.
•	Car search function
•	Hour of operation
•	Contact information.
Car
•	All feature cars
•	All new cars
•	All rent cars
•	All car in sale
•	Desire car search function
About
•	Company information
•	Meeting the team
•	Contact information.

Service 
•	Free support
•	Super-fast
•	Repairing
•	Air conditioning
•	Oil change
•	Dealership
•	Security
•	Trusted agent
•	Service videos
Contact
•	Contact information.
•	Online contact form




5.	Implementation:
	Navigation menu:
An application's or website's navigation bar, commonly referred to as a menu bar or nav bar, is a graphical user interface component that typically sits at the top of the screen. This navigation bar provides an essential part of every user interface as it gives users an option to quickly and easily reach the key parts or features of the website or application.

 
Codes:
 

	Homepage:
Everest Cars Garage aims to offer customers a variety of auto-related services, such as customizing, detailing, and repair. The website's homepage is made to provide visitors with a quick summary of the services available and point them in the direction of the relevant web pages.
 

Code:
 
 
 
 

	Car:
If we select car option from navigation bar cars page occurs

 



	Car’s page:

 
 

Our Everest cars site focuses on offering customers a range of auto-related services. The website's car page, offering details about new featured cars, rental cars, and cars that are available for purchase at reasonable costs, is one of its key features.
 
Codes:

 
	For instalment:
Users of our website have the option to buy a car in installment for a specific period of duration in the rental car section. Visitors to the website may choose from a number of car models, and users can focus their search based on their preferences and price range.
 
Codes:
 




	For Sale
The pre-owned vehicles that are for the offer are bought at reasonable costs. Users may access specific details on each vehicle, such as its price, mileage, and condition.


 
Codes:
 
	New Featured cars
The newest and most well-liked models from various companies are displayed in the section related to "new featured cars." Users may explore the various models and discover comprehensive details on each vehicle, including its features, specifications, and cost
 
 
 


	Car search function
Our website offers users the ability to select a model from a cost-speed range or to create their own selection from a list of automobiles that are relevant to their preferences.

 
Codes:
 
In general, Everest's website offers customers a complete platform for all of their car-related needs, from renting a car for a brief vacation to affordably buying a pre-owned car.
	About Us
 

 

Codes:
 
 
 
	Services:
If we select service option from navigation bars service screen appears.
 
Our service comes with a number of advantages, such as free assistance, lightning-quick service, skilled repair, air conditioning service, oil changes, dealership services, and trustworthy security measures. Our team is made up of dependable employees that are committed to delivering excellent service and guaranteeing client happiness. To help clients comprehend the maintenance and repair procedures, we also offer service videos.
We have some list of service in the below:
1.	Free support
2.	Super-fast
3.	Repairing
4.	Air condition
5.	Oil change
6.	Dealership
7.	Security 
8.	Trusted Agent
9.	Service videos

 
 
Code:
 
 


	Contact
When we select contact option from navigation option contact page appears 
 
Simple dynamic website of our assignment is Everest Cars. Everest Cars has been the industry norm for dynamic websites for Ulster University assignments. Everest Cars is a trustworthy auto shop with a focus on selling top-notch cars, our staff is dedicated to providing our clients with vehicles that are dependable, cheap, and match their unique demands. Our educated team is always available to help clients discover the ideal automobile, and we take pleasure in having a large range of vehicles. At Everest Cars, we work hard to uphold honesty and openness throughout the car-buying process to make sure that our clients are happy with their choice.


 
Code:
 
 


	Contact information
As illustrated in figure, customers can contact us through their social media accounts. Here are a few quick ways to get in touch with the Everest website as shown in figure.

 
Codes:
 

Top Nav-Bar:
Our generalise our customer service we have added the opening hours, email of the company and phone number where the customers can easily interact with us with the help of the interactive information on top of the website.
And also the customers can sign up for their account which we store their information on the database of the system. And the can easily view their choice of cars along with the information that they provide which makes the website more interactive to the customers. But as our website is based on dynamic and not online this features is still not available that’s why we added the 404 error page in case anything goes wrong.
 
Code:
 


	Error Handling (404 Page not Found):
We made our website more interactive to the customers. But as our website is based on dynamic and not online this features is still not available that’s why we added the 404 error page in case anything goes wrong.
 
Code:
 




6.	W3C Validator:
The W3C Validator is a crucial tool for making sure that a website is usable by everyone and that it functions uniformly in all browsers and platforms. Web administrators and programmers can use the W3C Validator to find and correct any problems that might prohibit their website from adhering to the suggested standards and rules, which will enhance the browsing experience for website visitors.
•	Cars.html
 

	Solution to error
    


•	About.html
 



•	Cars.htlm
 
•	Contact.html
 





•	Index.html:
   
	
	Solution to fix 


7.	Form validation
Before data is transferred to a server or database, material submitted on a form by the user is validated to ensure that it is accurate and complies with any standards. It entails the use of the client-side or server-side applications that verify the input data and make sure that it satisfies particular requirements, such as being in the right format, being within reasonable limits, and not having any malicious characters or scripts.

•	Login
 

•	Sign-up:
 

 
a.	Login form validation:
 
b.	Sign-up Form Validation:
 

Conclusion:
The goal of an Everest auto selling website is to give users the ability to purchase and sell vehicles online on a platform. Some specific objectives are mentioned below: To offer a user-friendly interface that makes it simple for vendors and buyers to find and list automobiles for sale. To provide a broad selection of cars for sale, including both new and used cars from different manufacturers and pricing points. To guarantee that information on the make, model, year, and condition of the cars is accurate and thorough. To offer a variety of tools and resources, such as automobile history reports, price manuals, and financing choices, to assist buyers and sellers in making educated selections. Ensure that buyers and sellers have a great experience using the website by offering outstanding customer service. Provide a safe and secure platform for transactions by putting in place controls such user authentication and payment. To implement safeguards like user verification and payment protection in order to build a safe and secure platform for transactions. In the end, the goal of an Everest car selling website is to offer a practical and dependable platform for individuals to purchase and sell automobiles while also making sure that the transaction is transparent, accurate, and secure.

References
Central, G.S. (2021) Google Search Central. Available from: https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview [Accessed 2023]. 
Document Object Model (DOM) (no date) Mozilla Developer Network. Available from: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model [Accessed 20 April 2023]. 
S., A. (no date) HOSTINGER TUTORIALS. Available from: https://www.hostinger.co.uk/tutorials/what-is-html 
Schools, W. (2023) W3 Schools. Available from: https://www.w3schools.com/jsref/dom_obj_figure.asp [Accessed 24 April 2023]. 
Simform (2022 Novemver 8) Available from: https://www.simform.com/blog/best-frontend-frameworks/#:~:text=A%20front-end%20framework%20is%20a%20set%20of%20tools,can%20easily%20design%20and%20build%20the%20application%20interface. [Accessed 24 April 2023]. 







