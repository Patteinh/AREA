# AREA - Major 2023 📱

## Table of Contents 📑

- [Overview of AREA](#overview-of-area-)
- [Documentation](#documentation-)
- [Technology Stack](#technology-stack-)
- [Libraries Used](#libraries-used-)
- [AREA Diagram](#area-diagram-)
- [Integrated External Services](#integrated-external-services)
- [Getting Started with AREA](#getting-started-with-area-)
- [License](#license-)

<br>

## Overview of AREA 🔎

AREA (Action Reaction) is an automation platform designed to automate interactions between various services. Inspired by platforms like IFTTT (If This Then That) and Zapier, AREA aims to provide users with a means to automate repetitive tasks.

### Main Objectives:

- Provide an intuitive user interface for creating and managing automations.
- Integrate a variety of popular services and enable seamless interactions between them.

### Key Features:

- Automation Creation: Users can create automations by linking an action from one service to a reaction from another service.
- User Management: Users can register, log in, and manage their profiles.
- Service Management: Users can connect and manage different services to their AREA account.

### General Architecture:

- Server: The heart of AREA, managing users, services, and automations.
- Web Client: A web interface for users to interact with the platform.
- Mobile Client: A mobile application for interaction on mobile devices.
- Database: Stores user data, service configurations, and automations.

<br>

## Documentation 📖

Below you'll find links to detailed documentation for the AREA project, including technical information, user guides, and system diagrams.

- **Technical Documentation**: Detailed information on the system architecture, libraries used, and API references.
🔗 [Read the Technical Documentation](https://www.canva.com/design/DAFwICz4VGY/VmUUTWtZ4N9dbpc8okFW3w/edit?utm_content=DAFwICz4VGY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 🔗

- **User Guide**: Instructions on how to use the AREA platform, set up triggers and actions, and integrate services.
🔗 [Read the User Guide](https://www.canva.com/design/DAFwIbsQJVE/1CG-esl8EwN7hWhHDWXmHQ/edit?utm_content=DAFwIbsQJVE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 🔗

- **System Diagram**: Visual representation of the AREA system components and their interactions.
🔗 [View the AREA Diagram](https://drive.google.com/file/d/1JO7P4ckywCi8hnC5euNMw6AVnJKtVCMT/view?usp=drive_link) 🔗

<br>

## Technology Stack 💻

<p align="center">
    <img src="https://skillicons.dev/icons?i=mongodb,nodejs,flutter,dart,androidstudio,react,ts,css,aws,githubactions" />
</p>

This section describes the key technologies used for building and deploying AREA, covering the database, server, mobile, and web clients, as well as the containerization environment.

<br>

<p align="center">
    <img src="https://skillicons.dev/icons?i=mongodb" />
</p>

### Database:

- MongoDB: A NoSQL database chosen for its flexibility and ability to handle structured and unstructured data (stores data in BSON documents).
- Mongo Compass: Used for a visual representation and easy interaction with the MongoDB database.

<br>

<p align="center">
    <img src="https://skillicons.dev/icons?i=nodejs" />
</p>

### Server:

- Node.js: Server-side JavaScript execution environment, chosen for its rich library ecosystem.

<br>

<p align="center">
    <img src="https://skillicons.dev/icons?i=flutter,dart,androidstudio" />
</p>

### Mobile Client:

- Flutter: Google's mobile development SDK, enabling the creation of high-quality native applications for iOS and Android from a single codebase.

<br>

<p align="center">
    <img src="https://skillicons.dev/icons?i=react,ts,css" />
</p>

### Web Client:

- React: JavaScript library for building user interfaces, chosen for its modularity.

<br>

<p align="center">
    <img src="https://skillicons.dev/icons?i=docker" />
</p>

### Containerization and Deployment:

- Docker: Used to containerize the application and ensure consistent deployment environments.
- Docker Compose: Used to define and run multi-container Docker applications.

<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws" />
</p>

### Cloud and Infrastructure Services:

- AWS (Amazon Web Services):
  - EC2 (Elastic Compute Cloud): For hosting the application servers with an EC2 instance.
  - Route 53: For domain name management, using AWS for the DNS system.
  - Elastic Load Balancing: For efficiently distributing incoming traffic and for high availability.
  - VPC (Virtual Private Cloud): Configuring an isolated network within AWS, allowing control over AREA's network environment.
  - Network Interfaces: For configuring network interfaces associated with EC2 instances.
  - ARN (Amazon Resource Name): A unique identifier assigned to the Load Balancer in AWS.

<br>

## Libraries Used 📚

For a comprehensive list of all libraries and dependencies utilized in this project, as well as their versions and purposes, please refer to our detailed technical documentation. The documentation provides in-depth insights into how each library contributes to the functionality of AREA and ensures that all components work seamlessly together.

🔗 [Read the full technical documentation for libraries details](https://www.canva.com/design/DAFwICz4VGY/VmUUTWtZ4N9dbpc8okFW3w/edit?utm_content=DAFwICz4VGY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

<br>

## AREA Diagram ✏️

<div style="text-align: right;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Diagrams.net_Logo.svg/800px-Diagrams.net_Logo.svg.png" alt="Draw.io Logo" width="60" style="display: block; margin: auto;">
</div>

🔗 [View AREA Diagram](https://drive.google.com/file/d/1JO7P4ckywCi8hnC5euNMw6AVnJKtVCMT/view?usp=drive_link).

<br>

## Integrated External Services

<div style="text-align: center;">
  <img src="https://cdn-icons-png.flaticon.com/128/1163/1163657.png" alt="OpenWeather Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/2972/2972531.png" alt="dateTime logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/300/300221.png" alt="Google Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/5968/5968534.png" alt="Gmail Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/3670/3670147.png" alt="YouTube Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/2504/2504780.png" alt="Dropbox Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/733/733609.png" alt="GitHub Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/3669/3669986.png" alt="Spotify Logo" width="60" style="margin-right: 15px;">
  <img src="https://cdn-icons-png.flaticon.com/128/3669/3669999.png" alt="Twitch Logo" width="60">
</div>


<br>

These external services are integrated into AREA, allowing users to link their accounts from these platforms with their AREA profile, thus facilitating the automation of interactions between various services.

To enhance this experience, AREA employs the concept of "ingredients."
Ingredients are key data snippets extracted from triggers, automatically identified to simplify the creation of actions. Ingredients might include device names, trigger times, or other service-specific data. Look for the flask icon to use them in action setups, adding a layer of customization to your automation flows.

<br>

For complete details of each service trigger, actions and ingredients read the full technical documentation:

🔗 [AREA Technical Documentation](https://www.canva.com/design/DAFwICz4VGY/VmUUTWtZ4N9dbpc8okFW3w/edit?utm_content=DAFwICz4VGY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

<br>

## Getting Started with AREA 💾

### Local Setup:
1. Ensure Docker and Docker Compose are installed on your local machine.
2. Clone the AREA project repository.
3. **Environment Configuration:**
   - Navigate to the server directory.
   - Create a `.env` file with the necessary environment variables for your setup.
4. Navigate to the project root directory in your terminal.
5. Run `docker-compose build` to construct the required Docker images.
6. Start the services with `docker-compose up`.
7. Verify the services:
   - AREA Server: `http://localhost:8080`
   - AREA Web Client: `http://localhost:8081`

### AWS Setup:
1. Connect to your AWS EC2 instance via SSH.
2. **Environment Configuration:**
   - Navigate to the server directory.
   - Create a `.env` file with the necessary environment variables for your setup.
3. If you have made changes to the code or if it's the first setup, run `docker-compose build`.
4. Start the services with `docker-compose up -d` to run them in the background.
5. Verify the services:
   - AREA Server: Access `https://api.techparisarea.com` to ensure the server is up and running.
   - AREA Web Client: Access `https://techparisarea.com` to ensure the web client is operational.
6. Ensure proper ports are opened in your EC2 security group and services are configured to use HTTPS with the correct SSL certificates for encryption.


## License ⚖️

This project is released under the MIT License. See `LICENSE` for more details.
