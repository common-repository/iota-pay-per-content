=== Iota Pay Per Content ===
Contributors: 019mrb
Donate link: https://github.com/iota-argentina-community-cluster/iota-ppc-wp-plugin/#donate
Tags: iota, pay, ppc, blog, payment, read, decentralised
Requires at least: 4.6
Tested up to: 5.2.1
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Allow payments on certain posts using IOTA.

== Description ==
Allow payments on certain posts using IOTA.
You can choose whether to wait for transactions to be confirmed or not in order to grant access to contents.
IMPORTANT: this is a work in progress and we encourage the community to help us improving the concept. Feel free to submit issues or pull requests if you have tested the code proposed.

== Installation ==
1. Install it and go to Plugins section on your Dashboard and activate the Plugin.
2. Go to IOTA PPC Configuration page and enter a Node (you can use one from (https://iota.dance)).
3. Enter the address in which you will receive the payments.
4. Select if you want buyers to wait until the transaction is confirmed or not. 

== Using the PPC on Posts ==
Once the plugin is installed you will find a box at your Entries page. In order to require a payment for a given post you need to check the "Request IOTA payment to access" box, enter an amount and select the units (i.e. Iota/Kiota/Miota)
You will also need to provide some text into the Excerpt box, to display as an advance of the blocked content.

Check screenshot 1

== Making the payments ==
Posts that require an IOTA payment will display the Title, Excerpt content and a QR Code, Deep Link and the Transaction data. To use Deep Links users must enable them on their Trinity Wallet. 
Once the payment is sent, users can click on "Verify Payment" and they should be redirected to the complete content. 

Check screenshot 2

== Considerations ==
1. Issuing a fake transaction is easy on IOTA so, if you want to be 100% sure about the payment of a given content it might be a good idea to wait for the transaction to be confirmed (this can be done at your IOTA PPC configuration page).
2. At the moment of this release Deep Links are not supported in all Trinity versions (they should work on Android and Iphone last releases).
3. We know, lots of globals and data/view mixed. This is kind of the Wordpress way but we will improve that soon. 
4. Feel free to style the components at index.php to match your design. Again, this is just a PoC and we hope the community help us to improve it. 

== Screenshots ==
1. Using the Iota PPC on posts
2. Making the payments

== Changelogs ==
= 1.0 =
First version

== Donate ==
Address: N9UZLNCGCOIKXCTLLEFVRLFKVO9WIFMEWSFWISMIVRTCMLKEDITNQ9P9MYVSMXXXTKUJHJXPKOLBY99VCJJRRWCTCC







