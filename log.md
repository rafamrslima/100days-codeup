# 100 days of codeUp

### Day 1/100
Today I started a course about Go, I took some time to get familiar with the structure of the language, basic syntax, operators and variables.

### Day 2/100
Today I learned about numeric systems, constants and the runtime package in Go, I also did the local environment setup for developing in VS code and started checking possible projects to develop in order to practice Go.

### Day 3/100
Today I kept my studies about golang, I learned how to create and manipulate arrays, slices and maps, tested some variations of for loop and learned how to use structs. I also solved two leetcode problems using Go.

### Day 4/100
Today I learned how to create functions in Go, how to return multiple values, how everything is passed by value and never by reference.

### Day 5/100
Today I studied few more things about Go, I learned about 'defer', interfaces, how to use polymorphism, and I tested on my local environment some things related to pointers and memory address.

### Day 6/100
Today I learned about recursive functions, callback and pointers in Go, I also started developing a little practical project to enhance my skills in the language.

### Day 7/100
Today I learned about the concepts of working with JSON in Go - how to encode and decode datatypes, I searched about go modules and tested the package github.com/spf13/cobra for working with interactive CLI applications.

### Day 8/100
Today I learned about hashing using the package bcrypt and I started learning the theory for concurrency and paralelism with goRoutines.

### Day 9/100
I keep learning Golang, today I saw the usage of mutex for parallel jobs, race conditions, how Go manage the threads according to the number of cpus available in the computer. I learned also how to do cross-compilation generating executable for windows from a mac for example.

### Day 10/100
I keep learning Golang, today I watched some content about channels and I need to create some tests locally for better understanding.
I also started a practical project for fetching crypto prices using Go.

### Day 11/100
Today I learned a bit more about channels (range, close, select). And I kept working on my practical project for fetching crypto prices, I implemented an http request to get data from api.coingecko.com and I created a interactive CLI where the user can choose which coins to fetch the price.

### Day 12/100
Today I kept studying Golang - I saw some theory about pointers, stack and heap. And I made some more changes in the coin-fetcher project, adding a table price in the console for a more friendly view.

### Day 13/100
Today I implemented the SaveToFile function in my coin-fetcher project in golang, with options to save the retrieved data in a csv or json file. I also learned a bit about the context package in Go which is used for cancellations or timeouts.

### Day 14/100
Today I learned about error handling in Go, the different usages of the log package, and how to use panic and recover keywords for managing the application flow.

### Day 15/100
Today I learned about error type in Go, how to construct an error in any part of my application, and the convention for using error type as return of functions. I also learned how to create documentation of my code using godoc.

### Day 16/100
I keep studying golang, today I learned how to create unit tests for my projects using the standard library, and learned about the design patterns fan-in, fan-out and pool of workers.

### Day 17/100
Today I practiced a bit more of coding in Go, I reviewed some content channels (receiving, sending) and synchronization of channels. And I uploaded a new leetcode solution solving the validParentheses problem using stack.

### Day 18/100
Today I had a look on common interview questions in Golang and based on that I started going deeper in some topics, the first was how Garbage collector works in go, I learned that it works based on mark-sweep strategy, it runs concurrently with goroutines and it requires just a minimal time to execute. The second topic was about slices and arrays, how slices always have an underlying array and how a new array is created when appending to a slice which has reached its maximum capacity.

### Day 19/100
Today I tested some different ways to create slices in Go using cap and len. I also created an interface and concrete implementations of that interface in order to test polymorphism.

### Day 20/100
I keep studying golang, today I created some examples of functions receiving parameters like pointers, maps, slices, I took some time to understand what happens when we modify the slice or map inside the function. I also learned and tested the sync.RWMutex, which it's useful when working with concurrent programs.

### Day 21/100
I keep studying golang, today I searched about packages that make it possible to connect a Go application to a database, I also started a practical project where I will read messages from a service bus queue, log the messages received in a database, then create and send emails to specific recipients using goroutines.

### Day 22/100
I keep studying golang, today I created a listener for an Azure service bus instance, the listener will be able to process multiple messages at the same time, for that I created a pool of workers that will use goroutines to process the jobs from a receiver channel. 

### Day 23/100
I keep studying golang, today I learned how to validate emails and I implemented a MessagesHandler in my practical project with the goal of receiving the service bus message, validating it, saving the message in the database for reference, then triggering the email service. This project is helping me on how to structure the project and work with different packages, dealing with real life scenarios.

### Day 24/100
Golang Studies -> In the practical project I am building, today I implemented the code responsible for saving records into the database using the pgxpool package. I also improved the logic of creating a listener to make it run in background while waiting for messages to reach the queue. I also learned about preempt in the golang runtime and how it is important for the general performance and behaviour of the application.

