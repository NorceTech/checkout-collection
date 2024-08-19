# Norce Checkout Collection
Collection of request to get started with Norce Checkout.

The Playground environment needs to be filled out quite extensively with information you will have received from Norce.

If you've previously worked in Norce Commerce you'll already have the following: 

`slug`, aka "playground-partner-name" in some documentation.
Commerce Identity Client Id `commerceIdentityClientId` and Secret `commerceIdentityClientSecret` is your personal access to the APIs. 
`commerceClientId` and `commerceApplicationId` is simply your client and appplication id for your setup.

Specific for Norce Checkout is
`merchant`, will most likely be the same as your `slug`. 
`token` is the Norce Checkout access token, primary or secondary, received from your contact at Norce.

For tests using the Klarna Checkout Adapter you'll need to provide klarna username and password. 

Basic basket requests still require some manual touches. A `PartNo` that represents a product that exists, as well as a `PriceListId` that works with that product.

There is some setup required for your Norce Commerce client. You need to have Payment Method 239 (Norce Checkout) and Deliver Method 128 (External Provider) configured.

## Download Bruno
You can download Bruno here:
https://www.usebruno.com/downloads