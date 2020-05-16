# Remove Admin Promotions for OpenCart
[![Maintainability](https://api.codeclimate.com/v1/badges/6ee65ee62daf16adfbda/maintainability)](https://codeclimate.com/github/shamelesscode/envato-sales-notifications/maintainability)
&nbsp;&nbsp;[![Test Coverage](https://api.codeclimate.com/v1/badges/6ee65ee62daf16adfbda/test_coverage)](https://codeclimate.com/github/shamelesscode/envato-sales-notifications/test_coverage)
&nbsp;&nbsp;[![Donate](https://img.shields.io/badge/PayPal-Donate-blue?logo=paypal)](https://paypal.me/shamelessgroup)

OpenCart has recently added an API feature to remotely retrieve advertisements to appear within the OpenCart Extensions management pages, depending on the extension type being viewed. While we understand and appreciate the need for OpenCart to add advertisements with referral links, it can often be a nuissance or point of confusion for customers who do not understand the purpose or validity of that link, especially when it appears and disappears depending on the item being viewed.

Installation
---

This extension was built using the native OCMOD extension format introduced in OpenCart 2.x, that is based on the original vQmod platform available for older OpenCart versions. This platform uses a series of XML instructions to dynamically modify core files of the OpenCart platform with cached versions that include the desired changes. This allows extensions to expand or modify core files without actually overwriting or replacing those files, hopefully making OpenCart upgrades easier and allowing any incompatible extensions to fail gracefully.

1) Download the "\*.ocmod.zip" archive relevant to your version of OpenCart from the [Releases](https://github.com/shamelesscode/oc-remove-admin-promotion/releases) section
2) Go to your OpenCart storefront's Admin portal
3) Click on "Extensions" from the left hand menu
4) Click on "Installer" from the resulting submenu
5) Click on the blue "Upload" button and select the archive file you just downloaded.
    
    ```
    You should see a green "Success: You have modified extensions!" message.
    ```
6) Click on "Modifications" in the left hand sub-menu of the "Extensions" menu item
7) Click on the blue "refresh" (two arrows in a circle) button in the upper right-hand corner of the screen to rebuild the extension cache.
    
    ```
    You should see a green "Success: You have modified modifications!" message.
    ```
8) Click on "Extensions" in the left hand sub-menu of the "Extensions" menu item
9) Click on the drop-down menu for "Choose the extension type" and go to different menu items.

    ```
    You should no longer see any banner advertisements appearing between the drop-down and
    the extensions list on the page as you change through the different extension types.
    ```

### Demo Video

<a href="https://www.youtube.com/watch?v=H7qt2HdkU-Y" target="_blank" alt="Play Demo Video on YouTube"><img src="https://www.shamelesscode.com/media/opencart-remove-admin-promotion-1.0-demovideo-github.jpg" width="100%"></a>
