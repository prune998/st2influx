# st2influx
a SmartThings Groovy SmartApp that ship metrics from sensors to an influxdb endpoint

![alt tag](https://raw.githubusercontent.com/prune998/st2influx/master/images/smartthings-dashboard.png)

Install :

- copy the content of the groovy file to a new smartApp in the SmartThings dev site https://graph.api.smartthings.com
- Save
- Publish for "My Apps"
- Go to the Smartthings mobile application and create a new SmartApp using the one you just created

Inside the application, select all the sensors you want to track. Then configure the Influxdb infos.
You need a running Influxdb server. Start at https://docs.influxdata.com/influxdb/v0.10/introduction/

One of the best Dashboard for InfluxDB is Grafana. http://grafana.org/
Upload the provided Dashboard (smartthings-dashboard.json) into your grafana setup. If needed, change the Datasource (mine is named "influxdb") to match the one your defined.


