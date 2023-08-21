# DS_Phonepe-Pulse-Data-Visualization-and-Exploration

![phonepe](https://github.com/Clintonnick3/DS_Phonepe-Pulse-Data-Visualization-and-Exploration/assets/129974527/9297259e-523a-4a56-ab59-ce94994a437c)

The PhonePe Data Visualization API is a powerful tool that allows developers to integrate interactive visualizations into their applications. This API provides an efficient way to display data in various formats, such as charts, graphs, and maps, enhancing the user experience and making data analysis more accessible.


# PhonePe Pulse :

# About :
PhonePe Pulse is a window into the world of how India transacts, with interesting trends, deep insights, and in-depth analysis based on data put together by the PhonePe team. It provides definitive data sources on digital payments in India, and covers topics such as how consumers are using digital payments, what the top use cases are, and whether kiranas across Tier 2 and 3 are getting a facelift with the penetration of QR codes.

# About API :
The PhonePe Data Visualization API is a powerful tool that allows developers to integrate interactive visualizations into their applications, enabling users to explore and understand transaction and user data. This API provides comprehensive features to analyze data at the state and district levels, including transaction totals, average transactions, high potential states and districts, and popular transaction instruments. Users can also extract information about the mobile devices used to access the app. Additionally, users can leverage the API to generate Plotly GeoJSON maps of Indian states, and easily interpret the distribution of data.

# Data :

The data used in PhonePe Pulse is available in this link [PhonePe Pulse](https://github.com/PhonePe/pulse#readme). The data is divided into different categories, such as transaction data, user data,. The data is stored in JSON format. A complete description of the data is provided in the link above, before proceeding to data visualization or data processing, kindly understand the data completely.

# Features :
* Transaction Data Visualization: Display transaction data in interactive charts, graphs, and maps, allowing users to analyze transaction totals, average transactions, and identify high potential states and districts.
* User Data Visualization: Visualize user data to gain insights into popular transaction instruments and the mobile devices used to access the app.
* State and District-Level Analysis: Drill down into data at the state and district levels to understand regional trends and identify key areas for business growth.
* Plotly GeoJSON Maps: Generate dynamic maps of Indian states using Plotly GeoJSON, allowing users to visualize data geographically.

# Requirements :
* Python
* MySQL
* Streamlit
* Github Cloning
* Geo Visualization
* Dynamic Updation

# Approach :
* Data Extraction: The data is obtained from the Phonepe pulse Github repository using scripting techniques and cloned for further processing.
* Data Transformation: The extracted data is formatted into a suitable structure, ensuring it is clean and ready for analysis. Pre-processing tasks may be performed as necessary.
* Database Integration: The transformed data is inserted into a MySQL database, offering efficient storage and retrieval capabilities.
* Live Geo Visualization Dashboard: Python's Streamlit and Plotly libraries are utilized to create an interactive and visually appealing dashboard. This dashboard presents the data in real-time, enabling users to explore the insights effectively.
* Database Integration with the Dashboard: The relevant data is fetched from the MySQL database and seamlessly integrated into the dashboard, ensuring the displayed information is up-to-date and accurate.
* User-Selectable Dropdown Options: The dashboard incorporates a minimum of 10 distinct dropdown options, providing users with the ability to select and view various facts and figures of interest. This feature enhances the customization and flexibility of the dashboard.
