# smoker
Configuration, management and monitoring of my home-built smoker, powered by Arduino

Runs the following services:
 - Configuration: nginx server hosting single configuration JSON file
 - Metrics: influxdb to receive time-series metrics from the smoker
 - Dashboards: grafana to display real-time dashboards for the smoker

# TODO

 - Config the config.json is in the proper format, and recalculate all of the values
 - Test to make sure Influx can receive metrics
 - Confirm Grafana datasource for Influx is working
 - Create dashboard, make sure it saves to grafana data for posterity
 