### Day 25/100
Golang Studies -> In the practical project I am building, today I decided to save files to blob storage instead of sending emails. So I created a resource on azure, I connected my go app to the resource and created a function to upload a file to it. Now the app is able to listen to a service bus queue, create go routines that will receive and process the message, then log the info in the database and save the file (report) in a folder in azure storage.

### Day 26/100
Today in the practical project I am building in Go, I implemented pdf creation based on data coming from the db, so I also created a function that queries the database and converts the data retrieved to a new struct. And I also implemented the upload of the pdf to azure blob storage.

### Day 27/100
Golang Studies -> today in the distributor project, I fixed the validation of some input fields and I added a retry policy for the blob storage files upload.

### Day 28/100
Golang Studies -> Today I solved a coding challenge in leetcode about finding palindromes, I learned and practiced some important concepts of the language like how to work with slices of runes and how to convert and compare strings.

### Day 29/100
Today I focused on studying some algorithms, especially binary search, which is common in coding challenges. I used golang in the examples.

### Day 30/100
I keep learning golang, today I created a web api using the native http package. The API exposes one get method that receives an id as parameter, it goes to db and retrieves some data there based on the given id, then it converts the data to json and returns it to the API caller. The API also returns bad request or not found depending on the case.

### Day 31/100
Today I added a readme.md to the web api and uploaded it to the github, I also dedicated some time on searching about the web3 job market in general and about the required knowledge to work as backend engineer.

### Day 32/100
Today I did a review about common questions in golang technical interviews, including topics like memory management, slices, channels, goroutines, interfaces etc.

### Day 33/100
Today I learned about how to compare structs in Go, using == is enough when the structs are comparable (having just fields like boolean, string, int, pointer). But in most cases manual comparison field by field is preferred because of the clarity and good performance.

### Day 34/100
Today I practiced binary search creation using Golang. I uploaded to github a function that implements a basic binary search that finds a specific number in a sequence of integers, if the number is not present I return -1.

### Day 35/100
Today I did a review about blockchain basics, EVM and solidity development. I also studied some content about the essential algorithms that need to be mastered in order to solve leetcode problems more efficiently.

### Day 36/100
Today I did a refactoring in the crypto-fetcher project, creating helpers in different folders in order to separate responsibilities and make the code cleaner.

### Day 37/100
Today I implemented basic jwt authentication in the crypto-fetcher API by importing the jwt package into the application. I also created a basic controller and moved some code there to achieve better readability in the solution.

### Day 38/100
Today I studied algorithms, I took some time to review vector models and practice some coding. I Also watched youtube videos about some math concepts.

### Day 39/100
Today I took some time to understand how GO ORM works and how it is useful when dealing with databases, I also learned about relationships and migrations.

### Day 40/100
Today I learned more about garbage collection in Go, I saw that it's possible to define the target percent of collection and it is possible to manually trigger the GC to perform the cleanup. I also learned what memory leak is and possible causes of memory leak (keep referencing unused objects for example, caches that never expire).

### Day 41/100
Today I started learning Rust, I watched some content about the variable types and how to declare them as mutable, some rules about the language not allowing unused variables for example and how to create functions.

### Day 42/100
I keep studying Rust, today I saw concepts of ownership, borrowing and references, and control flow.

### Day 43/100
Rust studies - today I learned about statements, how is the 'return' from functions. I reviewed concepts of stack and heap memory, and I saw some examples of ownership. I also learned how Cargo is used to start a project.

### Day 44/100
Rust studies - today I started practicing coding, created examples with different data types, I learned how to use structs, traits, match and tuples.

### Day 45/100
Rust studies - Today I learned the basics about pointers and also some rules related to references, for example we can have at any given time only one mutable reference or any number of immutable references, this behaviour prevents data races.

### Day 46/100
Rust studies - Today I learned how to work with enums, vectors and hashmaps in Rust, I created some examples of each to see how they work in practice.

### Day 47/100
Rust studies - Today I learned the difference between String and &str and when to use each of them, I also took a look at the setup requirements to start developing for Solana.

### Day 48/100
Rust studies - Today I took some time to understand the build process in Rust and how to build for different environments, I also learned how to unit test my applications using the native rust toolchain.

### Day 49/100
Rust studies - Today I took a look at how async code is written in Rust using Futures.

### Day 50/100
Today I learned more about blockchain and bitcoin, PoW and PoS, hashing and signatures. I took a closer look at how bitcoin works in terms of transactions and validation, and how the mining process works.

### Day 51/100
Rust Studies -> I cloned the Rustlings repository on my local env to practice programming with some exercises, so far I have solved the exercises related to variables, functions, primitive types and vectors. In parallel I am reading the Rust official book to get some concepts and examples.
