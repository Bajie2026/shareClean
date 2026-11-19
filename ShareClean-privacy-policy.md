# Privacy Policy for ShareClean

Last updated: 2026-11-18

ShareClean is provided by shiyadongg ("we", "us"). This policy explains what
happens to your data when you use the ShareClean app and its Share Extension.

## The short version

We do not collect, store, transmit, or share any of your data. ShareClean has
no servers, no accounts, no analytics, no advertising, and no third-party
SDKs. Everything happens on your device.

## What ShareClean does

When you share an image to ShareClean from another app, the Share Extension:

- reads the image in memory from the host app's share sheet;
- uses Apple's on-device Vision framework to detect text regions, faces and
  barcodes;
- applies local pattern rules to highlight potentially sensitive content
  (names, phone numbers, ID numbers, amounts, email addresses, QR codes);
- draws the masks you select onto the image;
- writes a clean copy by re-encoding the image, which removes EXIF metadata
  including GPS location;
- returns the clean copy to the host app, or copies it to the clipboard if
  you choose.

## Data we collect

None. Specifically:

- We do not receive your images. Images are processed only in the memory of
  the Share Extension and are not written to any shared container or uploaded.
- We do not collect identifiers, device information, usage statistics, or
  diagnostics sent to us. (A short technical log of the last share operation
  exists on your device only — see "Data stored on your device".)
- We do not use cookies, tracking, or advertising identifiers. We do not
  request App Tracking Transparency permission because we do not track.
- We do not have an account system, so there is nothing to log in to and no
  account to delete.
- The app contains no network code. It works fully in Airplane Mode. You can
  verify this in Settings, which shows "0 bytes uploaded".

## Data stored on your device

The following values are stored locally and never leave your device:

- your preferences (default mask style, whether to show hints);
- a daily counter used only to apply the free-tier limit;
- your purchase status, verified with StoreKit and shared between the app and
  its extension through an App Group container;
- a short local diagnostics log of the most recent share operation (technical
  steps only, never any image content), kept in the same local container to
  help you report problems. It never leaves your device and is overwritten
  on each use.

Purchases are processed entirely by Apple through the App Store. We never see
your payment information. Because ShareClean has no accounts, purchase status
lives only on your device and is restored with "Restore Purchases".

## Permissions

ShareClean requests no system permissions. It does not access your Photo
Library, Camera, Microphone, Contacts, Location, or Notifications. The image
you process is handed to the extension by the app you are sharing from.

If a future version offers "Save to Photo Library", it will ask for
add-only permission and this policy will be updated first.

## Third parties

None. ShareClean links only Apple system frameworks (Vision, Core Graphics,
ImageIO, StoreKit, SwiftUI). There are no third-party SDKs.

## Children

ShareClean is rated 4+ and does not knowingly collect any data from anyone,
including children.

## Changes

If this policy ever changes, the updated version will be posted at this URL
with a new "Last updated" date. We will never expand data collection without
also updating the app's App Privacy label and privacy manifest.

## Contact

shiyadongg — shiyadonggo@163.com
github.com/Bajie2026/shareClean
