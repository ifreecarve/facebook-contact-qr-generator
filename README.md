# Facebook Contact QR Generator
This is a GreaseMonkey / TamperMonkey script to generate scannable vCards from Facebook friends' contact info.

It works by reading information off your friends' "About" page, -- assembling that contact information into a vCard and rendering it as a QR code in place of their profile picture.  This allows you to easily import it into your contacts with Google Goggles.

![Example output](https://raw.githubusercontent.com/ifreecarve/facebook-contact-qr-generator/master/doc/facebook-contact-qr-generator-example.jpg)

To my knowledge, this is not in violation of any terms of service; [the best option that I could find](http://techcrunch.com/2010/11/26/the-address-book-wars-continue-facebook-contact-scraping-chrome-extension-taken-down/) had suffered this fate earlier.

## Known issues
* Sometimes you need to refresh the page once for it to work.  I assume this is a URL issue.
* It only triggers if there is at least one phone number present (because otherwise why would you want to scan it into your phone).