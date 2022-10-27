![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello, world! Back-end

> This API-only app displays a random greeting message. It is considered the back-end.

## Built With

- Ruby & PostgreSQL
- Ruby on Rails
- Linters (Rubocop & Stylelint)
- Git & GitHub

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

    Ruby 3.1.2
    PostgreSQL 15.0
    Ruby on Rails 7.0.4

### Setup

    git clone git@github.com:jevazquezb/hello_rails_back_end.git
    cd hello_rails_back_end
    

### Install

    1. bundle install
    2. rails db:create
    3. rails db:migrate

### Feed

**Note:** Repeat step 5 to add several messages to the API (change the message).

    4. rails c
    5. Greeting.create(message: 'Hello, world!')
    6. exit

### Usage

    rails s -p 3001

Go to [http://localhost:3001/api/v1/greetings](http://localhost:3001/api/v1/greetings) and make sure the messages are visible. Refresh the page to see the different messages.

### React Front-end

Go to [https://github.com/jevazquezb/hello_react_front_end](https://github.com/jevazquezb/hello_react_front_end).

### Done!

Ready to work?⛏️ You're all set to explore and change the repo locally (on your computer).

## Author

👤 **Jesús Vázquez**

- GitHub: [@jevazquezb](https://github.com/jevazquezb)
- Twitter: [@javb_1187](https://twitter.com/javb_1187)
- LinkedIn: [@jevazquezb](https://www.linkedin.com/in/jevazquezb)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used.
- My fellow Micronauts.
- Google and Stack Overflow.
- Inspiration.
- etc.

## 📝 License

This project is [MIT](./MIT.md) licensed.
