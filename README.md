# Mapping web app
A generic data driven web app using Google Maps that loads data and settings from a .json file in Google Drive.

The Mapping web app is free to access, publicly available with no fee, no credentials are required for access, and the code is available on GitHub, for anyone to use.

# Main features:
− Load your data and settings from a .json file in your Google Drive by adding the File ID to the Mapping web app url  
− Instantly filter across the entire data content as you type in the search box  
− Use checkboxes for easy grouping and filtering locations according to the main filter  
− Use additional filters in combination with the main filter to show selected locations  
− Filtering within a section works with “inclusive or” logic
− Filtering across sections works with “and” logic
− Choose to fit the zoom and center of the map to show selected locations
− Click a marker icon to open an Infowindow showing all the details of a specific location
− Show or hide the list of selected locations
− Allows for custom code on post-processing Data, Infowindow and Locations List
− Take advantage of the many more features provided by Google Maps

# Usage restrictions
If your are using the Mapping web app code from this repository, you have to consider the following changes:
− You have to use your own Polymer elements host, by replacing the base path in mapping.html file, with your path
− You have to use your own Google Maps Api key, by replacing the default value in xm-data.html file, with your api-key
− When building your .json files, you have to use your own paths for icons and elements
