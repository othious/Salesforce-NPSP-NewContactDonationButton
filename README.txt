# Salesforce-NPSP-NewContactDonationButton
This package creates a Lightning component that you can add to your Contact and/or Account record detail pages to replace the functionality that was available in the Classic interface to add a donation directly from the Contact or Account record detail pages.

YOU MUST COMPLETE THE FOLLOWING STEPS TO HAVE THE BUTTONS VISIBLE ON THE CONTACT AND ACCOUNT PAGES.
After installing this package you must manually add the buttons to the page layouts that you want to use these buttons on.

Adding the button to the Contact page layout:
1. Find the appropriate Page Layout for the Contact object
2. Drag the New Contact Donation button into the Salesforce Lightning and Mobile Actions section of the layout.  Be sure to grab the one that has the internal name of Lightning_New_Contact_Donation which you can see by hovering over the label prior to dragging it onto the page.
3. Save the page layout.
4. Repeat for any other Contact page layouts that should have this button.

Adding the button to the Account page layout:
1. Find the appropriate Page Layout for the Account object
2. Drag the New Account Donation button into the Salesforce Lightning and Mobile Actions section of the layout.  Be sure to grab the one that has the internal name of Lightning_New_Account_Donation which you can see by hovering over the label prior to dragging it onto the page.
3. Save the page layout.
4. Repeat for any other Account page layouts that should have this button.
