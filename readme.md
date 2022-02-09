# steps to break

i used this steps to break this repo

-   coldbox create app itb-webapp
-   start port=43512
-   create a valid datasource in lucee server admin
-   cfconfig export to=.cfconfig.json includeList=datasources
-   now i have a valid datasource in .cfconfig.json
-   install commandbox-migrations
-   migrate init: this modifies my box.json
-   reload or r
-   migrate install
