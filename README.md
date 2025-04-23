# Abduldata Application

Abduldata Application is a data management web application designed to provide users with various features such as:

- **Sign Up / Login**
- **SMS Verification** via Twilio for user authentication
- **Paystack Integration** for payments
- **Complaints & History** for users to track interactions

## Features

- **User Authentication**: Users must register and log in before accessing the dashboard.
- **SMS Verification**: Users are verified via SMS using Twilio's SMS service.
- **Paystack Payment Integration**: Seamlessly buy airtime, data, cable TV subscriptions, and pay electricity bills.
- **Complaints & History**: Users can file complaints and view their transaction history.
- **Responsive Design**: Fully responsive and mobile-friendly UI built using Tailwind CSS.

## Tech Stack

- **Frontend**: HTML, Tailwind CSS, JavaScript
- **Backend**: Node.js (for SMS verification and Paystack integration)
- **Payment Integration**: Paystack (for payments)
- **SMS Verification**: Twilio (Twilio Verify API)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/abdooldata-app/abdool-data-application.git
   cd abdool-data-application

2. Install dependencies (for backend setup):

npm install


3. Create a .env file and add your Twilio and Paystack keys:

TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_VERIFY_SID=your_verify_sid
PAYSTACK_SECRET_KEY=your_paystack_secret_key


4. Start the app:

npm start


5. Open your browser and visit http://localhost:3000.



Contributions

Feel free to fork the project, make improvements, and submit pull requests. If you encounter any issues or have feature requests, please open an issue in the GitHub repository.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For any questions, please contact us at auh439@gmail.com.
