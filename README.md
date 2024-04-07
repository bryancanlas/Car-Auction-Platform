# Car Auction Platform

Welcome to the Car Auction Platform, a web application designed to facilitate car auctions. Whether you're an enthusiast looking for your dream car or a seller seeking a platform to showcase your vehicles, this app provides a seamless experience for both buyers and sellers alike.

## Features

- **User Registration and Authentication**: Users can register with their full name, email address, and phone number. Registered users can log in to access the platform's features.

- **Auction Listings**: Users can view a list of all available auctions. Each listing displays details such as the car brand, year, type, opening price, and expiry date.

- **Creating New Auctions**: Registered users can create new auctions by providing details about the car, including brand, year, type, opening price, price increment, and expiry date.

- **Bidding on Auctions**: Users can place bids on open auctions. Bidders cannot bid on their own auctions, and bid prices are incremented based on the previous bid.

- **Admin Functionality**: Admin users have the authority to close or delete listings.

## Requirements

- Ruby Version: 3.2.2 (Ensure you have the correct version of Ruby installed)

- Ruby on Rails Version: 7.0.6

- For installation instructions, refer to [Ruby and ROR Installation Guide](https://gorails.com/setup/ubuntu/22.04) for Ubuntu, Mac, and Windows.

## How to Run the Project

Follow the steps below to set up and run the application locally:

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/bryancanlas/Car-Auction-Platform.git
2. Navigate to the project directory and install dependencies::

   ```bash
   cd Car-Auction-Platform

   bundle install
3. Set up Database:
   - Create a `.env` file inside the project directory and set up environment variables for MySQL credentials:
        ```
        DB_USERNAME = your_db_username

        DB_PASSWORD = your_db_pasword
        ```
   - Ensure MySQL is installed on your machine.

   - Run Active Record commands:        
        ```
        rails db:create

        rails db:migrate

        rails db:seed
        ```
4. Run the Application locally:

   ```bash
   ./bin/dev
5. Visit http://localhost:3000 in your web browser to access the application.

### Sample Accounts

**Admin**

```
email: admin@dev.com
password: Password1!
```
**Regular users**

```
email: jdcruz@dev.com
password: Password1!
```

```
email: mmakiling@dev.com
password: Password1!
```
## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


### Thank you for your consideration!