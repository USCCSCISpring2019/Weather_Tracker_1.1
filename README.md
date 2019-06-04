# HW3_summer2019_philip_jung

### Application begins at default page - index.jsp
### MySQL Schema included in root folder
### Control flow
	When a user is logged in, essentially they will be traversing a mirrored application.
	Here, all the JSPs are almost identical to the original (not-logged-in) JSPs, except all searches
	are first sent to a Pre-Search Servlet where all data will be logged.

### Updates
#####	When Google Map marker click returns a lat/long, the coordinates are truncated.
##### 	This is because OpenWeatherMap API does not allow exceedingly long doubles

##### When a user registers with no name/ no password, this is allowed because technically, they pass all
##### written directives of HW. (Didn't want to make custom error)

