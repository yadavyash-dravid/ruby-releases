# Ruby: accounting, inventory and invoicing that stays on your computer

Ruby keeps your books on **your own computer**, works without the internet, and adds what older accounting software does not: approvals so staff cannot slip, a trust score for every customer, automations that watch your books, and AI that reads your supplier bills.

This page is where you download it.

## Download (latest version)

| Your computer | File |
|---|---|
| **Mac with an Apple chip** (M1, M2, M3, M4…) | `ruby-<version>-mac-arm64.dmg` |
| **Mac with an Intel chip** | `ruby-<version>-mac-x64.dmg` |
| **Windows 10 or 11** (64-bit) | `ruby-<version>-win-x64.exe` |

Find the newest files under **Releases** on this page. Not sure which Mac you have? Apple menu → **About This Mac**: "Chip: Apple M…" means the Apple chip file; "Processor: Intel…" means the Intel file.

**Needs:** macOS 12 (Monterey) or newer, or Windows 10/11 64-bit. About 400 MB free space plus room for your books.

## First launch: the warning is expected

Ruby is from a small company and is not signed with the big companies' paid certificates yet, so your computer warns you the first time. **Step-by-step pictures and instructions: `INSTALL-GUIDE.md`.** In short:

- **Mac:** open Ruby, click Done on the warning, then **System Settings → Privacy & Security → Open Anyway**.
- **Windows:** on the blue "Windows protected your PC" box, click **More info → Run anyway**.

## Check your download (optional, takes a minute)

Each release lists a **checksum** (a fingerprint) for every file in `SHA256SUMS-mac.txt` and `SHA256SUMS-win.txt`. After downloading, compare:

- **Mac** (Terminal): `shasum -a 256 ~/Downloads/<file>`
- **Windows** (PowerShell): `Get-FileHash $HOME\Downloads\<file>`

If the long code does not match the one in the release, do not install it, and tell us.

## You need a licence

After installing, open Ruby → **Plugins** → **Install licence file…** and choose the `.erplic` file we sent you. To ask for a free 14-day trial, contact us.

## Help

**Contact us through [thesuperintelligence.school](https://www.thesuperintelligence.school)** with your Licence ID and a photo of any message you see.

Terms, privacy and refund policy: on the same website.
