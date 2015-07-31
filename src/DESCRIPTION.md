Widget to select the chart and filter data from a CKAN source in order to display it in google and flotr2 charts widgets. This widget will also allow the user to create a mashup with just the final desired graphs.

In order to make this widget work the CKAN resource data must be send from another widget or operator like ckan-source-from-url-operator, ckan-resource-selector or ckan-source-operator.

The only preference you should consider:

* The link to the CKAN instance where the resource is stored (https://data.lab.fiware.org by default)