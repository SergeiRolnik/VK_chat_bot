VKinder social chat bot

This bot allows you to find potential partners on VK social network matching your profile based on your gender, age, and city. 

Details:

    • You can control the bot by entering appropriate text commands or screen buttons
    • The bot lets you add selected partners to favorites and view their information later
    • To start the bot go to https://vk.com/club213011151 and enter any message

Before using the application:

    • Create a database on your PostgreSQL server
    • Update config.py file with the database info and other parameters
    • Run create_db.py file to create the necessary tables in the database

On the first launch you will be asked to create your personal token to be authorized in the application. The token can be obtained by following instructions on this page:
https://dev.vk.com/api/access-token/implicit-flow-user

The database diagram is provided below:

![image](https://user-images.githubusercontent.com/97103181/168756902-740bfacf-b69e-4d3f-895d-88d2a737990f.png)

