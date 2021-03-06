# Usage Instructions

## Options

1. **Use the Bitwarden browser extension (detailed screen shots below) on:**
- [Firefox](https://docs.start9labs.com/misc-guides/tor-firefox/index.html) (with Socks5 Proxy enabled) - (Mac, Windows, Linux, Android)
- Tor Browser - (Mac, Windows, Linux, Android)

2. **Use the Android Bitwarden native app with [Orbot](https://docs.start9labs.com/misc-guides/tor-os/android.html) running in VPN mode.**

3. **Access your Bitwarden web vault by visiting its Tor Address from any Tor-enabled browser.**


The instructions below are for Tor Browser on Mac, but it is the same basic for instructions for using the extension on alternative platforms.

1. Open the browser and visit the add-ons section.

<!-- MD_PACKER_INLINE BEGIN -->
![](./assets/img-1.png)
<!-- MD_PACKER_INLINE END -->

2. Search for “Bitwarden” and click “Add to Firefox”.

<!-- MD_PACKER_INLINE BEGIN -->
![](./assets/img-2.png)
<!-- MD_PACKER_INLINE END -->

3. Access the Bitwarden settings.

<!-- MD_PACKER_INLINE BEGIN -->
![](./assets/img-3.png)
<!-- MD_PACKER_INLINE END -->

4. Copy your Bitwarden Tor Address from the Services menu on your Embassy and paste it into the “Self Hosted Environment” → “Server URL” field. Add “http://” (*not* https://) to the frontend of the onion URL. Then click “Save”.

<!-- MD_PACKER_INLINE BEGIN -->
![](./assets/img-4.png)
<!-- MD_PACKER_INLINE END -->

5. Click “Create Account” and fill in the required fields.

This *does not* mean you are creating an account with Bitwarden or any other third party. You are creating an account with yourself on your own Embassy. It’s awesome!

<!-- MD_PACKER_INLINE BEGIN -->
![](./assets/img-5.png)
<!-- MD_PACKER_INLINE END -->

## Important!!

Bitwarden on the Embassy is a *self-hosted* password manager, which means your passwords physically live on your Embassy. Be sure to create backups and keep them safe. If you lose your Embassy or uninstall Bitwarden, and you have not made a backup, all your passwords will be lost forever.

## System Administrator Portal

This portal enables you to configure environment settings, edit users, edit organizations and check version information. To use the admin portal: 

1. Copy the admin token from `Properties`
1. Navigate to your Bitwarden Tor address + `/admin` ie. `http://<your_bitwarden_tor_address>.onion/admin`
1. Paste the admin token into the input field to login to the admin dashboard. 