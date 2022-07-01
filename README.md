# Inofficial release

Incomplete and just for testing purposes.

# If you have n8n installed: Install custom nodes module

Install it to the n8n root folder. This is the node_modules folder on the same level of n8n and n8n-core. This differs when you used the -g flag on n8n initial installation. From there do:
```
npm install n8n-nodes-dnc-activecampaign-legacy
```
# Fresh install n8n

Navigate to desired folder, create a package json and install n8n like so:

```
cd /var/www/vhosts/

mkdir my-n8n && cd my-n8n

npm init --yes

npm install n8n

npm install n8n-nodes-dnc-activecampaign-legacy
```
# Start n8n

Directly:
```
n8n
```

Plesk or C-Panel:
```
node /var/www/vhosts/n8n/bin/n8n
```

# Latest functionality

Access to the old API.

# Use

Pass a data object.

# Contribution

To make this node even better, please let us know, [how you use it](mailto:info@digital-north-consulting.com). Commits are always welcome. 

# Issues

If you have any issues, please [let us know on GitHub](https://github.com/quansenB/n8n-nodes-dnc-xentral/issues).

# About
Special thanks to [N8n nodemation](https://n8n.io) workflow automation by Jan Oberhauser.

Support by [digital-north-consulting.com](https://digital-north-consulting.com).

This node was programmed with :heart: by Jan Oberhauser. Because it is not intended to be integrated in the official ActiveCampaign node it was extended and prepared for inofficial release by Iñaki Breinbauer [quansenB](https://github.com/quansenB).

# License

[MIT](https://github.com/n8n-io/n8n-nodes-starter/blob/master/LICENSE.md)
