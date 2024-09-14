
# Green Grove Community Website

## Overview
**Green Grove** is a community-driven platform designed to promote environmental sustainability by encouraging greenery in polluted urban areas. Users can buy and sell plants, organize plantation events, and write blogs to spread environmental awareness.

## Key Features
- **Marketplace**: Buy and sell plants with ease.
- **Community Engagement**: Organize and participate in plantation events.
- **Blogging**: Share tips, ideas, and stories related to environmental sustainability.
- **Modular Architecture**: Built with SpringBoot microservices for scalability and efficient service discovery using Eureka Server.
- **High Performance**: Reduced system downtime by 30%, resulting in improved overall performance.

## Tech Stack
- **Backend**: Java, SpringBoot, Microservices, MySQL
  - Modular services for users, products, and events.
  - Scalable architecture with separate services for Sellers, Users, Addresses, and Products.
- **Frontend**: Available on my teammate's GitHub repository. [Link to Frontend Repo](https://github.com/mohankumarhr/greengrove.git)

## Installation and Setup
1. Clone the backend repository:
   ```bash
   git clone https://github.com/jeevanthecoder/Green-Grove-Community-Website.git
   ```
2. Navigate to the backend directory and build the project:
   ```bash
   cd product-service
   mvn clean install
   ```
   ```bash
   cd user-service
   mvn clean install
   ```
3. Run the SpringBoot application:
   ```bash
   mvn spring-boot:run
   ```
4. For the frontend setup, follow the instructions provided in the frontend repo linked above.

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License
This project is licensed under the Apache License 2.0.
