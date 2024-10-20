# Modules Diagram

```mermaid
Sensor 1>RTL-SDR USB;
Sensor 2>RTL-SDR USB;
Sensor n>RTL-SDR USB;
RTL-SDR USB>RTL_433;
RTL_433>RTL Data Collector;
RTL Data Collector>RRD DB;
RTL Data Collector>Picture;
Picture>WEB Server;
```
