# PM15 Blog

Personal blog for Paul Mederos, based on the Enchant theme he uses for work stuff.
The theme is a modified version of the default theme (Casper) for the open-source [Ghost](http://github.com/tryghost/ghost/) blogging platform.

Made with ❤️ in California. Hosted on [DigitalOcean](https://www.digitalocean.com/).

### Development

1. Run `yarn install` to get the goods
2. Run `yarn grunt` to kick off Grunt (watch SASS / compile JS)

### Deploy

After updating theme, you need to restart the `ghost` service via ssh console on DigitalOcean. I can't remember how to login to the ghost user, so after uploading the changes, I just run the `reboot` command on th droplet to restart the thing :shrug:
