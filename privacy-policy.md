# Fault Frame privacy policy

Effective date: 11 September 2026.

## Who provides the app

Fault Frame is an Android vehicle diagnostic app published by Thaddeus McAllister in Ireland under the developer name voxrelay. For app support or privacy requests, email voxrelaynew@gmail.com. This policy describes the app's diagnostic functions, local records, optional online vehicle identification, user-selected exports and support contact.

The publisher is responsible for deciding how personal information sent to the support address is used and is the data controller for that correspondence. The app does not send its local diagnostic records to the publisher automatically. External services receive information only as described below and have their own privacy notices.

## Diagnostic data on your device

When you choose an adapter, Fault Frame reads standard vehicle diagnostic information, which can include fault codes, readiness, live sensor readings, freeze frames, ECU identifiers and raw replies. It also reads a supported VIN after connection. The simulator supplies synthetic information instead of information from a vehicle.

Fault Frame processes these readings locally. Saved scans and drive logs remain in app-private storage unless you choose to export or share them. Garage entries contain the vehicle names and notes you enter, selected adapter connection details such as a Bluetooth address or local network endpoint, and reconnect preferences. Display choices, graph presets and the online-identification preference are stored locally. There is no account, advertising SDK, app analytics upload or automatic crash-report upload in this build.

The automatically read VIN and online identification result remain in the current diagnostic session. They are not automatically added to Garage, saved scans, drive logs or diagnostic reports. Information you deliberately type into a Garage name or note is retained as entered; avoid adding personal details you do not need.

## Optional identification through NHTSA

Online make/model/year identification is optional. For a one-time lookup, the app asks before sending the VIN over HTTPS to the US National Highway Traffic Safety Administration's vPIC service at vpic.nhtsa.dot.gov. A separate automatic-lookup option starts off and requires consent; if enabled, it sends the VIN after subsequent adapter connections. You can turn it off in Settings. Fault codes, recordings and Garage entries are not included in that request. Simulator VINs are not sent.

