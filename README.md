# E-Commerce Back End

## Description

This is a back-end for an e-commerce site that uses an Express.js API using Sequelize to interact with a MySQL database.

## Table of Contents

* [Installation](#installation)

* [Usage](#usage)

* [License](#license)

* [Contributing](#contributing)

* [Tests](#tests)

* [Credits](#credits)

* [Questions](#questions)

## Installation

To install necessary dependencies, run the following command:

```bash
npm i
```

## Usage

Follow [this](https://drive.google.com/file/d/1g2jwuqUNou2BXiC9un6Q9h9cBARsOnoH/view) link for a walkthrough video on how to start and run this back-end application.

NOTE: Before running anything, make sure to rename the '.env.EXAMPLE' file to '.env' and entering your username and password in the blank fields inside that file. 

To create the schema through the MySQL shell, go to your terminal, make sure you are in the root directory, and run:

```bash
mysql -u root -p
```

and then enter your password when prompted. Then, run:

```bash
source db/schema.sql;
```

and then:

```bash
exit;
```

in order to exit the MySQL shell. To seed the database, run:

```bash
npm run seed
```

And finally, to start the app, run:

```bash
node server.js
```

You can then use apps like Insomnia to get, create, update, and delete items in the database.

## License

N/A

## Contributing

Feel free to contribute!

## Tests

You can use apps like Insomnia to test the different routes. See the walkthrough video in the Usage section for an example.

## Credits

N/A

## Questions

If you have any questions about the repo, open an issue or contact me directly at jbriseno2000@gmail.com. You can find more of my work at [jb6131](https://github.com/jb6131/).