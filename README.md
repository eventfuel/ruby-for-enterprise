# Ruby for Enterprise
A collection of Ruby gems and alternatives that you can use to check the boxes for enterprise deployment. This was inspired by the [enterpriseready.io](enterpriseready.io) site and we wanted to outline all the tools we use to tick those boxes for our primary Ruby application.

## [Product Assortment](https://www.enterpriseready.io/features/product-assortment/)
This one is mainly on the product design side of things and how your offering is divided up. If that is by features, use the gems for access control and roles to define higher level access to particular features.

## [Single Sign On](https://www.enterpriseready.io/features/single-sign-on/)
Single sign on for enterprise is always going to be tricky if you are operating on the cloud and their directory is behind a firewall. You can DIY with things like ruby-saml and get their IT department to punch a hole in the firewall after doing extensive review of your entire codebase, probably not the easiest route.

Another option is to use identity providers (IDPs) to do that work for your.

One of the most modern in 2017 is [Okta](https://www.okta.com/). They are a startup that recently IPOed and have a large chunk of the Fortune 500 are already using the platform at least for some of their cloud tools. Riding this wave of cloud identity services is a good way of ticking that 

Using a solution like [omniauth](https://github.com/omniauth/omniauth) and [omniauth-okta](https://github.com/dandrews/omniauth-okta) is a fast way to make sure that all users from a particular organization are being authorised through an identity platform.

## [Audit Logs](https://www.enterpriseready.io/features/audit-log)
Paper trail
