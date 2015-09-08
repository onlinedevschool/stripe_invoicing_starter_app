# Invoicing App

> Ruby on Rails, Postgres, Bootstrap, Stripe and a touch of Javascript!

Being able to invoice a customer/client/vendor simply is a need every code slinger has, even if they have a full time job. So we will build a Rails application and integrate it with Stripe, and even make it look 'polished' by integrating Bootstrap. It will even send emails when invoices are created and also again when you are paid.

## Table of Contents

1. Generating and 'Bootstrapping' a Rails app
  1. Generating the Rails app
  2. Keeping away the clutter
  3. Fixing Turbolinks
  4. Bootstrap and Bootstrap forms
  5. A layout and some basic css

2. Logins and accounts for Inoicers
  1. Installing the Devise gem
  2. Creating an Invoicer model
  3. No registrations, only seeds

3. Integrating Stripe for payments
  1. Signing up at Stripe.com
  2. Installing the dotenv-rails gem
  3. Adding the test keys to development

4. Modeling out our data layer
  1. The Invoicer model
  2. The Invoice model
  3. The Payee model

5. The Payees Controller and Views
  1. The create payee form
  2. Creating the new payee
  3. Showing the payee details
  4. Showing a list of payees

6. The Invoices Controller and Views
  1. The create invoice form
  2. Creating the new invoice
  2. Showing a list of invoices
  3. Showing a single invoice

7. The Payment Controller and Views
  1. The new payment form
  2. Processing the payment
  3. Creating the new payment

8. Generating and seding the emails
  1. SendGrid and Letter Opener gems
  2. Invoice notifications
  3. Payment notifications



