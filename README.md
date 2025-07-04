# Widgets Experience Builder

This repository contains the compiled version of Experience Builder widgets.


## Steps to compile the widgets

1. Using your terminal, go to the folder  
**arcgis-experience-builder**/client/your-extension/widgets

2. Run the following command:  
`npm run build:prod`

3. The ocmpiled versiopn will be generated in   
**arcgis-experience-builder**/client/dist-prod/widgets/exp-builder-widgets

## Steps to publish with GitHub

The compiled version of the widget needs to be hosted on a web server in order to use it with ArcgGIS Entreprise. In this example, I use GitHub's publishing service "Pages".

1. Upload the compiled code to the GitHib repo
2. In the GitHib repo, go to "Settings" and then "Pages"
3. Choose the branch and publish it as a page
4. Note taht it takes about 10 minutes for the page to be activated

# Steps to publush the widget in the ArcGIS Entreprise portal

1. In the portal, choose "Content" and then "New item"
2. Choose "Application" and "Experience builder widget"
3. Enter the URL of the file manifest.json from the hosting service (GitHub Page)
4. Choose a name for the widget and enter a description.
5. Share the widget to a group on the portal (or make it public)
6. The widget is now available in Experience Builder on ArcGIS Entreprise portal

## Update the widgets
1. Recompile the widget
2. Push the changes to the repo

## Actualiser les widgets
1. Recompiler les widgets
2. Pousser le code compilé vers la branche correspondante du repo GitHub

## References

* [Add Experience Builder Custom Widgets In ArcGIS Enterprise](https://www.esri.com/arcgis-blog/products/arcgis-enterprise/developers/add-experience-builder-custom-widgets-in-arcgis-enterprise)
* [Add custom widgets](https://doc.arcgis.com/en/experience-builder/11.0/configure-widgets/add-custom-widgets.htm)