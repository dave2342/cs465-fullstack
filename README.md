# CS-465-Full-Stack-Development
## Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).    

We initially useed Express HTML with JavaScript to display static HTML web pages to a user, and then followed up by creating an SPA. Using Express, the content was rendered server-side and displayed to a user based on their requests. This server-side rendering and the use of multiple HTML pages helps make the website easily crawl-able by search engines. One main downside to using Express is that it could potentially be slower, for both the server as well as users visiting, since each client request requires a new page to be rendered.  

With the SPA (Single-Page-Application), we used the Angular framework, which is often used to create a dynamic website. The initial request from a client/user is sent to the server, which returns the initial page. From here, the content is dynamically updated on the same, initial HTML page. This creates a better and faster user experience. This type of application also makes it more difficult for search engines to crawl, so potential search results including the application's pages may be omitted.  

Why did the backend use a NoSQL MongoDB database?    

The backend used this type of database because of its simple and flexible design. Using MongoDB allowed us to store our trip data in JSON format, which was a perfect choice for our application. JSON format also integrates easily with JS frameworks, and since we used Angular, MongoDB was ideal!   

## Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?  
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.    

JSON and JavaScript are very different, as JSON is a format used to store and transport data, formatted as plain text. JavaScript, on the other hand, is a programming language that helps create more dynamic and interactive web pages. We saved our trip data in a JSON format, but parts of the application were used with JavaScript, as it is a client-side language and we used Express for this.  

JSON tied the front and backend development pieces together as it was the format of data used to transport data in either direction. If a client/user made a request, the server would retrieve the JSON-based data and display it in a "pretty" way for the user. ALso, for specific functions of the app, such as adding/editing a trip, the front-end sends the new data to the back-end in a JSON format to keep the same structure of data.  

## Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.    

We used various methods for testing our different endpoints of the application. HTTP requests include methods such as GET, POST, PUT, DELETE, etc. We used the methods of GET, POST, and PUT with the use of the application called Postman. Endpoints are the specific URL where the method would be accessed. If we wanted to do something such as "get" a list of all available trips, we could use the GET request method, and the endpoint URL could be /api/trips. GET is used to pull data from the server, POST is used to submit/enter data, and PUT is used to update data.  

Security should be one of the most important aspects of developing an application, website, etc. Ensuring the safety of users' data as well as the company's data is needed for success. There are many types of security that can be used, including input validation, authentication and authorization, and even CORS (which we used in Module 7). Validating the user input can prevent malicious attacks from users attempting things such as SQL injection, authentication prevents unauthorized users from accessing/doing tasks they shouldn't be allowed to, and authorization affects the available access to users who have been authenticated. CORS is used to share resources from the application to other domains, such as limited/allowing access from a localhost port.  

## Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?    

I have learned quite a bit from this course. While some of the coding was a bit over my head, and there were a LOT of files we created and edited, I believe I can use this new knowledge to further my education and professional goals. Over time, I would love to learn more about developing full stacks applications, and this course showed me a great introduction on the steps it takes to successfully create a fully working application.
