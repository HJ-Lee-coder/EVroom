# EVroom Privacy Policy

Effective date: October 25, 2026

EVroom (the "App") is an iOS app that receives speed and power data from a Tesla vehicle over Bluetooth and shows it on a gauge cluster with a synthesized engine sound. This policy explains what information the App uses, who it is shared with, and what choices you have.

## 1. Summary

- The App has no accounts or sign-in, and it does not send your information to any server run by the developer.
- Vehicle details and settings are stored only on your device.
- Third-party SDKs may process some information for ads (Google AdMob) and speed camera warnings (Kakao Mobility SDK). See sections 3 and 4.

## 2. Information processed only on your device (not sent to the developer)

| Information | Purpose | Where it is kept |
|---|---|---|
| Vehicle Identification Number (VIN) | Connect to your vehicle over Bluetooth | App settings on the device |
| Vehicle key (cryptographic key for Bluetooth authentication) | Pair with and connect to your vehicle | The device Keychain |
| Speed, power, gear and tire pressure received from the vehicle | Show the gauge cluster and generate engine sound | Not stored (held in memory only while displayed) |
| App settings (cluster style, speed unit, volume, etc.) | Remember your preferences | App settings on the device |
| Engine sound files you import | Play engine sound | App storage (you can delete them in the App) |

All of this is removed when you delete the App.

**Bluetooth** is used only to communicate with your own vehicle. The App does not scan for or collect information about other nearby devices.

## 3. Ads (Google AdMob)

The App shows rewarded ads from Google AdMob when you use some features, such as importing engine sound files. To serve ads, the Google ads SDK may collect the following, which Google processes under its own policies.

| Information | Purpose |
|---|---|
| Device identifier (advertising ID) | Serving ads, measuring ad performance, analytics |
| Approximate location | Serving ads, analytics |
| Advertising data, product interaction | Serving ads, analytics |
| Crash, performance and other diagnostic data | Analytics, serving ads |

- **Tracking permission (ATT)**: When you first open the App, iOS asks whether to allow tracking. You can use every feature if you decline; you will see ads that are not personalized. You can change this later in **Settings > Privacy & Security > Tracking**.
- **Consent (UMP)**: In regions that require consent, such as the European Economic Area and the United Kingdom, an ad consent form is shown. You can change your choice in the App under **Settings > About > Ad Privacy Settings**.
- No ads are shown while the vehicle is being driven.
- How Google handles information: <https://policies.google.com/privacy>, <https://policies.google.com/technologies/partner-sites>

## 4. Speed camera warnings (South Korea only)

The speed camera warning feature is available only when the device region is set to **South Korea**. In every other region, this feature and its use of location are turned off.

- The feature uses the **Kakao Mobility navigation SDK** and your **location** to announce camera locations and speed limits. The App asks for location permission when you connect to a vehicle with this feature on. You can decline and still use the rest of the App.
- Location may be used while the App is in use and in the background for this feature.
- To authenticate and provide safety information, the Kakao Mobility SDK may exchange location and device information with Kakao servers, and Kakao Mobility handles that information under its own policy. The developer does not receive or store it.
- Turning off the "Safe Driving" setting stops the use of location. You can change location permission at any time in iOS **Settings > EVroom > Location**.

## 5. In-app purchases

The "Remove Ads" purchase is processed by Apple. The App and the developer never receive your payment method or card details.

## 6. Sharing and international transfers

The developer does not collect your information directly or share it with third parties. The SDKs in sections 3 and 4 (Google, Kakao Mobility) process information under their own policies, and that may involve servers outside your country.

## 7. Retention and deletion

Information stored on your device is removed when you delete the App. You can delete imported engine sound files with "Delete This File" inside the App. The developer holds no information about you.

## 8. Children

The App is not directed to children under 13 (under 14 in South Korea), and it does not knowingly collect personal information from children.

## 9. Changes to this policy

If this policy changes, the new version will be posted on this page with a new effective date.

## 10. Contact

For privacy questions, contact:

- Developer: LEE. HJ
- Email: tinyfunapp@gmail.com
