# OpenAIRE UsageCounts Badges

OpenAIRE UsageCounts service offers two badges that can be embedded in datasources, like Institutional Repositories, Data Repositories, registered in the service and display usage statistics from OpenAIRE for the datasource or individual research products, like publications, datasets, books, etc.

The badge, shows the total number of the usage usage statistics collected (sum of views and downloads). By clicking on the badge, the number of views and downloads are displayed.

# Embedding the badges

To embed the OpenAIRE UsageCounts badge into a web page, the following simple code should be added.

### Datasource badge
```
<div id="openaire-widget-div"></div>
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script id="openaire-widget" src="https://beta.usagecounts.openaire.eu/widget/usageCountsDatasource.js" openaireID="openaire_datasourceID"></script>
```

### Research Product badge
```
<div id="openaire-widget-div"></div>
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script id="openaire-widget" src="https://beta.usagecounts.openaire.eu/widget/usageCountsItem.js" itemID="item_ID"></script>
```

### Badge Parameters

| Badge      | Parameter | Sample Value |
| ----------- | ----------- | -----------
| Datasource      | openaire ID       | opendoar____::f1748d6b0fd9d439f71450117eba2725 |
| Research Product   | doi, handle, oai-pmh ID        | 10.1179/2047971911y.0000000001 |
