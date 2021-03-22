Adyen Web

Adyen Web provides you with the building blocks to create a checkout experience for your shoppers, allowing them to pay using the payment method of their choice.

You can integrate with Adyen Web in two ways:

Web Drop-in: an all-in-one solution, the quickest way to accept payments on your website.
Web Components: one Component per payment method and combine with your own payments form logic.
Prerequisites
Adyen test account
API key
Client key
Installation
We only provide full support when you use one of these methods of installation.

Node package manager
Install the Adyen Web Node package:

npm install @adyen/adyen-web --save

Import Adyen Web into your application:

import AdyenCheckout from '@adyen/adyen-web';
import '@adyen/adyen-web/dist/adyen.css';

Using a <script> tag
You can also import Adyen Web using a <script> tag, as shown in the Web Components integration guide.

Development
To run the development environment:

Clone this repository.
Create a .env file on your project's root folder following the example in env.default and fill in the environment variables.
Install the dependencies by running:
yarn install
Run the development environment, which starts a server listening on http://localhost:3020:
yarn start
Contributing
We merge every pull request into the master branch. We aim to keep master in good shape, which allows us to release a new version whenever we need to.

Have a look at our contributing guidelines to find out how to raise a pull request.

See also
Why we open sourced Adyen Web
Complete documentation for Adyen Web
API Explorer
Example integrations
Adyen Components JS Sample Code
Support
If you have a feature request, or spotted a bug or a technical problem, create an issue here.

For other questions, contact our support team.

License
This repository is available under the MIT license.
