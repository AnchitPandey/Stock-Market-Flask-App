# Stock-Market-Flask-App
My curriculum project in which I use Flask as backend to display stock details, charts and latest news of the company input by the user. This was a basic project to be done with a static web page (no Bootstrap). The main concept I utilized is sending GET request from Flask to external APIs like Tiingo, NewsAPI and HighStock API to display the stock details
of the organization.

## Different Views

### 1. Main Screen
This is the start screen of the app. The user can enter the ticker symbol and click on search. If the ticker is found, then details of the ticker are displayed else a message is shown saying the ticker was not found. Pressing the clear button will clear the data on the screen. This is shown in 2 figures below:

![start-screen](https://user-images.githubusercontent.com/40236708/108418307-e77b5080-71e5-11eb-95cc-3c107e0c36f1.JPG)
![invalid-page](https://user-images.githubusercontent.com/40236708/108418305-e6e2ba00-71e5-11eb-8545-9136c4cf1311.JPG)


### 2. Details View
Once the user clicks on Search Button, I send a GET request to APIs like Tiingo, News API and HighStock to fetch the data for that company. A navbar is shown which describes the different details of the company user queried. The figures below show the different details of the company.




