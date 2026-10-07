# Love Invite Maker 💌

One HTML file. No server, no domain, no accounts. You fill in a form, download a personalised copy, send it on WhatsApp, and see her answer **and her plans**.

## What it can do

- **4 invite types:** Valentine 💘, Birthday wish 🎂, Date invite 🌹, Trip invite ✈️. Each fills in ready-made texts you can edit.
- **Everything is editable:** the big question, opening line or birthday wish, the Yes and No button text, the lines the No button shows, and the message after Yes.
- **Fun No button:** each No click makes Yes bigger and (optionally) No smaller.
- **Planner after she says Yes:** she picks a **date**, **time**, **place**, **food**, **extra ideas** (movie night, photoshoot, stargazing...) and a **trip** ("Come on a trip with me?"). She can add a note too. All the options are yours to change, one per line. Leave a box empty to hide that part.
- **You get her choices** by WhatsApp and/or instant notification.

## How to use

1. Open `will-you-be-my-valentine.html` in your browser (this is the builder).
2. Go through sections 1 to 4, then click **Create my invite**.
3. Click **Download HTML**. You get a personalised file named like `for-her-name.html`.
4. Send that file on WhatsApp as a document.
5. She opens it, taps Yes, picks her plan, and you get the answer.

## Getting her answer (use both)

### A) WhatsApp (she taps Send)
Enter your number with country code, no `+` or spaces (Sri Lanka example: `94771234567`). After Yes, a green button opens WhatsApp with a ready message. After she sends her plan, the button changes to **Send my plan on WhatsApp 💬** with all her choices filled in. She only needs to tap Send.

Browsers cannot send WhatsApp messages or emails silently, so this one needs her tap.

### B) Instant automatic alert (ntfy)
1. Install the free **ntfy** app (Android or iOS).
2. Subscribe to a secret name, e.g. `kasun-valentine-7392`.
3. Type the **same name** in the builder.
4. You get a notification when she taps Yes, and another with her full plan when she taps **Send my plan**.

She needs internet at that moment. Anyone who knows your secret name can read it, so make it random.

## Test first

Create a copy with your own name, open the downloaded file, click No a few times, click Yes, pick some options and send. Check that the ntfy alert arrives and the WhatsApp button opens your chat.

## Photos

Paste an image link (keeps things small) or upload a photo (cropped small and stored inside the file, best with the downloaded file).

## Sending tips

- Send as a **document** on WhatsApp. On Android, tap it and open with Chrome.
- iPhone may not run HTML from WhatsApp's preview. Tell her to open it in Safari/Chrome, or drag the file onto Netlify Drop to get a normal link.
- If buttons do not work, she is probably inside WhatsApp's viewer. Open it in a normal browser.

## Privacy

Nothing is uploaded while building. Everything lives in the file. The only network call is the optional ntfy alert.
