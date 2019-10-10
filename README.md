redrum
======

home automation dashboard

### About

Based on a raspberry pi 4, a node-red project for home automation.  

Current features include:  
- Control Bluetooth lightbulbs (https://www.amazon.de/gp/product/B018IDMTJK/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1 - currently unavailable?)
    - on/off state
    - colour
    - temperature
    - brightness
- CPU temperature chart
- network arp scanner
    - device database including name, mac address, ip, last seen etc

### Dependencies

```
{
    "node-red-contrib-arp": "0.0.2",
    "node-red-contrib-cpu": "0.0.4",
    "node-red-contrib-interval": "0.0.1",
    "node-red-dashboard": "2.17.1",
    "node-red-node-ui-table": "0.1.5"
}
```
