# Bamazon

A Node/JavaScript-based storefront application.

## Getting Started

Using Node in your terminal/Bash, run your bamazonCustomer.js file. Follow the instructions to purchase items from the Bamazon store.

### Prerequisites

Node, MySQL, Inquirer

### Installing

Download the repository. Run 'npm install' in your repository folder to install all dependencies from the package-lock.json file.

### Use

## Bamazon Transactions

First, cd into the repository in your terminal. Next, run the command 'node bamazonCustomer.js'. This will prompt the MySQL connection
and display the storefront to you with currenty inventory as such:

![Connection/Display](https://raw.githubusercontent.com/JonathanDavis22/Bamazon/master/Images/Screen%20Shot%202019-01-12%20at%209.19.09%20PM.png "Connection/Display")

Next, respond to the question of what you would like to purchase by answering by item name, and how many you would like to purchase
by entering the number, or else enter 'Q' to quit:

![Purchase](https://raw.githubusercontent.com/JonathanDavis22/Bamazon/master/Images/Screen%20Shot%202019-01-12%20at%209.19.44%20PM.png "Purchase")

Finally, as seen here, if you attempt to purchase more items than in inventory, or an item not in inventory, you will be denied and 
told this is not a valid selection. Additionally, as seen in these screenshots, the MySQL database updates in real-time.

![Denial](https://raw.githubusercontent.com/JonathanDavis22/Bamazon/master/Images/Screen%20Shot%202019-01-12%20at%209.20.29%20PM.png "Denial")

## Built With

* [Node](https://nodejs.org/api/http.html) - The JavaScript runtime used
* [MySQL](https://www.mysql.com/) - Used to create realtime database for storefront inventory.
* [Inquirer](https://www.npmjs.com/package/inquirer) - Used to ask questions, parse input, and validate answers.

## Authors

* **Jonathan Davis** - *Completion* - (https://github.com/JonathanDavis22)
