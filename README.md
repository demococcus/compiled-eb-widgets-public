# Widgets Experience Builder

This repository contains the compiled version of some Experience Builder widgets.


## How to compile the widgets

1. Using your terminal, go to the folder  
**arcgis-experience-builder**/client/your-extension/widgets

2. Run the following command:  
`npm run build:prod`

3. The compiled version will be generated in   
**arcgis-experience-builder**/client/dist-prod/widgets/exp-builder-widgets

## How to publish as static page (on GitHub)

The compiled version of the widget needs to be hosted on a web server as a static page. In this instance, I am using GitHub's "Pages".

1. Upload the compiled code to the GitHub repo
2. In the GitHib repo, go to "Settings" and then "Pages"
3. Choose the branch and publish it as a page
4. Note taht it takes about 10 minutes for the page to be activated

## How to publush the widget on ArcGIS Entreprise portal

1. On the portal, choose "Content" and then "New item"
2. Choose "Application" and then "Experience builder widget"
3. Enter the URL of the file manifest.json from the hosting service (GitHub Page)
4. Choose a name for the widget and enter a description
5. Share the widget to a group on the portal (or make it public)
6. The widget is now available in Experience Builder on ArcGIS Entreprise portal

## How to update the widgets
1. Recompile the widget
2. Push the changes to the repo

## References
* [Add Experience Builder Custom Widgets In ArcGIS Enterprise](https://www.esri.com/arcgis-blog/products/arcgis-enterprise/developers/add-experience-builder-custom-widgets-in-arcgis-enterprise)
* [Add custom widgets](https://doc.arcgis.com/en/experience-builder/11.0/configure-widgets/add-custom-widgets.htm)