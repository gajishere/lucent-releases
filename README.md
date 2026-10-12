<p align="center">
  <img src="assets/lucent-banner.jpg" alt="Lucent — Your papers. Your path to understanding. A glass book with a blue ribbon." width="100%">
</p>

<p align="center">
  <strong>A personal study guide built around your actual exams.</strong><br>
  Turn past papers into connected explanations, worked solutions, and a place to ask questions.
</p>

<p align="center">
  <a href="https://github.com/gajishere/lucent-releases/releases/latest"><img src="assets/download-windows.svg" alt="Download Lucent for Windows" width="280" height="54"></a>
</p>

<p align="center">
  Windows 10 / 11 · 64-bit · No GitHub account needed<br>
  <sub>Runs on your computer. Opens in your browser.</sub>
</p>

<p align="center">
  <a href="#study-from-your-own-papers">Explore Lucent</a> &nbsp; · &nbsp;
  <a href="#get-started">Get started</a> &nbsp; · &nbsp;
  <a href="#keep-lucent-up-to-date">Updates</a> &nbsp; · &nbsp;
  <a href="https://github.com/gajishere/lucent-releases/releases">Release notes</a>
</p>

---

## Study from your own papers

Bring your past exam papers, then add lecture notes, a syllabus, or an answer key for context. Lucent helps turn that material into a study guide you can keep building on.

| Follow the material | Make it yours |
| :--- | :--- |
| **One connected guide.** Read from foundations to worked solutions in a continuous document, with chapter jumps when you need them. | **Ask where you're stuck.** Ask about a sentence, equation, or step. Your conversation stays attached to that passage. |
| **Stay connected to the source.** Review the question inventory and follow questions back to their original papers. | **Keep useful explanations.** Add an AI answer to your guide as an editable clarification without losing the conversation. |
| **Study in your own rhythm.** Reopen saved guides offline, track your place, or export a printable copy. | **Choose your setup.** Connect ChatGPT or Claude, choose a teaching profile, and switch between light and dark themes. |

The interface supports **English and Bahasa Indonesia**. You can choose the teaching language for each guide.

## Get started

1. **Download and install.** Open the [latest release](https://github.com/gajishere/lucent-releases/releases/latest), expand **Assets** if needed, and download the file named `Lucent-Setup-<version>.exe`. Run the setup wizard.
2. **Connect your AI account.** Open Lucent from the desktop or Start menu shortcut, then choose **Connect ChatGPT** or **Connect Claude** in Settings.
3. **Bring your papers.** Create a course, upload PDFs or photos, and choose **Analyse papers**. Review the question inventory, then select **Build my study guide**.

No terminal commands, Node.js installation, or separate Claude Code setup are needed. For Claude, Lucent prepares the official local runtime when needed; the first connection adds a download of about **244 MB**.

> **Before you install:** Lucent currently supports Windows 10/11 x64. The installer is not yet Windows code-signed, so Windows may display an unknown-publisher or SmartScreen warning. Download it from this repository's Releases page.

## Keep Lucent up to date

From **version 0.2.0**, open **Settings → App updates**:

**Check for updates → Download update → Update and restart**

Lucent verifies the download and waits until active work has finished before installing. Your saved courses and study materials stay in their existing folder.

**Coming from an older version?** Exit Lucent from its tray icon, then run the latest setup once. After that, future releases can be installed inside Lucent.

## Your workspace stays with you

Your papers, guides, and notes are saved on your computer. Saved guides remain readable without an internet connection.

AI features need internet access and a connected account. Material needed for an AI request is sent to the provider you choose. Requests use that account's available allowance and usage settings; connecting Lucent does not create a separate or unlimited AI quota.

## A few useful answers

<details>
<summary><strong>Which release file should I download?</strong></summary>

Choose the `.exe` installer under **Assets**. The `.sha256` file is a checksum, and `latest.json` is used by Lucent's updater. GitHub's **Source code** archives are not the Windows app.

</details>

<details>
<summary><strong>Where does Lucent save my work?</strong></summary>

By default, in `%LOCALAPPDATA%\Lucent` on Windows. If you use a custom data folder, it stays there. Updates preserve your data. You can create a backup from **Settings → Back up now**.

</details>

<details>
<summary><strong>Does closing the browser quit Lucent?</strong></summary>

Lucent stays in the Windows system tray. Use the tray icon to reopen it, or right-click the icon and choose **Exit Lucent** to stop the app.

</details>

<details>
<summary><strong>Can I use it without an AI connection?</strong></summary>

You can read saved guides offline. Analysing new papers, building guides, and asking AI questions require internet access and a connected ChatGPT or Claude account.

</details>

<details>
<summary><strong>What if an explanation looks wrong?</strong></summary>

AI can misread a symbol or make a reasoning mistake. Review the paper analysis before building, and compare important steps with your course material or answer key. Lucent keeps the source questions close so you can check them.

</details>

---

<p align="center">
  <strong>Start with the papers you have. Build the understanding you need.</strong><br><br>
  <a href="https://github.com/gajishere/lucent-releases/releases/latest">Download the latest release</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/gajishere/lucent-releases/issues">Report a problem</a><br>
  <sub>This repository is Lucent's public home for Windows downloads and release notes.</sub>
</p>
