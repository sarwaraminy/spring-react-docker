<h1>Enterprise Application with MySQL, Java Spring Boot, and React </h1>

Welcome to our Enterprise Application project! This project demonstrates the integration of MySQL database with Java Spring Boot for the backend and React for the frontend. We've implemented essential functionalities needed for enterprise applications, including CRUD operations, report generation in PDF and Excel formats, sorting, and search capabilities.

<h2>Features</h2>
<b>CRUD Operations:</b> Perform Create, Read, Update, and Delete operations on your enterprise data.<br />
<b>Report Generation:</b> Generate reports in both PDF and Excel formats for easy data analysis.<br />
<b>Sorting:</b> Sort data by column titles to quickly find the information you need.<br />
<b>Search Ability:</b> Search through your data efficiently with our search functionality.<br />
<b>User Authentication and Authorization:</b> Secure your application with user authentication and authorization.<br />
<b>User Registration Page:</b> Allow new users to register with your application.<br />
<b>User Role:</b> Implement user roles to manage permissions within your application.<br />
<h4>before running docker-compose build your spring backend to creat *.jar file in target/ folder</h3>
<ul><li>mvn package -DskipTests=true</li></ul>
<b>Dockerization:</b> Containerize your application components for easy deployment and scalability.<br />
<ul>
  <li>docker-compose down</li>
  <li>docker-compose build</li>
  <li>docker-compose up -d</li>
  <h4>Stop all images</h4>
  <li>docker-compose stop</li>
  <h4>Docker command that is removing an image</h4>
  <li>docker rmi {image-id} --force</li>
  <h4>Docker command that is removing a container</h4>
  <li>docker rm {container-id}</li>
  <h4>To interact with docker mysql container run the following docker command</h4>
  <li>mysql -h 127.0.0.1 -P 6604 -u root -p</li>
  <h4>to see the an image information</h4>
  <li>docker inspect image id</li>
</ul>
<b>Flywaydb:</b>  Implement database migration tool that allows you to manage and automate the evolution of your database schema over time.

<b>Technologies Used</b>
<b>MySQL:</b> A robust relational database management system for storing your enterprise data.<br />
<b>Java Spring Boot:</b> A powerful framework for building Java-based enterprise applications, providing features such as dependency injection, RESTful web services, and more.<br />
<b>React:</b> A JavaScript library for building user interfaces, offering a component-based approach for creating interactive UIs.<br />

<h1>Prerequisites</h1>
<h3>Before getting started, ensure you have the following installed:</h3>
<ul>
  <li> Java Development Kit (JDK)</li>
  <li> Node.js and npm</li>
  <li> MySQL Server</li>
  <li> Docker (optional, for containerization)</li>
</ul><br>

<h2>Getting Started</h2>

<h2>Clone the repository:</h2> 
<b>git clone https://github.com/sarwaraminy/sprint-boot-with-react.git</b>

<h2>Backend Setup:</h2>

Navigate to the backend directory.<br />

Configure your MySQL database settings in application.properties.<br />

Run the Spring Boot application:<br />


./mvnw spring-boot:run<br />
Frontend Setup:<br />

Navigate to the frontend directory.<br />

<h2>Install dependencies:</h2>
npm install file-server<br />
npm install axios<br />
npm install react-router-dom <br />

npm install<br />
Start the React development server:<br />

npm start<br />
<h2>Access the Application:</h2>

Open your web browser and visit http://localhost:3000 to access the application.<br /><br />

<h2>Contributing</h2>
We welcome contributions from the community! Feel free to open issues for bug fixes or feature requests, and submit pull requests to contribute code.<br />

<h2>Deploy</h2>: to deployee you need to do the following:<br />
<ul>
<li>Update pom.xml and add the tomcat dependency and update build pacakges</li>
<li>Update your Main application Class DemoApplication.java</li>
<li>Update pom.xml and add the tomcat dependency and update build pacakges</li>
<li>Update your Main application Class DemoApplication.java</li>
<li>run this command in your project: mvn clean package
<li>After running this command, you should find the demo-0.0.1-SNAPSHOT.war file in the target directory.</li>
</ul>

<h1>Screenshots</h1>
<h3>Login page</h3>
<image alt="Room Login page" src="screenshots/login.png" />
<h3>Registraion page</h3>
<image alt="Room Registration page" src="screenshots/signup.png" />
<h3>Dashboard page</h3>
<image alt="Room Dashboard page" src="screenshots/dashboard.png" />
<h3>CRUD opration</h3>
<image alt="Room CRUD opration" src="screenshots/CRUD-opration.png" />


<b>License</b><br />
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.<br />

<b>Contact</b><br />
If you have any questions or suggestions, please feel free to contact us at sarwaraminy@gmail.com .<br />

<b>Thank you for using our Enterprise Application! We hope it serves your needs effectively</b>.<br />
