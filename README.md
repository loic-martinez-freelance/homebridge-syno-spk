<p align="center">
<img width="400px" src="https://user-images.githubusercontent.com/3979615/79035227-bdd5be00-7bff-11ea-900f-2fef01bba4ba.png">
</p>

# Homebridge Package for Synology DSM

This third-party Synology Package simplifies the process of running [Homebridge](https://github.com/nfarina/homebridge) on Synology NAS devices.

## Information on this fork

Makes the package compatible with ARMADA375 old Synology NAS so it can run Homebridge without docker.

It should be compatible with these Synology models : 
- DS215J
- DS115

## DSM 7

This package will deploy Homebridge and the Homebridge UI natively on your Synology NAS. It will create a new shared named `homebridge` to store the Homebridge configuration and user data.

**Step 1:** Download the `.spk` from here: https://github.com/oznu/homebridge-syno-spk/releases/tag/2.0.0

**Step 2:** Open Package Center in DSM and select the `Manual Install` option.

**Step 3:** Click `Agree` when warned about using a package from an unknown publisher.

**Step 4:** Click `Done` to confirm installation. This may take some time as the latest version of Homebridge is downloaded and installed.

**Step 5:** Use the Homebridge app icon in the main menu to access the Homebridge UI where you can manage your setup.

The Homebridge Config UI app starts on port `8581`. The default username is **admin** with password **admin**.

## Issues

If you have an issue with the installation of Homebridge using this package please raise an issue on this project's GitHub page. For everything else:

* Homebridge Conifg UI Issues: [oznu/homebridge-config-ui-x](https://github.com/oznu/homebridge-config-ui-x)
* General Homebridge Issues: [nfarina/homebridge](https://github.com/nfarina/homebridge)
* For problems with individual plugins please raise issues on the relevant GitHub project page.

## Contributing

Pull requests are welcome.

## Setting up for development

See the [Synology DSM Developer Guide](https://help.synology.com/developer-guide/).

## License

Copyright (C) 2017-2022 oznu

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the [GNU General Public License](./LICENSE) for more details.
