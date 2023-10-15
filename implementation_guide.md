# System Setup Instructions for MySQL Data Dump and Node-RED Dashboard

Welcome to the System Setup Guide for the MySQL Data Dump and Node-RED Dashboard, created by WGU Hackathon students for the Leo Project. This guide will walk you through the process of setting up both components of your water management system.

## Getting Started

### Downloading and Installing Node-RED

1. To begin, you need to download and install Node-RED, which is the core platform for your water management system.

   - Visit the official Node-RED website: [https://nodered.org/](https://nodered.org/)
   - Follow the installation instructions provided for your operating system.

### Accessing Node-RED

1. Open a web browser and enter the URL to access Node-RED.

### Installing Necessary Nodes

1. To extend the system's capabilities, you'll need to install specific nodes. The required nodes for your system include:

   - node-red-contrib-groov-io
   - node-red-contrib-aws-iot-hub (Future AWS implementation)
   - node-red-dashboard
   - node-red-node-openweathermap
   - node-red-node-mysql-test
   - node-red-node-mysql
   - node-red-contrib-weatherflow-api-client
   - node-red-node-ui-table

2. Follow these steps to install the nodes:
   - Click on the menu icon (three horizontal lines) in the top-right corner of the Node-RED editor.
   - Select "Manage palette."
   - Go to the "Install" tab.
   - Search for each node by name and click "Install" next to each one.

   If these nodes are not already installed, please ensure you install them following the steps provided.

## MySQL Data Dump Setup

### Importing Data

1. Your team has already provided a MySQL database dump file containing essential data.
2. Follow these steps to upload the data dump file to Node-RED:
   - Log in to Node-RED.
   - Click on the menu icon (three horizontal lines) in the top-right corner of the Node-RED editor.
   - Select "Import."
   - Choose the provided MySQL dump file and import it.

## Node-RED Dashboard Setup

### Accessing the Dashboard

1. Once you're logged in to Node-RED, you'll see the Node-RED workspace.
2. Click on the "Dashboard" tab or link to access the dashboard that has been set up for you.

### Dashboard Widgets

1. The dashboard displays various widgets, including charts, gauges, and buttons, designed to help you monitor and control your water management system.
2. Interact with these widgets to view data and perform actions as needed.

## Conclusion

You have now completed the system setup for both the MySQL data dump and the Node-RED Dashboard, created by WGU Hackathon students for the Leo Project. You're ready to use the Node-RED Dashboard for monitoring and controlling your water management system, utilizing the data provided through the MySQL dump. Should you have any questions or require assistance, please don't hesitate to reach out to your team.

Enjoy using the dashboard!
