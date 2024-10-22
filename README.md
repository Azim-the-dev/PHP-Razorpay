# PHP Integration with Razorpay

This demo showcases the integration of Razorpay's payment gateway with a PHP application.

## Installation Steps

### Step 1: Clone this Repository

Use the following command to clone this repository:

```bash
git clone https://github.com/Azim-the-dev/PHP-Razorpay.git
```

### Step 2: Clone the Razorpay PHP Library

Clone the Razorpay PHP library using the command below:

```bash
git clone https://github.com/razorpay/razorpay-php
```

### Step 3: Configure API Keys

Edit the `config.php`, `verify.php` and `index.php` files to include your Razorpay API Key ID and Secret.

## File Descriptions

1. **index.php**: This file contains the Orders API and the checkout code.
   
2. **config.php**: This file holds essential configuration details, including your API Key ID and Secret.
   
3. **verify.php**: This file contains the logic for verifying payment signatures.
   
4. **success.html**: A page that users are redirected to upon successful payment.

For more details, refer to the official Razorpay documentation: [Razorpay PHP Integration Docs](https://razorpay.com/docs/payments/server-integration/php/payment-gateway/).

You can also access the Razorpay PHP library on GitHub: [Razorpay PHP Library](https://github.com/razorpay/razorpay-php).