NHTSA also receives normal connection information such as your public IP address and request metadata. Its [privacy policy](https://www.nhtsa.gov/about-nhtsa/privacy-policy) describes website logging and says automatically collected website-visit information is retained indefinitely. Fault Frame does not control NHTSA's storage or deletion, and does not promise that remote processing is temporary. The request goes directly from your device to a US government service; UK and other non-US vehicle coverage may be incomplete. Turning off automatic lookup prevents future automatic requests but cannot retract a request already sent.

## Reference links and exports

Searching the bundled fault-code reference does not send the search to a server. Opening a source link hands its public address to your chosen browser. The website and browser then apply their own privacy practices. Fault Frame does not automatically add your VIN or scan results to those source links.

Saving or sharing a report or recording is your choice. Android's document picker or share chooser lets you select the destination or receiving app, which may be a cloud service. That recipient can keep its own copy under its own policy. Automatic VIN and identity fields are omitted from diagnostic reports, but raw diagnostic readings, timestamps and ECU information can still reveal details about a vehicle. Review files before sharing them.

## Permissions and security

Bluetooth access is used to discover, pair with and communicate with the selected adapter. Android 10 and 11 may require location permission for Bluetooth discovery; this app does not read GPS coordinates or record routes. Local-network/internet access is used for a chosen Wi-Fi adapter and the optional NHTSA request. Notifications identify the ongoing connection or recording. The connected-device service and a partial wake lock support diagnostic work while connected; they are not location tracking.

NHTSA requests use HTTPS. Adapter communication uses the adapter's Bluetooth or local-network protocol and is not guaranteed to be encrypted by Fault Frame; local Wi-Fi OBD traffic is ordinary TCP. App-private files use Android's access controls, without additional app-level file encryption. Fault Frame has no automatic cloud-sync feature. The release configuration excludes its data from Android app backup/transfer; exported copies and copies independently made outside the app remain under your control or the recipient's control.

## Retention and deletion

Session VIN and identity are cleared when the diagnostic session is reset or disconnected. Saved scans, completed recordings, Garage entries and preferences remain until you delete or change them, clear the app's storage, or uninstall the app. Storage is bounded; full history rejects new saves rather than silently deleting older diagnostic records. Uninstalling or clearing app storage does not remove exports already stored elsewhere.

The app creates temporary files to complete exports and provide share recipients access. Shared copies are eligible for the app's bounded cleanup after at least 24 hours; they are not guaranteed to disappear exactly at that time, and Android may clear cache storage independently. Files already saved or received outside Fault Frame must be deleted at those destinations. Fault Frame cannot delete NHTSA's request logs or another app's copies.

## Support and feedback

If you email voxrelaynew@gmail.com, the publisher receives your email address, any name your email provides, your message, attachments you choose to include and normal email headers. The publisher uses this information to respond, investigate the issue you report and handle any related privacy request. Providing feedback is optional; without enough information, it may not be possible to investigate a particular issue. Do not include a full VIN or unreviewed diagnostic attachments in routine feedback.

The support mailbox uses Google's Gmail service. Google and your email provider handle message delivery, storage and service security. Google's [privacy policy](https://policies.google.com/privacy) describes its handling of information, retention and international processing. Google operates servers in multiple countries, so support correspondence may be processed outside Ireland or the European Economic Area. This policy does not promise that deleting a message from the publisher's mailbox deletes every copy held by a mail provider or recipient.

Support correspondence is retained for as long as needed to answer the request, investigate and resolve the reported issue, and deal with a related follow-up or dispute. The criteria are whether the matter is resolved, whether the information is still needed for that matter, and whether a specific legal obligation requires it to be kept. Information that is no longer needed for these purposes is to be deleted. You can request deletion by emailing the same address.

## This privacy-policy website

This policy is hosted on GitHub Pages at the [Fault Frame privacy-policy page](https://mcallistertad.github.io/fault-frame-privacy/). The page contains no publisher-added analytics, advertising, cookies, forms or third-party embedded content. Opening it makes a normal web request to GitHub, which receives technical information such as your IP address, browser information, requested page and request time to deliver and operate its service.

GitHub controls its service logging and retention. Its [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) explains how it uses technical information, its retention criteria and international transfers, including processing in the United States and other countries. The publisher does not receive your app's VIN, diagnostic readings or local records when you visit this page.

## Reasons for using personal information

The app uses local data to perform the diagnostic, saving and export operations you choose. Its optional disclosure of a VIN to NHTSA depends on your consent, given for one lookup or through the separate automatic-lookup setting. You can withdraw that choice for future requests by turning off automatic lookup in Settings. Withdrawal does not undo processing that already occurred.

For support correspondence, the publisher relies on the legitimate interest of answering requests and investigating reported app problems, using the information needed for that purpose. You can object to that use. Information needed to fulfil a data-protection request or another specific legal duty is processed to meet that legal obligation. These purposes do not include marketing, advertising or profiling.

## Your choices and privacy requests

You can use the simulator, offline reference and supported local diagnostics without online identification. You can cancel a one-time lookup, disable automatic lookup, revoke Android permissions, delete local records and choose whether to export or send feedback. There is no Fault Frame account to delete. Contact the privacy point above about information you have sent to the publisher; contact an external recipient about copies it controls.

Depending on applicable law and circumstances, you may have rights to access, correct, delete or restrict use of personal information, receive a portable copy, object to processing and withdraw consent. Email voxrelaynew@gmail.com to exercise these rights for information held by the publisher. The publisher cannot access or delete records held only on your device; use the app's deletion controls or Android's app-storage controls for those records. You can also complain to your data-protection authority, including Ireland's [Data Protection Commission](https://www.dataprotection.ie/en/faqs/initial-contact-dpc/making-complaint-dpc), which provides [information about your rights](https://www.dataprotection.ie/en/individuals/rights-individuals-under-general-data-protection-regulation).

## Changes

This policy will be updated when the app's data handling changes. The published policy and the in-app privacy information should describe the same release behaviour. Fault Frame is independent and does not represent NHTSA or any government or political entity.
