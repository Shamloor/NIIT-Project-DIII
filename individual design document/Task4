+ Input: Linux script analysis result picture MySQL data
+ Responsible for the web development of the entire system
+ Basic functions, such as registering, logging in, and retrieving passwords, are complete. Note that these functions must use the Mysql database on the Linux VM.
mysql list clause:
```
CREATE TABLE `db_account` (
`id` int NOT NULL AUTO_INCREMENT,
`username` varchar(255) DEFAULT NULL,
`email` varchar(255) DEFAULT NULL,
`password` varchar(255) DEFAULT NULL,
`role` varchar(255) DEFAULT NULL,
`register_time` datetime DEFAULT NULL,
PRIMARY KEY (`id`),
UNIQUE KEY `unique_email` (`email`),
UNIQUE KEY `unique_username` (`username`)
) ENGINE=InnoDB AUTO_INCREMENT=6 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
```

+ Front end vue page design and beautification, the front end is divided into four parts, the home page is a brief introduction of our bank loss analysis service, and scrolling pictures. The second part of the visual analysis design, the first user upload the previous user record data set, passed to the remote server for subsequent analysis, passed the results of visual analysis. Part 3, Training section Click Start training wait time and then pass in the results. In the fourth part, the prediction part uploads the new user behavior file for prediction, and the obtained result part can be displayed to the front-end. Users can click download to get the csv including the probability of user loss.
Back-end springboot user request logic processing and remote virtual machine connection and return value processing.
The back end springboot writes services to connect to remote servers, as well as user requests, MySQL database connections, etc. The controller accepts the call service by making front-end get and post requests.
