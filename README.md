# BoldGrid-Cpanel-Plugin

The BoldGrid cPanel integration plugin allows Server Administrators and web hosts to offer BoldGrid as a one-click installation directly from their users’ cPanel accounts, as well as integrate BoldGrid into their hosting packages. Administrators can offer BoldGrid completely free of cost, or sign up to become a hosting partner and offer premium licenses at a markup. Follow these steps to install the BoldGrid cPanel integration plugin.

Please note, these instructions are intended for a server administrator. This process requires root or sudo access to your server, as well as access to a terminal or SSH.

1. SSH into your server as a user with sudo access, or root.
2. Run the following command: `sudo yum install https://repo.boldgrid.com/cpanel/boldgrid-cpanel-latest.rpm`
3. Proceed to acknowledge the installation confirmation with the “y” key.
4. Log into WHM as the root user, or an administrative reseller.
5. Navigate to Plugins -> BoldGrid.
6. Input your BoldGrid Reseller Client ID and Client Secret and then click Login to the BoldGrid API. (If you don’t have one, sign up to become a hosting partner or leave blank to offer free BoldGrid licenses to your customers)
7. Optionally, enter the URL’s for your support documentation, or leave blank to use BoldGrid’s documentation.
<img src="https://raw.githubusercontent.com/cpanelplugins/BoldGrid-Cpanel-Plugin/main/Selection_155.png"></img>

Congratulations, you’ve successfully installed the BoldGrid cPanel integration plugin! For more tips and tricks check out our other support guides for BoldGrid Hosts: https://www.boldgrid.com/support/bg-for-hosts/
