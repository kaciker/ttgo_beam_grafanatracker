# ttgo_beam_grafanatracker
Connection to InfluxDB cloud


This app is used to connect to the Xavier Florensa  https://github.com/xavierflorensa/TTGO-t-Beam-to-InfluxDB-cloud20



You need to install two plugins in Grafana

## Connection to InfluxDB cloud
https://grafana.com/grafana/plugins/grafana-influxdb-flux-datasource

## track Map
https://grafana.com/grafana/plugins/pr0ps-trackmap-panel



If you use Docker Compose, you can include this in the grafana conf to install both plugins 

      - GF_INSTALL_PLUGINS=grafana-influxdb-flux-datasource
      - GF_INSTALL_PLUGINS=pr0ps-trackmap-panel
