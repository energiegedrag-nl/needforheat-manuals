# NeedForHeat manuals

This repository contains the manuals, FAQs, information pages and privacy statements shown by the NeedForHeat app. They are served by [needforheat-manual-server](https://github.com/energiegedrag-nl/needforheat-manual-server), with this repository as its source.

> **Own deployment.** This repository is maintained by [energiegedrag-nl](https://github.com/energiegedrag-nl) and served at `manuals.energiegedrag.nl`. To run your own instance, fork it, replace `energiegedrag-nl` by your GitHub organisation and `energiegedrag.nl` by your domain, and fill in the campaign fields below.

## Campaign texts are templates

The pages under [`campaigns/generic`](campaigns/generic) are an **organisation- and domain-independent example**. They contain fields in double braces that you replace (search for `{{`) before you use them, preferably in a copy named after your own campaign (`campaigns/<your-campaign>`):

| Field | Meaning | Example |
|---|---|---|
| `{{ORGANISATION}}` | organisation that runs the campaign and is the data controller | Example Energy Cooperative |
| `{{CAMPAIGN_NAME}}` | name of the measurement campaign | NeedForHeat Winter 2026 |
| `{{DOMAIN}}` | internet domain of your servers | example.org |
| `{{CONTACT_EMAIL}}` | helpdesk e-mail address | helpdesk@example.org |
| `{{DPO_CONTACT}}` | data protection officer, if any | dpo@example.org |
| `{{PURPOSE}}` | purpose of the campaign, one or two sentences | |
| `{{VERSION_DATE}}` | date of the privacy statement | 1 December 2026 |
| `{{HOSTING_PROVIDER}}`, `{{BACKUP_PROVIDER}}`, `{{OTHER_PROCESSORS}}` | processors you use | |
| `{{RETENTION_PERIOD}}`, `{{WAITING_PERIOD}}` | retention of the pseudonym link; waiting time before publishing open data | 5 years; 3 months |
| `{{GITHUB_ORG}}` | GitHub organisation that hosts your copy of the source | energiegedrag-nl |

The privacy statements are a starting point, not legal advice: have them reviewed by your own data protection officer (and, for research, an ethics committee) before publishing.

## What changed compared to the original

- The REDUCEDHEATCARB 2023 campaign of Windesheim University of Applied Sciences, including its ethics approval, is not part of this repository. It remains available in the [original repository](https://github.com/energiegedrag-nl/needforheat-manuals). Questions about that campaign, or any other earlier Windesheim measurement campaign, should go to Windesheim.
- All `@windesheim.nl` contact addresses were removed; campaign pages use `{{CONTACT_EMAIL}}` instead. (Own `@energiegedrag.nl` addresses will follow once mail is set up.)

## License

This content is available under [CC BY 4.0](./LICENSE.md). It is based on the original manuals by the [Research group Energy Transition, Windesheim University of Applied Sciences](https://windesheim.nl/energietransitie).

## Citation

If you use this repository in your research or work, please cite the following pre-print, which describes the overall NeedForHeat DataGear system of which this repository is a part:

> Ter Hofte, H., & van Ravenzwaaij, N. (2025). *NeedForHeat DataGear: An Open Monitoring System to Accelerate the Residential Heating Transition*. arXiv preprint arXiv:2509.06927. https://doi.org/10.48550/arXiv.2509.06927

## Credits

Author:
* Henri ter Hofte · [@henriterhofte](https://github.com/henriterhofte)

This repository continues [energietransitie/needforheat-manuals](https://github.com/energiegedrag-nl/needforheat-manuals). Thanks to the authors of the original:
* Nick van Ravenzwaaij · [@n-vr](https://github.com/n-vr)

### AI assistance

Since November 2026, parts of the maintenance of this repository have been done with [Claude Code](https://claude.com/claude-code) (Anthropic), under the author's direction and review. Commits made this way carry a `Co-Authored-By: Claude …` trailer. The author remains responsible for all content.
