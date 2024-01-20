# Set up recurring payments for a single course

Tihs plugin, is a moodle payment gateway that provides support for recurring payments made manually that need to be approved by a person.
This plugin is based on the paygw_bank  developed by UNESCO-IESALC for their campus moodle platform. https://campus.iesalc.unesco.org/


## Instalation.

This plugin is tested in moodle on 4.0.2.

## TODO: Add instructions. 

## TODO: Add Global Configuration.

## TODO: Add future work
Add UPI payments 

## TODO: I LEFT THE REST OF THE ORIGINAL TO REMEMBER WHAT TO UPDATE
Just like another plugin, you can install from the Moodle plugins directory.   https://moodle.org/plugins/paygw_bank
You can also download the zip in the releases section and install directly in "Site administration ">Plugins >"Install plugins"

## Global configuration.

The plugin has the following configurations in the plugin section:
- Allow user add files. The user can (or must, depending of the instructions), upload files that proves the payment.
- Surcharge. The surcharge is an additional percentage charged to users who choose to pay using this payment gateway.
- Send confirmation email. An email is sent to user if the payment is approved.
- Send denied email An email is sent to user if the payment is denied.

The mail texts are in the language strings of the plugin.


## Add this payment gateway to your courses.

Just as all the payment gateways , add the bank transference to a payment account.  Yoy must configure the instructions shown to the user in de payment process, acording to your process.

## Management of payment request .

"Site administration ">"Bank transference" >"Manage transfer" you can see the list of pending payments, and access to the files attached if the option is enabled.  Yoy can deny or approve the payments. If you approve  the payment, automatically the element purchased is served (f.e it the user buy an enrollment to a course,the enrollment is created)

