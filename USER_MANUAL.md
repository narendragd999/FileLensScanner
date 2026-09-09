# FileLens Pro — User Manual & Complete Feature Guide

Welcome to **FileLens Pro**, the ultra-fast, intelligent, local-first search engine and productivity suite for Windows. FileLens Pro combines sub-millisecond file search, deep content indexing, document OCR, conversational Document Q&A, and cable-free instant file sharing to mobile devices.

---

## 📑 Table of Contents

1. [System Overview & Privacy](#1-system-overview--privacy)
2. [Installation & Getting Started](#2-installation--getting-started)
3. [The Floating Search HUD (`Alt + Space`)](#3-the-floating-search-hud-alt--space)
4. [Mastering the 8 Search Modes](#4-mastering-the-8-search-modes)
5. ["Ask FileLens" — Document AI Assistant (`Ctrl + Q`)](#5-ask-filelens--document-ai-assistant-ctrl--q)
6. [Multi-Document & Folder Research (`Ctrl + R`)](#6-multi-document--folder-research-ctrl--r)
7. [Deep Content Search & Document OCR](#7-deep-content-search--document-ocr)
8. [Hindi Typing & DevLys 010 Support](#8-hindi-typing--devlys-010-support)
9. [Instant Local Send — Wi-Fi QR Code File Sharing (`Ctrl + S`)](#9-instant-local-send--wi-fi-qr-code-file-sharing-ctrl--s)
10. [Inline Calculator & Unit Converter](#10-inline-calculator--unit-converter)
11. [Action Command Palette (`Ctrl + K`)](#11-action-command-palette-ctrl--k)
12. [Quick-Launch Tray: Recent Files & Pinned Items](#12-quick-launch-tray-recent-files--pinned-items)
13. [Duplicate File Cleanup](#13-duplicate-file-cleanup)
14. [Windows Explorer Shell Integration](#14-windows-explorer-shell-integration)
15. [Power User Keyboard Shortcuts Cheat Sheet](#15-power-user-keyboard-shortcuts-cheat-sheet)
16. [7-Day Free Trial & License Activation](#16-7-day-free-trial--license-activation)
17. [Troubleshooting & Frequently Asked Questions](#17-troubleshooting--frequently-asked-questions)

---

## 1. System Overview & Privacy

FileLens Pro is designed with a strict **Privacy-First & Local-Only** approach:
- **100% Local File Searching:** Your files, search queries, index data, and documents never leave your computer.
- **Blazing Fast Speed:** Indexes hundreds of thousands of files across all drives in seconds.
- **Real-Time Monitoring:** Automatically updates whenever you save, edit, move, or delete a file — no manual re-indexing required.

---

## 2. Installation & Getting Started

### Standard Windows Setup Wizard (`FileLensProSetup.exe`):
1. Download **`FileLensProSetup.exe`**.
2. Double-click the installer to launch the Setup Wizard.
3. Choose your preferred startup options:
   - **Create Desktop Shortcut:** Puts a shortcut on your desktop.
   - **Start FileLens Pro with Windows:** Keeps your search index automatically synchronized in the background.
   - **Launch Minimized to System Tray:** Runs quietly in the notification area next to the clock.
4. Click **Install**, then **Finish**. FileLens Pro will launch immediately.

### First Launch & Drive Indexing:
1. Open the FileLens Pro main window by pressing **`Alt + Space`** or clicking the tray icon.
2. Select the drives you wish to index (e.g., `C:\`, `D:\`).
3. Click **Start Index**. FileLens scans your entire drive in seconds.

---

## 3. The Floating Search HUD (`Alt + Space`)

The **Floating Search HUD** is your primary everyday launcher and search bar. It floats above whatever program or browser window you are using.

- **Summon:** Press **`Alt + Space`** anywhere in Windows.
- **Type:** Start typing immediately — results appear as you type with zero delay.
- **Navigate:** Use the **`↑`** (Up) and **`↓`** (Down) arrow keys to move between search results.
- **Open File:** Press **`Enter`** to launch the selected file in its default program.
- **Reveal in Explorer:** Press **`Ctrl + Enter`** to open the containing folder and highlight the file.
- **Dismiss:** Press **`Esc`** or click anywhere outside to close the search bar.

### Live Preview Card:
Highlighting any file automatically opens a rich preview card on the right side showing:
- A high-resolution preview/thumbnail
- File metadata (file size, modified date, line count, full path)
- One-click action buttons: **Open**, **Reveal**, **Copy**, **Share**, and **Ask AI**

---

## 4. Mastering the 8 Search Modes

FileLens Pro offers 8 search modes. Switch between them anytime by pressing **`Tab`**, **`Ctrl + M`**, or clicking the mode pills in the top bar:

| Mode | Icon | Best Used For | Example Query |
| :--- | :---: | :--- | :--- |
| **Partial** *(Default)* | ⚡ | Fast substring matching anywhere in filename or path | `inv 2026` finds `Invoice_2026.pdf` |
| **Natural Language** | 🧠 | AI semantic search; finds documents by meaning and concept | `client quarterly tax invoices` |
| **Exact** | 🎯 | Strict character-for-character matching | `"Annual Report 2026.docx"` |
| **Whole Word** | 🔤 | Matches complete isolated words, ignoring fragments | `tax` matches `tax`, not `taxonomy` |
| **Fuzzy** | ✨ | Typo-tolerant search for misspelled filenames | `dcmnt` finds `document.pdf` |
| **Wildcard** | 🌐 | File pattern matching using `*` (any chars) and `?` (single char) | `*.xlsx` or `sales_202?.*` |
| **Regex** | ⚙ | Advanced regular expressions for power users | `^IMG_\d{4}\.(jpg|png)$` |
| **Boolean** | 🔀 | Logical combinations using `AND`, `OR`, and `NOT` | `contract AND NDA NOT draft` |

---

## 5. "Ask FileLens" — Document AI Assistant (`Ctrl + Q`)

Turn any document into an interactive AI assistant that answers questions in plain English:

### How to Use:
1. Highlight any PDF, Word doc, spreadsheet, or text file in search results.
2. Press **`Ctrl + Q`** or click the **Ask AI** button on the preview card.
3. The Document AI panel opens immediately.

### 1-Click Preset Actions:
- **📑 Summarize:** Get an executive summary of the entire document.
- **📊 Key Facts:** Extract numbers, financial figures, dates, and names in a bulleted list.
- **📋 Action Items:** Discover assignments, to-dos, and deliverables mentioned in the file.

### Ask Custom Questions:
Type any question in natural language (e.g., *"What are the payment milestones?"* or *"Does this resume mention Python experience?"*) and press **Enter**. Click **📋 Copy Answer** to paste it anywhere.

---

## 6. Multi-Document & Folder Research (`Ctrl + R`)

Analyze an entire folder or collection of documents at once:
1. Highlight a folder or select multiple files and press **`Ctrl + R`** (or click **Research** in the toolbar).
2. Choose an analysis action:
   - **Synthesize Findings:** Combine key themes across all documents into one summary.
   - **Cross-Doc Comparison:** Compare metrics, clauses, or specs in a side-by-side table.
   - **Audit Inconsistencies:** Automatically identify contradictory figures or dates.
3. **Grounded Citations:** Every claim includes a clickable source citation `[Source: filename.pdf]` that opens the exact file in Windows Explorer.
4. Click **Export Report** to save your research as a Markdown or text document.

---

## 7. Deep Content Search & Document OCR

FileLens Pro searches **inside** your documents, not just their filenames:
- **Supported Formats:** PDFs, Word (`.docx`), Excel (`.xlsx`), PowerPoint (`.pptx`), text (`.txt`, `.csv`, `.md`, `.json`, `.py`, `.html`, etc.), and archives (`.zip`, `.rar`, `.7z`).
- **Optical Character Recognition (OCR):** Automatically extracts text from scanned documents, receipts, invoices, and photos (`.png`, `.jpg`, `.bmp`, `.webp`, `.tiff`). Once OCR has processed the image, you can search for words printed inside the picture just like any text document!

---

## 8. Hindi Typing & DevLys 010 Support

- **On-Screen Devanagari Keyboard:** Click the **अ** icon to open the interactive Hindi keyboard.
- **Phonetic Transliteration:** Type in English (e.g. `namaste`) and get `नमस्ते` automatically.
- **DevLys 010 Support:** Search documents typed in Hindi Remington typewriter fonts used across government offices and courts.
- **Fast Language Cycling:** Press **`Ctrl + T`** in the search box to cycle between: *English* ➔ *Hinglish Phonetic* ➔ *DevLys 010*.

---

## 9. Instant Local Send — Wi-Fi QR Code File Sharing (`Ctrl + S`)

Transfer any file from your computer to an **iPhone**, **iPad**, or **Android** device in seconds:
1. Highlight any file in search results.
2. Press **`Ctrl + S`** or click **📱 Share** on the preview card.
3. A QR code appears on your monitor.
4. Open the **Camera app** on your phone and scan the QR code.
5. Tap the link on your phone screen:
   - Tap **Download File** to save the file to your mobile storage.
   - Or tap **Preview in Browser** to view photos, read PDFs, or stream audio/video directly on your phone!

> **Note:** Your PC and phone must be connected to the same local Wi-Fi router.

---

## 10. Inline Calculator & Unit Converter

No need to open a separate calculator app. Simply type calculations or conversions into **`Alt + Space`**:
- **Math:** `144 * 12`, `(250 * 4) / 5 + sqrt(144)`, `2^10`
- **Data Storage:** `500 MB to GB`, `2 TB to GB`
- **Length & Distance:** `100 m to ft`, `5 miles to km`
- **Temperature:** `100 c to f`, `72 f to c`
- **Currencies:** `100 USD to INR`, `50 EUR to USD`, `1000 JPY to GBP`
- Press **`Enter`** or **`Ctrl + C`** to copy the calculated value immediately.

---

## 11. Action Command Palette (`Ctrl + K`)

Highlight any file in the search list and press **`Ctrl + K`** to access all power actions:
- **Open File** (`Enter`)
- **Reveal in Explorer** (`Ctrl + Enter`)
- **Copy Full Path** (`Ctrl + C`)
- **Copy Filename** (`Alt + C`)
- **Instant Local Send** (`Ctrl + S`)
- **Ask AI** (`Ctrl + Q`)
- **Toggle Pin / Unpin** (`Ctrl + P`)
- **Run as Administrator** (`Ctrl + Shift + Enter`)
- **Compute Hash (SHA-256)**
- **Move to Recycle Bin** (`Del`)

---

## 12. Quick-Launch Tray: Recent Files & Pinned Items

When you summon Floating Search (**`Alt + Space`**) with an empty search box:
- **📌 Pinned Items:** Frequently used files pinned with **`Ctrl + P`**.
- **🕒 Recent Files:** Files recently created, edited, or opened across your computer.
- Press **`Enter`** to launch the top item immediately.

---

## 13. Duplicate File Cleanup

1. Click **Duplicates** in the toolbar or sidebar.
2. Scan any drive or folder to find identical files.
3. Review duplicates side-by-side with file size, modified date, and preview.
4. Select redundant copies and click delete — all files are moved safely to the **Windows Recycle Bin**.

---

## 14. Windows Explorer Shell Integration

Search inside any specific folder right from Windows:
1. Right-click any folder or drive in **Windows Explorer**.
2. Select **"Search with FileLens Pro..."**.
3. Floating Search opens immediately pre-filtered to that folder.

---

## 15. Power User Keyboard Shortcuts Cheat Sheet

| Shortcut | Action Performed | Where Applicable |
| :--- | :--- | :--- |
| **`Alt + Space`** | Open / Summon Floating Search HUD | Global (Anywhere in Windows) |
| **`Esc`** | Close Search HUD or dismiss dialogs | Search HUD |
| **`↵ Enter`** | Open file / Copy calculation result | Search Results |
| **`Ctrl + Enter`** | Reveal file in Windows Explorer | Search Results |
| **`Ctrl + K`** | Open Action Command Palette | Search Results |
| **`Ctrl + Q`** | Launch "Ask FileLens" Document AI | Search Results |
| **`Ctrl + R`** | Launch Multi-Doc / Folder Research | Search Results |
| **`Ctrl + S`** | Open Instant Local Send (Wi-Fi QR Code) | Search Results |
| **`Ctrl + C`** | Copy full file path to clipboard | Search Results |
| **`Ctrl + P`** | Toggle Pin / Unpin from Quick-Launch Tray | Search Results |
| **`Tab` / `Shift + Tab`** | Cycle search mode forward / backward | Search Bar |
| **`Ctrl + M`** | Cycle search mode | Search Bar |
| **`Ctrl + T`** | Cycle typing language (English ➔ Hinglish ➔ DevLys) | Search Bar |
| **`↑` / `↓` Arrows** | Navigate results (auto-syncs preview card) | Search Results |
| **`Ctrl + 1` ... `9`** | Directly open result 1 through 9 | Search Results |

---

## 16. 7-Day Free Trial & License Activation

- **7-Day Trial:** All 20+ Pro features are completely unlocked from the moment you install. No credit card required.
- **Activating Your License Key:**
  1. Open FileLens Pro and click **Settings** ➔ **License**.
  2. Enter your serial key (format: `FLPRO-XXXX-XXXX-XXXX-XXXX`).
  3. Click **Activate License**. Your lifetime license activates immediately.

---

## 17. Troubleshooting & Frequently Asked Questions

**Q: Does FileLens Pro work offline?**  
Yes! Instant search, deep content indexing, OCR, and the calculator work 100% offline.

**Q: Why won't my phone connect to the QR Code link?**  
1. Ensure both your computer and phone are connected to the same Wi-Fi router.  
2. Temporarily disable Mobile Data (4G/5G) on your phone so it searches via local Wi-Fi.  
3. If Windows Firewall blocks access, click **1-Click Fix** inside the Share window.

**Q: How do I rebuild the search index?**  
Open Settings ➔ Indexing ➔ click **Rebuild Index**.

**Q: Need help or customer support?**  
Contact us anytime at **filelenspro@gmail.com**.
