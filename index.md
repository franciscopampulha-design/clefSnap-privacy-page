# ClefSnap privacy policy: changes for sent scan reports (draft, 2026-11-09)

For the owner's privacy page (franciscopampulha-design/clefSnap-privacy-page). Ship
the app version that uploads reports only after this is live.

## 1. "The short version": replace the first bullet

> Your scores, photos and PDFs stay on your device. The app reads printed music on your
> device. We receive a photo or PDF only when a scan cannot be read and you choose to
> send it to us, and then only that scan.

## 2. "Information sent off your device": add after "Usage statistics"

> **Scans you choose to send.** When a scan cannot be read, the app asks whether you
> want to send it to us so that a future version can read it. Nothing is sent unless you
> tap Send. If you do, the app sends that scan's photos or PDF, why the reading stopped
> (and on which page, how long it took, how many lines of music were read), the app
> version, your device model, system version and memory, and your language. It does
> not send your other scans, your scores, your name or any account information; the
> app has no account. The scan goes over an encrypted connection to our own server
> (clefsnap.com, hosted by Namecheap), where only we can read it. We use it only to
> find and fix the reason it was not read, and we keep it for at most 90 days. Your IP
> address is not stored with it (a one-way hash of it is kept for an hour to limit
> repeated uploads). To have a scan you sent deleted sooner, write to
> theeargymapp@gmail.com with the day you sent it and your device model.

## 3. "Your rights": replace the first sentence

> We keep no personal data about you on any server of ours, except scans you choose to
> send, which are kept for at most 90 days (see above) and deleted on request.

## 4. The date at the top

> Last updated: <the day this goes live>

## Google Play Data safety form (Play Console → App content → Data safety)

- Data collected: **Photos and videos → Photos** (and **Files and docs**, for PDFs):
  collected, not shared, **optional** (the user chooses), purpose **App functionality**
  (fixing reading failures). Processed ephemerally: no.
- **App info and performance → Diagnostics**: collected, optional, App functionality.
- **Device or other IDs**: unchanged (Firebase's app-instance id, as now).
- Encrypted in transit: yes. Users can request deletion: yes.
