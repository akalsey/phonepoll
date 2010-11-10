phonepoll
=========

This is a Drupal module that provides phone access to Drupal polls. Using this module and [Tropo](http://tropo.com/) people can vote in polls via calls or SMS.

This is an early release. Setup is a little manual right now, but will improve shortly.

Setup
-----

Copy this directory to your prefered module directory. If you don't have a prefered location, sites/all/modules is always a good choice. Enable this module in admin/build/modules

Create a poll. Note the node ID of the poll. You'll need that for the next step.

Create a Tropo account at http://tropo.com/ and create a WebAPI application. For the URL of your application, enter http://yoursite.example.com/phonepoll/poll/NODE-ID (replacing NODE-ID with the node ID of your poll)

Add a phone number -- Tropo has numbers throughout the US and in 41 countries.

Call or SMS your new number and vote.

Planned enhancements
--------------------

Panned enhancements include...

* customization of the dialog
* allowing the poll creator to fire off a SMS or voice message to all voters with the result
* One-click setup of the Tropo app