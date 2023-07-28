## Guide.
* the product works with .csv files. The .csv files should be formatted wit hthe following column headers for appropriate data display:
"Address |	City	| State |	Property Name | Latitude |	Longitude |	Total Sqft |	Built |	Floors |	Office/APT". Please see data.csv in card-slider/v3/.
* Once formatted (can be done in Excel, Spreadsheets, etc) export as csv and rename to "data.csv".
* Images named after the Property Name column are automatically uploaded as images. The images are stored in the card-slider/v3/imgs.
* Please set your Mapbox API token while referencing the Mapbox docs. https://docs.mapbox.com/help/getting-started/access-tokens/ is a useful reference.

Methods of use
* [Placing in an iframe](https://www.techtarget.com/whatis/definition/IFrame-Inline-Frame#:~:text=What%20is%20inline%20frame%20(iframe,webpage%20within%20the%20parent%20page.)https://www.techtarget.com/whatis/definition/IFrame-Inline-Frame#:~:text=What%20is%20inline%20frame%20(iframe,webpage%20within%20the%20parent%20page)
* The index.html webpage and other files at the directory level ./v3/ can be placed on any website.

 How to Use
 * Clicking a card or marker selects the property. When selected, the property count and square footage count updates. To change the display of these, go to index.html in ./v3 and ctrl+f "sqft" to change to square footage or whatever terms required.
 * To deselect a property, click a marker or card, or click the x next to the property name displayed at the bottom of the screen.
 * This product is designed to be very versatile. If you take any property sheet with property name, latitude and longitude coordinates in their appropriate columns, the information will be displayed on the map (provided API is set up). The cards displayed on any portfolio can be changed with any .csv sheet. The images can be freely scraped and I will upload the Python image-scraping-based-on-csv-title script if I have it in an old commit and can find it.
 * The manual labor is at the data entry level of simply documenting the properties listed. depending on the client one can just scrape the information from a precompiled index publicly listed somewhere on the web. It's just a matter of formatting the data into the appropriate table.
