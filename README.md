Deployment of a 3-tier application using Docker compose, including configuring public IP addresses and setting up necessary security group rules for accessing the frontend, API, and database services.

Check the data for .env.sample files

Import data into Mongo DB container:      docker exec -it container_id mongoimport --db wanderlust --collection posts --file ./data/sample_posts.json --jsonArray
