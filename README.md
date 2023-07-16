# RealTimeMessagingPyspark
Real-time message processing system for children's messages using Python, Pyspark, and NLP techniques.

## Description
This project aims to develop a system to process children's messages in real-time. Python and PySpark are used for data extraction and processing, and several NLP techniques are employed to identify if a child is asking for help.

## Project Structure
The project is divided into two main parts: Scrapper and Server.

## Scrapper
The Scrapper is responsible for extracting messages from the web page www.everyonesinvited.uk. Python, Selenium, and Beautiful Soup are used for this purpose. The extracted messages are saved in a CSV file for further processing.

For more details about the Scrapper, refer to the notebook Scrapper.ipynb.

## Server
The Server is responsible for receiving and processing the messages in real-time. It uses Spark Streaming, an extension of the core Spark API, to receive and process the data. During processing, the server uses Sentiment Vader for sentiment analysis, keyword detection for identifying important themes, and unsupervised Natural Language Processing (NLP) techniques to extract meaningful insights from the messages.

For more details about the Server, refer to the notebook Server.ipynb.
