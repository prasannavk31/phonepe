{"nbformat":4,"nbformat_minor":0,"metadata":{"colab":{"provenance":[],"authorship_tag":"ABX9TyN+GARyvYZnhcBJ77nRlgqG"},"kernelspec":{"name":"python3","display_name":"Python 3"},"language_info":{"name":"python"}},"cells":[{"cell_type":"markdown","source":["#Phonepe-Pulse-Data-Visualization-and-**Exploration**"],"metadata":{"id":"xxOytLO9aiTe"}},{"cell_type":"markdown","source":["# Problem Statement: "],"metadata":{"id":"413WCHNhaoo3"}},{"cell_type":"markdown","source":["The Phonepe pulse Github repository contains a large amount of data related to various metrics and statistics. The goal is to extract this data and process it to obtain insights and information that can be visualized in a user-friendly manner."],"metadata":{"id":"s5duArGma0va"}},{"cell_type":"markdown","source":["# Approach:"],"metadata":{"id":"cUx7VwrCa9wh"}},{"cell_type":"markdown","source":["\n","\n","*   Data extraction: Cloning the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as CSV or JSON.\n","*   Data transformation: Using a scripting language such as Python, along with libraries such as Pandas, to manipulate and pre-process the data. This may include cleaning the data, handling missing values, and transforming the data into a format suitable for analysis and visualization.\n","*   Database insertion: Use the \"mysql-connector-python\" library in Python to connect to a MySQL database and insert the transformed data using SQL commands.\n","*  Dashboard creation: Using the Streamlit and Plotly libraries in Python to create an interactive and visually appealing dashboard. Plotly's built-in geo map functions can be used to display the data on a map and Streamlit can be used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.\n","*   Data retrieval: Using the \"mysql-connector-python\" library to connect to the MySQL database and fetch the data into a Pandas dataframe and Using the data in the dataframe to update the dashboard dynamically.\n","\n","\n","\n","\n","\n"],"metadata":{"id":"YDM6HkL_bF_N"}},{"cell_type":"markdown","source":["# Packages:"],"metadata":{"id":"qXutPab9bl22"}},{"cell_type":"markdown","source":["* streamlit\n","* pandas\n","* streamlit_lottie\n","* mysql-connector-python\n","* plotly-express\n","* geopandas\n","* streamlit-option-menu"],"metadata":{"id":"4frhCCBvbsjG"}},{"cell_type":"markdown","source":["# Data"],"metadata":{"id":"9fC1flwEbxz7"}},{"cell_type":"markdown","source":["The data was cloned from https://github.com/PhonePe/pulse.git"],"metadata":{"id":"TkFGgGNTb_8M"}}]}