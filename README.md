# Youtube_Project #

**Introduction**

This project creates a Streamlit application that allows users to access and analyze data from multiple YouTube channels. The project utilizes SQL, MongoDB, and Streamlit to create a user-friendly application that allows users to retrieve, store, and query YouTube channel and video data.

**Project Overview**

The Youtube_project consists of the following components:
- Streamlit Application: A user-friendly UI built using Streamlit library, allowing users to interact with the application and perform data retrieval and analysis tasks.
- YouTube API Integration: Integration with the YouTube API to fetch channel and video data based on the provided channel ID.
- MongoDB Data Lake: Storage of the retrieved data in a MongoDB database, providing a flexible and scalable solution for storing unstructured and semi-structured data.
- SQL Data Warehouse: Migration of data from the data lake to a SQL database, allowing for efficient querying and analysis using SQL queries.

**Technologies Used**

The following technologies are used in this project:
- Python: The programming language used for building the application and scripting tasks.
- Streamlit: A Python library used for creating interactive web applications and data visualizations.
- YouTube API: Google API is used to retrieve channel and video data from YouTube.
- MongoDB: A NoSQL database used as a data lake for storing retrieved YouTube data.
- SQL (MySQL): A relational database used as a data warehouse for storing migrated YouTube data.
- PyMySql: A Python library used for SQL database connectivity and interaction.
- PyMongo: A Python library used for MongoDB database connectivity and interaction.
- Pandas: A data manipulation library used for data processing and analysis.
- RegularExpression :RegularExpression is a built-in module in Python that provides support for working with regular expressions, which are powerful tools for pattern matching and text manipulation.
- DateTime :Python Datetime module supplies classes to work with date and time.
- CSS : Cascading Style Sheets is a language used for laying out and structuring web pages.
  
**Installation and Setup**

To run the YouTube Data Harvesting and Warehousing project, follow these steps:
1. Install Python: Install the Python programming language on your machine.
2. Install Required Libraries: Install the necessary Python libraries using pip or conda package manager.
3. Set Up Google API: Set up a Google API project and obtain the necessary API credentials for accessing the YouTube API.
4. Configure Database: Set up a MongoDB database and SQL database (MySQL) for storing the data.
5. Configure Application: Update the configuration file or environment variables with the necessary API credentials and database connection details.
6. Run the Application: Launch the Streamlit application using the command-line interface.

**Usage**

Once the project is setup and running, users can access the Streamlit application through a web browser. The application will provide a user interface where users can perform the following actions:
- Enter a YouTube channel ID to retrieve data for that channel.
- Store the retrieved data in the MongoDB data lake.
- Collect and store data for multiple YouTube channels in the data lake.
- Select a channel and migrate its data from the data lake to the SQL data warehouse.
- Search and retrieve data from the SQL database using various search options.

**Features**

This project offers the following features:
- Retrieval of channel and video data from YouTube using the YouTube API.
- Storage of data in a MongoDB database as a data lake.
- Migration of data from the data lake to a SQL database for efficient querying and analysis.
- Search and retrieval of data from the SQL database using different search options, including joining tables.
- Support for handling multiple YouTube channels and managing their data.

**Conclusion**

The Youtube_Project provides a powerful tool for retrieving, storing, and analyzing YouTube channel and video data. By using SQL, MongoDB, and Streamlit users can easily access and manipulate YouTube data in a user-friendly interface. 

**References**

- Streamlit Documentation: https://streamlit.io/
- YouTube API Documentation: https://developers.google.com/youtube/v3/getting-started
- MongoDB Documentation: https://www.mongodb.com/
- PyMongo Documentation: https://pymongo.readthedocs.io/
- PyMySql Documentation : https://pymysql.readthedocs.io/
- Python Documentation: https://docs.python.org/
- RegularExpression Documentation: https://docs.python.org/3/library/re.html
- Css Documentation : https://www.w3schools.com/css/css_intro.asp
