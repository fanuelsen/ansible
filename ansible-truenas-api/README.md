## Ansible task for updating Truenas hosts.

### Edit sites in main.yml to your preference, add more sites as needed.
| Lines | Usage | 
| ---- |----| 
| ```ip:``` | ip / dns of your truenas host |
| ```token:``` | API Bearer token generated from the Truenas GUI |
| ```validate_certs::``` | Set to false if you have self generated certs |
