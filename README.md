# Web_Development_w_Google_s_Go_Solution

# Document & exercises: 
 Go-Web folder

# 1. Getting started 
 1. Why choose Go ( golang ) for web development
 2. Course prerequisites
 3. Course resources  
 3.1 Course Documents
 4. Language review
 5. How to succeed

# 2. Templates
 1. Understanding templates
 2. Templating with concatenation
 3. Understanding package texttemplate parsing & executing templates
 4. Passing data into templates
 5. Variables in templates
 6. Passing composite data structures into templates
 7. Functions in templates
 8. Pipelines in templates
 9. Predefined global functions in templates
 10. Nesting templates - modularizing your code
 11. Passing data into templates & composition
 12. Using methods in templates
 13. Hands-on exercises
 14. Using package htmltemplate, character escaping, & cross-site scripting
 
# 3. Creating your own server
 1. Understanding servers
 2. TCP server - write to connection
 3. TCP server - read from connection using bufio.Scanner
 4. TCP server - read from & write to connection
 5. TCP server - code a client
 6. TCP server - rot13 & in-memory database
 7. TCP server - HTTP request  response foundation hands-on exercise
 8. TCP server - HTTP method & URI retrieval hands-on exercise
 9. TCP server - HTTP multiplexer
 
# 4. Understanding nethttp package
 1. nethttp package - an overview
 2. Understanding & using ListenAndServe
 3. Foundation of nethttp Handler, ListenAndServe, Request, ResponseWriter
 4. Retrieving form values - exploring http.Request
 5. Retrieving other request values - exploring http.Request
 6. Exploring http.ResponseWriter - writing headers to the response
 7. Review
 
# 5. Understanding routing
 1. Understanding ServeMux
 2. Disambiguation func(ResponseWriter, Request) vs. HandlerFunc
 3. Third-party servemux - julien schmidt’s router
 4. Hands-on exercises
 5. Hands-on exercises - solutions # 1
 6. Hands-on exercises - solutions # 2

# 6. Serving files
 1. Serving a file with io.Copy
 2. Serving a file with http.ServeContent & http.ServeFile
 3. Serving a file with http.FileServer
 4. Serving a file with http.FileServer & http.StripPrefix
 5. Creating a static file server with http.FileServer
 6. log.Fatal & http.Error
 7. Hands-on exercises
 8. Hands-on exercises - solutions
 9. The http.NotFoundHandler
 
# 7. Deploying your site
 1. Buying a domain - google domains
 2. Deploying to google cloud
 
# 8. Creating state
 1. State overview
 2. Passing values through the URL
 3. Passing values from forms
 4. Uploading a file, reading the file, creating a file on the server
 5. Enctype
 6. Redirects - overview
 7. Redirects - diagrams & documentation
 8. Redirects - in practice
 9. Cookies - overview
 10. Cookies - writing and reading
 11. Writing multiple cookies & hands-on exercise
 12. Hands-on exercise solution creating a counter with cookies
 13. Deleting a cookie
 
# 9. Creating sessions
 1. Sessions
 2. Universally unique identifier - UUID
 3. Your first session
 4. Sign-up
 5. Encrypt password with bcrypt
 6. Login
 7. Logout
 8. Permissions
 9. Expire session
 
# 10. Amazon Web Services
 1. Overview
 2. Creating a virtual server instance on AWS EC2
 3. Hello World on AWS
 4. Persisting an application
 5. Hands-on Exercise
 6. Hands-on Solution    
 7. Terminating AWS services
 
# 11. Relational Databases
 1. Overview
 2. Installing MySQL - Locally
 3. Installing MySQL - AWS
 4. Connect Workbench to MySQL on AWS
 5. Go & SQL - Setup
 6. Go & SQL - In Practice
 
# 12. Scaling On AWS
 1. Overview of Load Balancers
 2. Create EC2 Security Groups
 3. Create an ELB Load Balancer
 4. Implementing The Load Balancer
 5. Connecting To Your MySQL Server Using MySQL Workbench
 6. Hands-on Exercise
 7. Hands-on Solution
 8. Autoscaling & CloudFront
 
# 13. Photo Blog
 1. Starting Files
 2. User Data
 3. Storing Multiple Values
 4. Uploading Pictures
 5. Displaying Pictures
 
# 14. Web Dev Toolkit
 1. Keyed-Hash Message Authentication Code (HMAC)
 2. Base64 Encoding
 3. Web Storage
 4. Context
 5. TLS & HTTPS
 6. JSON - JavaScript Object Notation
 7. Go & JSON - Marshal & Encode
 8. Unmarshal JSON with Go
 9. Unmarshal JSON with Go using Tags
 10. Hands-On Exercise Solution
 11. AJAX Introduction
 12. AJAX Server Side    
 
# 15. Go & Mongodb
 1. Organizing Code Into Packages
 2. Create User & Delete User
 3. MVC Design Pattern - Model View Controller
 4. Install Mongodb
 5. Connect to Mongodb
 6. CRUD with Go & Mongodb
 7. Hands on Exercise & Solution
 8. Hands on Exercise & Solution
 9. Hands on Exercise & Solution
 
# 16. Docker
 1. Introduction to Docker
 2. Virtual Machines & Containers
 3. Installing Docker
 4. Docker Whalesay Example
 5. Using a Dockerfile to Build An Image
 6. Launching a Container Running Curl
 7. Running a Go Web App In a Docker Container
 8. Pushing & Pulling To Docker Hub
 9. Go, Docker & Amazon Web Services (AWS)
 
# 17. PostgreSQL
 1. Installing Postgres
 2. Create Database   
 3. Create Table
 4. Insert Records
 5. Auto Increment Primary Key
 6. Hands-on Exercise 
 7. Hands-on Exercise - Solution
 8. Relational Databases
 9. Query - Cross Join
 10. Query - Inner Join   
 11. Query - Three Table Inner Join
 12. Query - Outer Joins
 13. Clauses
 14. Update a Record
 15. Delete a Record
 16. Users - Create, Grant, Alter, Remove
 17. Go & Postgres
 18. Select Query
 19. Web App
 20. Query Row
 21. Insert Record
 22. Update Record
 23. Delete Record
 24. Code Organization
 
# 18. MongoDB
 1. NoSQL
 2. MongoDB
 3. Installing Mongo
 4. Database
 5. Collection
 6. Document
 7. Find (aka, query)
 8. Update
 9. Remove
 10. Projection
 11. Limit
 12. Sort
 13. Index
 14. Aggregation
 15. Users
 16. JSON
 17. Create Read Update Delete (CRUD)