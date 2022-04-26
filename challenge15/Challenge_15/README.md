# Robo Adviser

In this application, I combine my new AWS skills with my existing Python superpowers to create a bot that will recommend an investment portfolio for a retirement plan.

In the first stage of this application, I create the robo adviser bot and add an intent with its corresponding slots.
I name the intent recommmendPortfolio, and configure all of the sample utterences.
Then, I create four slots and mark all of them as required.
I complete the first stage by setting the confirmation prompt.

In the second stage of my application, I build and test the robo adviser.

In the final stage of the application, I enhance the robo adviser with an Amazon Lambda function. I name it recomend_portfolio, and add two validation rules:
The value of age must be greater than zero and less than 65, and the investment amount must be greater or equel to 5000. I complete the function in a way that once the intent is fulfilled, the bot will respond with a custom investment recommendation based on the selected risk level, as follows:

None: “100% bonds (AGG), 0% equities (SPY)”

Low: “60% bonds (AGG), 40% equities (SPY)”

Medium: “40% bonds (AGG), 60% equities (SPY)”

High: “20% bonds (AGG), 80% equities (SPY)”


---

## Technologies

This project leverages Python 3.7.

---

## Installation Guide

Before running this application, Python must be installed.

---

## Usage

Simply launch amazon lex and begin a chat with the bot to get started on investing for your retirement!

---

## Contributors

Just me, and a little bit of help from module 13

## License

No license, feel free to copy the code any time.
