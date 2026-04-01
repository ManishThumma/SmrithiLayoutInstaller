# Smrithi™ Layout Installer

> *Smrithi (स्मृति) — Sanskrit for "memory" or "that which is remembered."*

**Live site → [manishthumma.github.io/SmrithiLayoutInstaller](https://manishthumma.github.io/SmrithiLayoutInstaller/)**

---

## The Story Behind Smrithi

It started with my dad's US visiting visa.

From the day he applied for his passport to the day he walked into the consulate, I had **sleepless nights**. Not because of the visa process itself — but because of *the documents.*

Every two days it was a new phone call.

*"Nanna, where is my bank statement?"*
*"Amma, where did we keep the property papers?"*
*"I can't find the Aadhaar. Did you scan it? Why didn't you scan it?"*

And if you know desi parents, you already know what came next — somehow, *somehow*, it became **my fault.** A document they last touched in 2013, stored in a shoebox under three sarees and a broken mixer, and I'm the one getting the 11pm phone call about it. Classic.

I was thousands of miles away, watching my dad scramble through stacks of papers, taking blurry photos of documents with his phone flashlight, sending them on WhatsApp one page at a time, in the wrong order, sometimes upside down.

The visa got approved. He's coming soon. And I genuinely cannot wait.

But the sleepless nights during that whole process? I never want to go through that again. So while I'm counting down the days, I built **this** — because the next time around, the documents will be ready before anyone even asks.

So I built **Smrithi.** A clean, thoughtful folder structure you can set up for your parents (or yourself) in under five minutes. Upload it to Google Drive, share it with your family, and the next time your amma can't find the passport scan from 2019 — it's right there. Folder `01`. Alphabetical order. No drama.

Be the responsible child your parents think you already are.

*This one's for every Indian kid abroad who has ever gotten a 2am call about a document that has been missing since before they were born.*

---

## What It Does

One click. One download. A complete, ready-to-use folder structure for organizing every important document in your family's life.

```
Smrithi_Vault/
├── 00-Read Me First/           ← Setup guide, checklist, FAQ, tips
├── 01-Personal Identification/  ← Aadhaar, PAN, Passport, Driving License ...
├── 02-Education/                ← Marksheets, Degrees, Certificates ...
├── 03-Employment & Income/      ← Offer letters, Salary slips, PF ...
├── 04-Finance/                  ← Bank accounts, Investments, Tax returns ...
├── 05-Travel & Visa/            ← Passport scans, Visa docs, Itineraries ...
├── 06-Medical/                  ← Insurance, Lab reports, Prescriptions ...
├── 07-Government Exams/         ← Hall tickets, Scorecards, Forms ...
├── 08-Property & Land/          ← Deeds, Bills, Rental agreements ...
├── 09-Legal & Family/           ← Marriage certificate, Will, PoA ...
└── 10-Emergency & Access/       ← Emergency contacts, Access notes ...
```

Download it. Extract it. Share it. Fill it in. Never get that 2am phone call again.

---

## How to Use

**Step 1** — Go to [manishthumma.github.io/SmrithiLayoutInstaller](https://manishthumma.github.io/SmrithiLayoutInstaller/)

**Step 2** — Click **Download Folder Structure**

**Step 3** — Extract `Smrithi_Vault.zip` anywhere — your computer, Google Drive, iCloud, OneDrive

**Step 4** — Open `00-Read Me First` — there's a setup guide, checklist, FAQ, and tips already inside

**Step 5** — Start scanning and uploading documents into each folder

**Step 6** — Share it with your parents. Sleep peacefully.

---

## What's Inside `00-Read Me First`

The ZIP already comes with these four files:

| File | What it is |
|------|------------|
| `A-Setup Guide.pdf` | Step-by-step walkthrough of the vault |
| `B-SmrithiChecklist.xlsx` | Track which documents you have and which are missing |
| `Frequently Asked Questions (FAQ).pdf` | Common questions answered |
| `Terms & Tips.pdf` | Best practices for scanning, naming, and backing up |

---

## Project Structure

```
SmrithiLayoutInstaller/
├── index.html              # The entire app — UI, logic, and bundled files
├── structure.json          # Every folder path in the vault
├── components/
│   └── assets/
│       └── images/
│           └── logo.png
└── .github/
    └── workflows/
        └── deploy.yml      # Auto-deploys to GitHub Pages on push to main
```

---

## Tech

- Pure HTML, CSS, and JavaScript — no framework, no build step
- [JSZip](https://stuk.github.io/jszip/) for in-browser ZIP generation
- [Inter](https://rsms.me/inter/) via Google Fonts
- GitHub Pages for hosting

---

## License

MIT — free to use, share, and adapt.

---

*Built by [Manish Thumma](https://github.com/ManishThumma) — after one too many sleepless nights.*
