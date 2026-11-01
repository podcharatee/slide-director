# Tools by need

Use what is already available. Recommend anything else, and install it only after the owner agrees. Check each tool's current docs, prices and limits, because they change.

| Need | Options | Watch out for |
|---|---|---|
| HTML deck, design direction | [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design), [frontend-slides](https://github.com/zarazhangrui/frontend-slides) | Neither handles Thai by itself |
| Render pages, check overflow, export PDF | [Playwright](https://playwright.dev/docs/intro) with Chrome | A pass does not mean the page looks good |
| Cut clips, make loops, join rehearsal video | [FFmpeg](https://ffmpeg.org/about.html) | Zoompan on a still image can shake |
| Animate or sharpen a real photo | [Higgsfield CLI](https://github.com/higgsfield-ai/cli) or another image-to-video tool | Costs credits; compare every clip with its source |
| Read the script aloud for timing | [ElevenLabs](https://elevenlabs.io/docs/overview/intro) or another voice tool | Check Thai support per model; a cloned voice needs consent |
| Work in Canva | [Canva connector](https://www.canva.dev/docs/connect/canva-mcp-server-setup) | See the Canva notes below |
| Drive a desktop app when no connector can | [Cua Driver](https://github.com/trycua/cua) | High privilege; use a separate machine when possible |
| Read files from Google Drive, Google Slides or Figma | The matching connector for your AI app | Not field-tested with this skill |
| Fast first draft or editable .pptx | Gamma or Moda connector | Not field-tested with this skill |

## Destination notes

### Canva

Observed through the Canva connector in October 2026. Test again, because this may have changed.

- Images upload through the connector. Video files were rejected, so upload video in the Canva app.
- Transitions and animation could not be set through the connector. Set them in the app.
- A web deck does not carry over as it is. Plan to rebuild transitions and video loops.
- To swap an image, delete it and insert the new one at the exact position. Updating the fill added a slight crop.
- Canva's default face rendered Thai cleanly in editable text.

### PDF

- Give every HTML video a poster image, or the page exports as black.

### PowerPoint and Google Slides

Not field-tested with this skill. Build one test page in the real app before making the whole deck, and check the Thai font first.

## Before installing a third-party skill

Read all of its files first. Decline it if it locks the palette against the brand, turns telemetry on by default, updates itself, overwrites other skills or reads login data.
