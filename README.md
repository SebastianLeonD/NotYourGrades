# Privacy Policy — NotYourGrades

_Last updated: October 7, 2026_

## Short version

Your schoolwork never leaves your device. The extension has no server of its own and no analytics.
Data leaves your device in only two cases, both started by you: buying the $1.99 unlock, or sending
a message through the contact form.

## What is stored on your device

Saved with Chrome's `storage.local` API, on your computer only:

- whether editing is turned on,
- whether the on-page edit counter is visible,
- the grade values you typed, so they survive a page refresh,
- your licence state: whether you have paid, and the date your free trial started.

Clearing the extension's storage, or removing the extension, erases all of it. **Restore real
grades** in the popup erases the typed values on demand.

## What is never collected

Your grades, name, school, teachers, class list, and assignment names are read from the page you are
already looking at, used to do arithmetic, and written back onto that same page. They are never
transmitted, never stored off your device, and never seen by the developer. There is no analytics,
no telemetry, no tracking, and no advertising. Nothing is sold or shared with anyone.

## Trial and payment data

**Before you choose to buy, the extension makes no network requests for payment or licensing.** No
account, no identifier, no contact with any server. (The contact form, below, sends only when you
press Send.)

Payment is handled by [ExtensionPay](https://extensionpay.com) using [Stripe](https://stripe.com).
When you press **Unlock** or **I already paid**:

- ExtensionPay issues a random identifier, stores it in your browser, and registers it with their
  service. It is not linked to your grades, your school, or anything you typed.
- From then on the extension asks ExtensionPay a single question — whether that identifier has paid —
  when it starts up and when you open the popup. The answer is cached locally so the extension keeps
  working offline.
- Your email address and card details are entered on ExtensionPay's and Stripe's own pages, never
  inside this extension. The developer can see that a purchase occurred and the email attached to
  it; the developer never sees card details.

Their handling of that data is covered by
[ExtensionPay's privacy policy](https://extensionpay.com/privacy) and
[Stripe's privacy policy](https://stripe.com/privacy).

**How long you have been on the free trial is measured by a date stored in your own browser**, not on
a server. A deliberate trade-off: verifying it remotely would require collecting your email before
you had decided whether you wanted the extension at all. It also means reinstalling resets the trial.

## Contact form

The contact page is the one other place data leaves your device, and only when you press Send.

Submissions are delivered to the developer's email by [Web3Forms](https://web3forms.com), a form
delivery service ([their privacy policy](https://web3forms.com/privacy)). What is transmitted:

- your **message** and the **category** you picked,
- your **email address only if you chose to enter one** — the field is optional, and a placeholder
  address is substituted when it is left blank,
- your **screenshot only if you attached one**. Large images are resized and re-encoded inside your
  browser before sending, so the file that leaves your device may differ from the original,
- the **page address** and your **browser's user-agent string**, attached automatically, so that a
  reported bug can be reproduced.

This information is used solely to reply to you and to fix the problem you reported. It is not used
for marketing, not added to any mailing list, and not shared or sold.

## Permissions

- `storage` — to save the items listed above.
- Access to `*.focusschoolsoftware.com/focus/Modules.php*` — the extension's code only runs on Focus
  grade pages and only reads the numbers already displayed there.
- A script on `extensionpay.com` — ExtensionPay's own code, bundled with the extension. It runs only
  on ExtensionPay's checkout and login pages, so the extension learns when your payment completes.
  It reads nothing else.

The extension cannot read any other site you visit.

## Children's privacy

This extension is likely to be used by students under 18. That is why it requires no account,
transmits no schoolwork, and collects no personal information on its own. Personal data is involved
only when someone chooses to provide it: an email address given to the payment processor when
buying, or an email address and message sent through the contact form. Students under 13 should ask
a parent or guardian before buying or using the contact form.

## Contact

sebastian.08ld@gmail.com
