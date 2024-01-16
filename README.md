# -Reversed-SF-API

‼️ Reversed StreamFab API Available ‼️

🔰 Description:

The StreamFab API is an API created by StreamFab (https://streamfab.com/) for extracting Widevine keys which are necessary for decrypting DRM-protected content. This API uses Google's Widevine ChromeCDM to generate Widevine license requests and it decrypts the resulting license responses in order to derive the content keys of a Widevine protected DRM video.

Presently, StreamFab appears to encrypt the responses of their API to prevent tampering by unauthorized individuals. 
The Reversed StreamFab API, which I am offering, includes a script and a tool designed to automatically decrypt these responses without manual intervention. For decrypting StreamFab's API responses on Linux machines, the script will use a .so file. To decrypt API responses on Windows machines, I have added the option to select either a .dll or a .exe file, based on your preference. By using this you will get the ability to create Widevine license requests using StreamFab's ChromeCDM API, execute license requests using it to your video's license server, and extract the content keys from your DRM-protected video by sending the received license responses back to StreamFab's ChromeCDM API.

Furthermore, StreamFab utilizes another API to cache content keys and retrieve them based on the video's KID (Key ID). This approach enables them to bypass the necessity of repeated license requests for the same video. 
The Reversed StreamFab API, which I am selling, also includes a script which can help you to extract content keys using your video's KID by searching their cached keys database.

As the Reversed StreamFab API I am offering is designed in a straightforward and a simple manner, you will also gain the ability to integrate the StreamFab API into your existing scripts/tools for extracting Widevine content keys easily.

🔰 Summarized Features of the Reversed StreamFab API script:

❇️ Ability to use StreamFab's ChromeCDM API for extracting keys.
❇️ Ability to search StreamFab's cached keys database and get keys using the KID
❇️ Ability to use the decrypt the StreamFab API responses on both Windows and Linux machines.
❇️ Ability to implement the StramFab's ChromeCDM API on your own scripts by looking the given example script.
❇️ Many of you know that StreamFab hardly changes anything in their API. This means that what I'm offering will last a long time. Plus, you'll also get to use the newest Chrome CDM version through this API without any changes when StreamFab adds it in the future.

Price: 75$

🔰 Payment Choices:

❇️ You have the ability to pay via Paypal, Credit/Debit Card, or Apple Pay.
❇️ Moreover, payments using various cryptocurrencies are welcomed.

You can directly purchase the "Reversed SF API" through my Buy Me a Coffee shop link: https://www.buymeacoffee.com/DRMReversed/e/204425

Furthermore updates and information will be posted on my channel https://t.me/drmreversed
