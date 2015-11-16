HTTP Receiver
=============

This project is an attempt to make an simple clean Java program with an embedded web-server.

My initial goals for this project
---------------------------------

* Service needs to save payload with all non-secret http headers
* HTTP response need to be configurable - based on used credentials
* The source of credentials can be configured - redis key-value database
* The data target is configurable - log to console, Amazon S3, redis, mongo
* Everything needs to be clean and well tested



Potential long term goals
-------------------------
0. Write language agnostic system tests, something that can give an idea of the performance of application
0. Make an performant Java implementation without heavy frameworks
0. Port the application to other languages - golang, others?
