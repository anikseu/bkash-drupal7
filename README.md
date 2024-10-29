# bKash Payment Gateway for Drupal 7 Commerce

This is a **Custom Payment Gateway Module** for Drupal 7 Commerce, built to support [bKash](https://www.bkash.com) payment integration. This module allows seamless integration of the bKash payment gateway for eCommerce sites using Drupal 7 Commerce.

## Features

- Supports bKash payments within Drupal Commerce.
- Handles offsite payments with automatic redirection.
- Receives and processes IPN (Instant Payment Notification) callbacks.

## Requirements

- **Drupal 7** with **Commerce Module** installed and configured.
- **bKash Merchant Account** for payment processing.

## Installation

1. **Download the Module**:  
   Clone this repository or download it to your `sites/all/modules/custom` directory:

   ```bash
   git clone https://github.com/anikseu/bkash-drupal7.git
   ```

2. **Enable the Module**:  
   Go to `Modules` in your Drupal admin panel and enable the **Custom Payment Gateway** module.

3. **Configure the Payment Gateway**:  
   - Navigate to `Store > Configuration > Payment Methods`.
   - Add **Custom Payment (bKash)** as a new payment method.
   - Enter your bKash API credentials in the provided fields.

## Usage

Once configured, the bKash payment option will be available for users during checkout. The module will redirect users to bKash’s site for payment, and they will be redirected back upon completion.

## Customization

If you need to extend the functionality:
- **IPN Endpoint**: The IPN endpoint at `/commerce_bkash/ipn` can be customized for additional processing.
- **Settings Form**: Customize form fields or validation within the module file to add any specific configurations.

## Contributing

We welcome contributions! Please open an issue or submit a pull request if you find bugs or want to add new features.

## License

This module is open-source and available under the MIT License. See the `LICENSE` file for more details.

## Support

If you encounter issues, please create an issue on GitHub. We’ll do our best to address it.

---
