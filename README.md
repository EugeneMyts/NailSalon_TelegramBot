Nail Salon Telegram Bot
This project is a Telegram bot developed using the Spring Boot framework in Java. The bot is designed to provide various features and functionalities for a nail salon, including appointment scheduling, price list display, salon information, and more.

Features
The Nail Salon Telegram bot offers the following features:

Appointment Scheduling: Users can conveniently schedule appointments for nail services through the bot. The bot provides an interactive interface to select preferred dates and times, allowing users to book appointments seamlessly.

Price List Display: The bot includes a comprehensive price list that showcases the different nail services offered by the salon. Users can easily access this information to make informed decisions.

Salon Information: Users can retrieve detailed information about the nail salon, such as its location, working hours, contact details, and any additional information the salon wishes to provide.

Photo Gallery: The bot offers a photo gallery feature that enables users to view images of various nail designs, allowing them to gain inspiration and choose their desired styles.

Salon Owner Access: A separate access level is implemented specifically for salon owners. This access grants salon owners the ability to manage appointments, view the appointment schedule, and make any necessary adjustments.

Installation
To run the Nail Salon Telegram bot locally, follow these steps:

Clone the repository: git clone https://github.com/EugeneMyts/NailSalon_TelegramBot.git

Install the required dependencies using Maven: cd NailSalon_TelegramBot
mvn install

Configure the bot token:

Obtain a Telegram Bot API token by creating a new bot using the BotFather on Telegram.

Replace the placeholder value for the telegram.bot.token property in the application.properties file with your obtained bot token: telegram.bot.token=YOUR_BOT_TOKEN

Build and run the project: mvn spring-boot:run

Usage
To start using the Nail Salon Telegram bot, follow these steps:

Open the Telegram app and search for the bot using its username or the provided link.

Start a conversation with the bot by sending a message or using the "/start" command.

The bot will guide you through its available features and provide interactive menus for different actions, such as scheduling appointments, viewing the price list, accessing salon information, and browsing the photo gallery.

Depending on the access level, salon owners will have additional options for managing appointments and viewing the appointment schedule.

Contributing
Contributions to the Nail Salon Telegram bot project are welcome! If you would like to contribute, please follow these guidelines:

Fork the repository and create a new branch for your feature or bug fix.

Commit your changes with descriptive commit messages.

Push your branch to your forked repository.

Submit a pull request to the main repository, explaining the purpose and changes of your contribution.

Please ensure that your code adheres to the existing coding style and conventions used in the project. Additionally, write unit tests for new features or modifications to maintain code quality and stability.

License
This project is licensed under the MIT License. Feel free to modify and distribute the code according to the terms of this license.

Contact
If you have any questions or suggestions regarding the Nail Salon Telegram bot project, please feel free to reach out to me.


