# What Changed: Privacy Policy

Effective date: October 7, 2026

What Changed is a free Figma plugin made by an independent developer, Tarikul Islam ("I", "me"). This policy explains what the plugin does with your data. The short version: the plugin collects nothing, and it only talks to Figma.

## What the plugin handles

**Your Figma personal access token.** You paste a token so the plugin can read your file's version history through Figma's API. The token is stored only on your device, in Figma's plugin storage for your account (`figma.clientStorage`). It is sent only to Figma's API (`api.figma.com`), as the authentication header Figma requires. It is never sent anywhere else, and I never receive it.

**The date you saved the token.** Stored next to the token on your device, so the plugin can remind you before the token expires.

**The file link.** Figma does not tell public plugins which file they run in, so you paste the file link once. The plugin stores the file's key, and the file's name at that moment, inside that Figma file (plugin data), so collaborators in the same file skip this step and a copy of the file asks for its own link. Anyone with access to the file can see that this key is stored there; it is the same key that appears in the file's own URL.

**Your scope choices.** The plugin remembers your last choices (range, page, change types) on your device.

**The placed report's id.** When you place a report on the canvas, the plugin stores that report frame's id on the page (plugin data), so the next report replaces it instead of piling up.

**File content and version history.** When you run a comparison, the plugin downloads the saved versions you chose and layer previews from Figma's API (`api.figma.com` and Figma's image host `figma-alpha-api.s3.us-west-2.amazonaws.com`). It compares them inside the plugin, on your computer. The results exist only while the plugin is open, unless you choose "Place on canvas", which adds a report frame to your file like any other layer you create.

## What the plugin does not do

- It does not collect, store or sell any personal data.
- It has no analytics, tracking, ads or crash reporting.
- It does not send any data to me or to any server other than Figma's.
- It does not write to your file, except the file key and name, the report id described above, and the report frame you place yourself.

## Third parties

The only service the plugin contacts is Figma. Figma's own privacy policy applies to your use of Figma and its API: https://www.figma.com/legal/privacy/

## Keeping and deleting your data

- Figma tokens expire within 90 days. You can revoke a token at any time in Figma, under Settings, Security, Personal access tokens. A revoked token stops working in the plugin immediately.
- Reconnecting with a new token replaces the stored one. Revoking the token in Figma makes any stored copy useless.
- The stored file key stays with the file. It is the same key that is already in the file's link, so it reveals nothing new about the file.

## Children

The plugin is not directed at children under 13 and does not knowingly process their data.

## Changes to this policy

If this policy changes, the new version will be published at the same address (https://t4rikul.github.io/what-changed-privacy/) with a new effective date.

## Contact

Questions about this policy: workwidtarik@gmail.com
