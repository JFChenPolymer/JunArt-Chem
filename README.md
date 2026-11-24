# JunArt Chem

Free software for chemistry figures and graphs, from the J. Chen Group (Polymer Chemistry), Department of Chemistry and Biochemistry, University of South Carolina.

Draw chemical structures, reaction schemes and mechanisms, make graphs and curve fits from your data, and lay them out as journal-ready figures. You can export them as PNG, TIFF, PDF, SVG or PowerPoint slides.

## Download (version 2.19.1)

Get the files from the **Releases** page (right side of this page, or the *Releases* link):

| File | For |
|---|---|
| `JunArt-Chem-2.19.1-Windows-x64.zip` | Windows 10 or 11 (64-bit) |
| `JunArt-Chem-2.19.1-Mac-AppleSilicon.zip` | Macs with Apple silicon (M1 or later). Intel Macs are not supported. |
| `JunArt-Chem-2.19.1-Web.html` | Any computer: download it and double-click to open it in a web browser. Nothing to install. |
| `JunArt-Chem-2.19.1-Handbook.pdf` | The user handbook |

## Step-by-step guides with troubleshooting

How to install JunArt Chem and connect it to the Claude and ChatGPT desktop apps, with a troubleshooting table for every common message:

- [**Windows guide (PDF)**](JunArt-Chem-Install-Guide-Windows.pdf)
- [**Mac guide (PDF)**](JunArt-Chem-Install-Guide-Mac.pdf)

## Installing: the security warning is expected

JunArt Chem is free. It is not signed with a paid Apple or Microsoft developer certificate, so Apple and Microsoft do not know who made it. The first time you install it, macOS or Windows warns you about an unverified developer. This is normal for free software from small developers. Allow it **only for files downloaded from this repository's Releases page**.

### Mac

1. Double-click the zip file to unzip it (Safari may already have done this).
2. Double-click **Install JunArt Chem.command**. macOS says it cannot verify the developer. Click **Done** (not *Move to Trash*).
3. Open **Apple menu ▸ System Settings ▸ Privacy & Security**. Scroll down to **Security**, where there is a message about "Install JunArt Chem.command". Click **Open Anyway**, then confirm with **Open Anyway** and your password or Touch ID.
   - On macOS 14 Sonoma and earlier, you can instead right-click the file, choose **Open**, then click **Open**.
4. A Terminal window shows the installation steps, and JunArt Chem opens when it is done. After that, open it from **Applications**. macOS does not ask again.

### Windows

1. Right-click the zip file and choose **Extract All**.
2. In the unzipped folder, double-click **Install JunArt Chem**.
3. If a blue window says **"Windows protected your PC"** (Microsoft Defender SmartScreen), click **More info**, then **Run anyway**.
4. JunArt Chem opens. Later, start it from the Start menu or the desktop shortcut.

Downloaded the Windows version before 24 November 2026? Download it again and install it over the old one: the earlier copy could not connect to the newest Claude app for Windows.

If your institution manages your computer, its IT policy may block apps from unverified developers. In that case, ask your IT office, or use the web version, which needs no installation.

You can check that a download is complete and unchanged by comparing its SHA-256 checksum with the one listed in the release notes.

## Connecting the Claude or ChatGPT desktop app

1. In JunArt Chem, open the **AI** tab and click **Connect** next to **Claude desktop** and/or **ChatGPT desktop**.
2. **Quit that app completely**, then open it again. It reads the new setting only when it starts.
   - **Windows:** closing the window (×) does **not** quit Claude or ChatGPT; they keep running as an icon at the **bottom right of the taskbar**. Click the **^** arrow next to the clock, right-click the app's icon and choose **Quit**, then open the app again from the Start menu.
   - **Mac:** press **Cmd+Q** with the app in front (the red close button only closes the window).
3. Check: in Claude's message box, click **+ ▸ Connectors**; JunArt Chem (junart-chem) is listed and switched on. In ChatGPT: **Settings ▸ MCP servers**.
4. Ask, for example: "Use JunArt Chem to draw caffeine and label it 1."

If Claude says it has no connector for JunArt Chem, the app was almost always closed but not quit: quit it as in step 2 and open it again. This needs the Claude or ChatGPT **desktop** app; the web versions cannot control programs on your computer. More help: the troubleshooting table in the guide for your computer.

## Privacy

JunArt Chem collects no data and has no accounts. Your figures and data stay on your computer.

Some features are optional and send information to other services, under those services' own terms and privacy policies:

- The AI features send your requests to ChatGPT (OpenAI) or Claude (Anthropic), using your own account.
- Structure look-ups by name use PubChem. Only the name, CAS number or InChI is sent, never your structures.

## License

JunArt Chem is free to use under the **JunArt Chem License** ([LICENSE.txt](LICENSE.txt)):

- You may use it for anything, including commercial work.
- You may share unchanged copies free of charge.
- You may not sell it or share changed versions.
- Figures you make with it are yours.

The open-source components it includes are listed in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

## Disclaimer

JunArt Chem is provided free of charge and **"as is", without warranty of any kind**. You use it at your own risk. The authors are not liable for any damage, data loss or error arising from its use. You are responsible for checking every structure, name, calculation, statistic, curve fit, figure and exported file before you rely on it, including in publications, patents, regulatory, safety or clinical work. Output from the optional AI features can be wrong and must be checked in the same way. The installers are not signed or notarized by Apple or Microsoft, so download them only from this repository. ChatGPT, Claude, PubChem and other names mentioned here are trademarks of their owners. They are named only to describe compatibility; no affiliation with, or endorsement by, any company, institution or employer is implied. The full terms are in [LICENSE.txt](LICENSE.txt); where this statement and the license differ, the license applies.

© 2026 Junfeng Chen
