# ReactRealState
Layout Recommendation 

The support of our recommendation was, at least during the initial phase of this project this app will contain website navigation and content organization more simple and concise than big player in the Real State market such as Sutton Group and Royal LePage.

Header
On header, we show the main sections of website:

- Logo
- Home;
- Properties for sale;
- Properties for rent;
- About;
- Contact me;
- Newsletters;
- I want to sell my property.

Home
The main feature of this component is to display the main properties available for buy, sale or leasing.

This component does not has complex features, for example **Search Properties by address.** We will display the **featured properties** to users and will be render in cards that contain the following information:

Name;
E-mail;
Phone number;
Type of message:
Booking a visit;
More information;
More information;
I want to sell my property;
Other questions.
Text field to add comments;
Recaptcha;
Send button.

PROPERTIES FOR SALE &  PROPERTIES FOR RENT
In this section we will find all listed properties for sale and/or rent.
Property location;
Property value;
Property size;
Number of bedrooms;
Number of bathrooms.
Right below these filters, we see the properties.

To reduce user's cognitive overload it will be rendered 16 properties (5 rows with 3 cards).
To load more properties the user should click on Show More button.
Each card has the following information:
Carousel displaying pictures of the property;
Type of property:
Apartment;
House;
Condo;
Bachelor.
Address;
Property metrics;
Number of rooms;
Number of bathrooms;
Property value.

PROPERTY'S INTERNAL PAGE
After click on any Property Card, user will be redirected to the internal page. In this section will be render all information about the property (imperial/metric when applicable), such as:
Property photos;
Property location;
Property information, like:
Building in (year);
Property size;
Number of levels;
Number of rooms (by level);
Number of bathrooms (by level);
Kitchen layouts;
Parking;
Basement;
Construction Materials

Property information, like:
Heating
Cooling
Laundry
Office;
Condo fee (if applicable);
Tax fee (if applicable);
Amenities;
Pet friendly.

After these information, similar properties, that might appeal to the user, are shown.
We must define the parameters behind these recommendations, like:
Property value;
Address;
Certain property characteristics, like number of rooms, for example. 

Furthermore, we can define a correlation to display new properties, for example, similar value + number of bedrooms + Location + Size = Recommend a new property.
This section also has a float form that allows the user to fill it and show interest about the property.

ABOUT ME
This section is to introduce yourself to our potential customer, your values, achievements and competitive advantage.

CONTACT ME
Clicking on Contact me menu item the user will be redirected to a section that has a form with respective fields:
Name;
E-mail;
Phone number;
Message type:
Book a visit;
More information;
Questions.
Text field to add comments;
Send button.

NEWSLETTERS
Finally, the user will be able to access and read content you previously wrote and sent by email. This content could help to rise website's visibility in search mechanisms (Google e.g.).
It will be possible to see through a list (like in a blog) previous newsletters

I WANT TO SELL MY PROPERTY
Property location;
Estimated Property value;
Property Style:
Single family detached;
Semi detached;
Condo Apartment;
Townhouse
Estimated Property value.


