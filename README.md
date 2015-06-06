# food-for-health
App for finding places for SNAP, WIC, DUFB, and others

## What
This application is intended to serve as a resource for recipients of public benefits such as SNAP and WIC. The purpose is to allow users to locate sources of healthy food close to where they live or work, particularly in "food desert" areas where access to healthy food sources is limited. By using this application, users will be able to view a list or map of healthy food outlets, and then filter the displayed results if desired by selecting the types of food sources they seek, entering additional parameters such as whether the outlet accepts SNAP and/or WIC benefits, or whether the outlet provides additional benefits such as double benefits.

The ultimate objective is to support more healthy eating habits among recipients of public benefits as well as others choosing to utilize the system.

#### Assumptions
1. Many recipients of public benefits, particularly in "food desert" areas, would avail themselves of healthier food choices if they had ready access to information on where these sources are located close to them.
2. Most recipients of public benefits have access to the web, either through a smartphone or a PC-based browser.

#### Process
1. The user navigates to the application and specifies their location, either by using the internal location capabilities of their mobile device (GPS), or by specifying their address (or the address on which they wish the search to be based).
2. The application uses the address to search the data to locate store/outlet records and displays results initially as a list of results ordered by proximity to the user's address.
3. The user can change to map view if desired by selecting the map tab. Search results are passed to Google Maps and displayed as customized pins based on the category of outlet as specified in the spreadsheet.
4. The user can also modify the search criteria by selecting or deselecting specific store/outlet categories (e.g., farmers market, small/medium grocer), benefit acceptance status (e.g., accepts SNAP, accepts WIC), and/or additional benefits (e.g., double benefits).

#### Status
This project is currently in prototype / proof of concept status.

## How
This application is driven by data provided by the Richmond City Health District (RCHD). The data was imported from XLS files provided by RCHD and imported into Google docs. The application itself is written in Javascript with connections to the Google Maps API to display results in map format.
