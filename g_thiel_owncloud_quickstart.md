# ownCloud Server Quickstart
**Note:** If you plan to install ownCloud Enterprise Edition, it is best to [see the instructions for that edition](https://doc.owncloud.org/server/latest/admin_manual/enterprise/installation/install.html) before you read this Quickstart.
## Instructions
1. Make sure that your system and environment meet these [prerequisites](https://doc.owncloud.org/server/latest/admin_manual/installation/system_requirements.html).
2. Plan which installation approach is most suitable for you:

    + **Tarball.** The most common approach in a production environment and the one that allows for maximum customization, this method lets you [set up ownCloud from scratch](https://doc.owncloud.org/server/latest/admin_manual/installation/source_installation.html) using a classic LAMP stack and the ownCloud .tar archive.

    + **Docker.** If you already have Docker and want the benefits it can bring to your environment, you can [use the ownCloud Docker image to install ownCloud](https://doc.owncloud.org/server/latest/admin_manual/installation/docker/).

    + **Appliance.** This method is the quickest and requires the least knowledge of Linux. Once you install a virtual machine, [import its ownCloud X Appliance image](https://doc.owncloud.org/server/latest/admin_manual/appliance/installation.html) to apply all of the software you need: ownCloud X Server, Apache2, PHP, and MySQL.

    + **Linux Distribution packages.** [Installing from ownCloud's Open Build Service packages](https://doc.owncloud.org/server/latest/admin_manual/installation/linux_installation.html) has the advantage that packages are maintained by ownCloud engineers, and you can use your package manager to keep your ownCloud server up to date.
3. Now, go to the [ownCloud download page](https://owncloud.org/download/), download the resources for the approach you decided on, and perform the installation.
4. [Configure the server](https://doc.owncloud.org/server/latest/admin_manual/configuration/server/) according to the needs of your environment.
5. [Enable users to connect to the server](https://doc.owncloud.org/server/8.2/admin_manual/configuration_server/config_sample_php_parameters.html#).
6. From the [User Management page](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/user_configuration.html) of your ownCloud web UI, add user accounts.
8. [Download an ownCloud client](https://owncloud.org/download/#owncloud-desktop-client). Install it and test ownCloud in a browser, using the IP address that was configured for the server as the url. Make sure that you log in as the user of the client, not as the administrator.   