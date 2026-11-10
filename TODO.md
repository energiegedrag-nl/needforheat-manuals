# TODO – needforheat-manuals

Open work for this repository, distilled from the earlier NeedForHeat backlog at Windesheim, including the discussions on it (paraphrased and regrouped), and from the 2026 maintenance review.

Items that touch several repositories are written out in full in one *lead* repository; the others list them with a link (→). Keep the details up to date in the lead repository only.

## Soon: robustness and correctness

- [ ] → Robust manual server — see [needforheat-manual-server](https://github.com/energiegedrag-nl/needforheat-manual-server/blob/main/TODO.md#msrobust)

## Later: features and ideas

- [ ] <a id="header"></a>**Remove the duplicated header in manuals, FAQ and privacy pages.** Also affects: needforheat-manual-server.
- [ ] <a id="lang"></a>**Language in the path, so relative links work.** The language is encoded in file names, which breaks relative links. Put the language code higher in the content tree and keep file names. Also affects: needforheat-manual-server, needforheat-gearup-app.
- [ ] <a id="manlinks"></a>**Fix links and errors in device manuals.** Fix broken links in the deployment sections (for example to erasing a device) and the HTML issues SonarCloud reported; turn the newer P1 installation manual into a generic template. Also affects: needforheat-p1-reader-firmware, needforheat-living-room-module-firmware, needforheat-presence-detector-firmware, needforheat-boiler-monitor-firmware.
- [ ] <a id="polarity"></a>**Helpdesk chart for thermostat wire polarity and crossover.** Also affects: needforheat-boiler-monitor-hardware.
- [ ] → Finish the rename from Twomes to NeedForHeat — see [needforheat-generic-firmware](https://github.com/energiegedrag-nl/needforheat-generic-firmware/blob/main/TODO.md#rename)
- [ ] → CONTRIBUTING.md with the branching workflow — see [needforheat-generic-firmware](https://github.com/energiegedrag-nl/needforheat-generic-firmware/blob/main/TODO.md#contrib)
- [ ] → Home Assistant as a data source — see [needforheat-server-api](https://github.com/energiegedrag-nl/needforheat-server-api/blob/main/TODO.md#ha)
