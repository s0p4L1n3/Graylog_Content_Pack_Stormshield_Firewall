# Stormshield Firewall Content Pack

Tested with Stormshield 4.0.3 and Graylog 5.1.4. Should work with all Stormshield 4.X version.

The Content Pack should be compatible with all Graylog 5.X version.

**Note this was built without extractors, only pipeline rules.**

## Includes

* Input (Syslog/UDP/1514)
* Stream (Firewall)
* Pipeline Rule w/ 1 stage (Extract key/values pipeline function)
* Dashboard (24h) (Stats Firewall)


## Requirements
* Graylog 5.0 
* Stormshield Firewall w/ Syslog 1514/UDP Ports
* Open port 1514 for UDP on the graylog host and/or docker compose file
* Edit content-pack.json and find the strings:
  - `firewall.lab.lan` and rename it according to your firewall hostname.
  - `Europe/Paris` and rename it according to your server Timezone
* Make sure set order according to below image in System > Configuration > Message Processors
![image](https://github.com/s0p4L1n3/Graylog_Content_Pack_Stormshield_Firewall/assets/126569468/25978888-0b9f-4c1c-be15-9a6e6214feb7)

 
## Install the content pack

![Install_content_pack](https://github.com/s0p4L1n3/Graylog_Content_Pack_Stormshield_Firewall/assets/126569468/50deca7c-e7ba-45af-b3ff-136d478e55bb)


## Stormshield Firewall Syslog configuration

![image](https://github.com/s0p4L1n3/Graylog_Content_Pack_Stormshield_Firewall/assets/126569468/782b29be-29df-4fc5-aa48-25079b76d60f)


## Screenshots

![image](https://github.com/s0p4L1n3/Graylog_Content_Pack_Stormshield_Firewall/assets/126569468/39372f8d-a38c-4829-bf1f-5c3d49360a0b)

![image](https://github.com/s0p4L1n3/Graylog_Content_Pack_Stormshield_Firewall/assets/126569468/be4acea1-8c85-4c36-8b3b-163f2c59b8b4)
