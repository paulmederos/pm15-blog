# PM15 Blog

Personal blog for Paul Mederos, based on the Enchant theme he uses for work stuff.
The theme is a modified version of the default theme (Casper) for the open-source [Ghost](http://github.com/tryghost/ghost/) blogging platform.

Made with ❤️ in California. Hosted on [DigitalOcean](https://www.digitalocean.com/).

### Development

1. Run `yarn install` to get the goods
3. Use `yarn start` to kick off the SASS watching. This should be enough.

### Deploy

1. Use Transmit 5 to connect SFTP to DigitalOcean server.
2. Yup, drag + drop `/var/www/paulmederos.com/content/themes/pm15-blog`
3. Restart Ghost service

To restart:

1. SSH into DigitalOcean `ssh root@167.99.161.231` and enter password
2. switch to user with `su paul`
3. `cd /var/www/paulmederos.com`
4. `ghost restart`
5. Good to go 🎉

If all else fails, you can type `reboot` as root to restart the server.
