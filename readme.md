# Get Started
1. Clone repo on to system
2. Edit telegraf.conf
  - Add the VM Host Name (ex. MyMachine)
  - Edit the URL for InfluxDB (ex. ["http://192.168.1.20:8086"]

# Grafana
1. Dashboards > Manage > Import
2. Import System Metrics Dashboard ID- 5955
3. Select database "virtualmachines"

Once the dashboard loads, you can select different **Server** names
