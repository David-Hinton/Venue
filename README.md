# Locus

## 1. Introduction

Locus is a software application that provides a comprehensive solution for event coordinators to manage and enhance their events. The application focuses on showcasing vendor locations, facilitating vendor management, collecting customer data, enabling event customization, and offering various features for event coordination and management. This document outlines the design and functionality of Locus.

## 2. System Overview

Locus is designed to provide event coordinators with a user-friendly interface to manage and customize event maps. The system incorporates features such as vendor location display, vendor management, rating vendors, live popularity metrics, event customization, real-time updates, special prices for subscribers, event swag point of sale, email collection for customer retention, campaign options, analytics and reporting, vendor sourcing portal, additional services like trash collection, police presence, and ice delivery, vendor compensation portal, property management, permit process, rental of event assets, and sustainability badge linking to vendors.

## 3. Architecture Overview

Locus follows a client-server architecture, with a web-based client interface for event coordinators and a server-side infrastructure to handle data storage and processing. The system employs a combination of frontend and backend technologies to provide a seamless user experience.

### 3.1 Frontend Components

The frontend of Locus is developed using modern web technologies, including HTML5, CSS3, and JavaScript frameworks such as React.js. The user interface is designed to be intuitive, responsive, and visually appealing. Key frontend components include:

- Map Display: The map interface provides a visual representation of the Locus, with the ability to add shapes indicating vendor locations and event assets. Event coordinators can customize the map using an editor tool.

- Vendor Management: The vendor management module allows event coordinators to link and reference vendors' accounts to the map shapes. It also facilitates vendor rating and the association of sustainability badges to vendors.

- User Interface: The user interface includes features for live popularity metrics, campaign options, email collection, and event customization. It provides real-time updates and special prices for subscribers.

### 3.2 Backend Components

The backend of Locus is responsible for data storage, processing, and serving API endpoints. It is built using a server-side framework, such as Node.js, and uses a relational database, such as MySQL or PostgreSQL, to store and manage data. Key backend components include:

- Database: The database stores vendor information, event details, user data, and other relevant information. It facilitates efficient retrieval, update, and management of data.

- API Layer: The API layer exposes endpoints for frontend communication, enabling data exchange between the client and server. These endpoints handle operations related to vendor management, ratings, analytics, vendor sourcing, compensation, and more.

- Authentication and Security: The system incorporates secure authentication mechanisms to ensure authorized access to sensitive data and functionality. It employs encryption and secure communication protocols to protect user and event information.

## 4. Functional Modules

### 4.1 Vendor Management

The Vendor Management module enables event coordinators to add shapes to the map, representing vendor locations, and link these shapes to the respective vendor accounts. It also provides functionality for vendor rating and linking sustainability badges to vendors.

### 4.2 Event Customization

Event Customization allows event coordinators to modify the map, add event assets, and define special prices for subscribers. It offers an intuitive editor tool that facilitates real-time updates and customization options to create a unique event experience.

### 4.3 Analytics and Reporting

The Analytics and Reporting module provides comprehensive insights and reporting capabilities for event coordinators. It generates reports on vendor performance, customer engagement, event metrics, and sustainability efforts. These reports assist in making data-driven decisions and optimizing future events.

### 4.4 Vendor Compensation and Management

The Vendor Compensation and Management module offers a portal for event coordinators to manage vendor payments and track compensation. It ensures seamless financial transactions and simplifies the vendor management process.

### 4.5 Additional Services and Property Management

Locus integrates additional services such as trash collection, police presence, and ice delivery. It also includes property management features for managing permits, rental of event assets, and facilitating a smooth event experience.

## 5. Conclusion

Locus provides a comprehensive software solution for event coordinators to manage and enhance their events. With features such as vendor management, event customization, analytics and reporting, vendor compensation, additional services, and property management, the application aims to streamline event coordination and create memorable experiences for attendees.