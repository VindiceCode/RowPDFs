## Overview

PDF Data Extractor for Monday.com

Streamline your document processing with our intelligent PDF Data Extractor. This app allows you to easily upload PDF documents and automatically extract key data points, transforming them into structured rows in your Monday.com boards.

Key features:

•	Drag-and-drop PDF upload
•	AI-powered data extraction and organization
•	Automatic creation of new rows based on PDF content
•	Intelligent mapping of data to existing board structure
•	Seamless integration with Monday.com's Main Table view

Perfect for businesses dealing with invoices, reports, or any standardized PDF documents. Save time, reduce errors, and keep your projects up-to-date effortlessly.




Developing locally
Some of the examples in this repository require you to run a local server and expose it to the internet. To do so, you can either:

Use a tunneling service such as ngrok or localtunnel
Or utilize the monday apps CLI tool, which supports local development and tunneling out of the box. To do that, you will need to install node on your machine and then run the following:
npm i -g @mondaycom/apps-cli
mapps init -t <your-personal-token> (see here: https://developer.monday.com/apps/docs/quickstart-guide-for-monday-code#command-line-interface)
mapps tunnel:create inside the example directory you want to run