# Cybersecurity-Incident-Response-System

## Project Overview
This project is a **Cybersecurity Incident Response System** designed to help security teams manage, track, and respond to network security incidents efficiently. It provides a web-based interface for incident management, integrates with external threat intelligence APIs to retrieve and display relevant data, and stores all incident information in a MongoDB database.

The system includes features such as incident creation, modification, deletion, and viewing. Additionally, it automates the retrieval of external threat intelligence to support security teams in identifying potential threats in real-time.

## Features
- **User Interface**: A responsive web interface built with React.js that allows users to view and manage network security incidents.
- **Incident Management**: Full CRUD (Create, Read, Update, Delete) functionality for incidents.
- **Threat Intelligence Integration**: Real-time retrieval of threat data from the **CIRCL Information Sharing Platform (CISP) API**.
- **Database**: MongoDB backend for storing incidents and threat data.
- **Automation**: Automatically pulls threat intelligence for every new incident created, helping to identify malicious actors or IP addresses.
- **Security**: Basic user authentication and authorization for accessing the management panel.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript (React.js)
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **External API**: CIRCL Information Sharing Platform (CISP) API for threat intelligence
- **Other Tools**: Mongoose for MongoDB object modeling, Axios for API calls

## Setup Instructions

### Prerequisites
To run this project, you will need:
- **Node.js** and **npm** installed on your local machine.
- **MongoDB** installed locally or use a MongoDB Atlas cloud instance.
- **Git** for version control.
