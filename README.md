OpenWRT package for IVPN

This is a fork of Kirill Scherbenok's OpenWRT package for VyprVPN, found here https://github.com/scherbenokk/vpn.git/.

To use these packages you need to add this feed to your openwrt feeds list dy adding following line in openwrt_source_tree/feeds.conf.default file: src-git vpn https://github.com/BelArvardan/vpn.git

Update/download all feeds: ./scripts/feeds update

Install all (-a) packages from this feed (-p) vpn: ./scripts/feeds install -a -p vpn

Then select needed packages in menuconfig and make the firmware.



IVPN is an online privacy service and security service operating out of Gibraltar.

PGP fingerprint: 8169 5A68 8402 C4BE AB33 CEA4 92B6 B00E C485 B578

Find More information about IVPN or signup by following this link. https://www.ivpn.net/aff.php?aff=1471


