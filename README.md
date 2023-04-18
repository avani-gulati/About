
# IE 555 Project Proposal

## Team Members:  
- **Avani Gulati**, **UB Email Address 1** - This is the person who will submit the proposal
- **Manohar Golleru**, **UB Email Address 2**
- **Shivani Tirumalasetti**, **UB Email Address 3**
- **Dinakar Inavolu**, **UB Email Address 4**

---

## Title: Real time crypto trends dashboard

Our project aims to create a real-time crypto trends dashboard that utilizes the latest technology to provide users with up-to-date information on different cryptocurrencies. We will be using Plotly Dash, a powerful data visualization library, to create various interactive visualizations such as candlestick plots and line graphs. Our dashboard will be an interactive HTML webpage that users can access from anywhere. We will use **bitstamp.net** as a data sources to collect and analyze data from various cryptocurrency exchanges to ensure that our dashboard provides accurate and reliable data.

--- 

## Project Type

### Online Data Analysis
> Students may develop their own programming project. In this option, students must identify a source of online data, which will be dynamically imported via Python. The Python code must utilize these data to either make decision support recommendations or provide a detailed analysis of the data. A YouTube video describing the mechanics of the Python code will be required, in addition to a “how-to” guide for running the code. All source code must be submitted, and the course instructor must be able to execute the code without errors.

#### Data Sources
We will use **bitstamp.net** as a data sources to collect and analyze data from various cryptocurrency exchanges to ensure that our dashboard provides accurate and reliable data
    - *https://www.bitstamp.net/api-deprecated/*

#### Analysis Plan

**Steps involved:**
- 1.Import the data from bitstamp.net via GET and turn it into a Panda dataframe
- 2.Change the time stamp to Date and Time to use it for visualization and also for the interactive time step for the trends
- 3.Creating a HTML webpage to display the visualizations
- 4.Integrate the Plotly Dash library to create the visualizations
- 5.Adding controls such as dropdown and scrollbar to allow users to make changes to the type of cryptocurrency or the time step used to display the plots
- 6.Making the interface more user friendly

**Why this data source?**
The chosen data source, bitstamp.net, will enable us to conduct this analysis by providing real-time data on different cryptocurrencies. The data provided by bitstamp.net is reliable and accurate, and it covers a broad range of cryptocurrencies. It provides data in real time for various crypto currencies with time stamp,closing price,high,low,volume these data values are very crucial for this project and would enable us to perform all the analysis we wanted to.Overall, the chosen source data is well-suited for the analysis plan outlined in the project description

#### Motivation
As avid crypto traders, we understand the difficulties traders face in finding suitable visualizations for real-time cryptocurrency data. This project aims to address that challenge by creating an easy-to-use, interactive tool that provides traders with insightful visualizations of market trends and patterns. By leveraging real-time data, our project will provide traders with the most up-to-date information, helping them make more informed trading decisions. Ultimately, this project aims to contribute to the rapidly growing field of cryptocurrency trading and help traders navigate this complex and dynamic market
