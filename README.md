# Jinxin Future — Official Website

The official site for **Jinxin Future** (品牌：瑾欣未来科技有限公司 / Jinxin Future Technology Co., Ltd.).

- Live: https://jinxinfuture.online
- Brand: "Building products for the age of AI."

## Pages

| Path | Page |
|------|------|
| `/` | Home — brand statement, core question, explorations, journal teaser, contact |
| `/products/` | ZIJI — AI writing companion (用文字，看见真实的自己) |
| `/about/` | About — legal entity, mission, leadership |
| `/contact/` | Contact — email + registered entity details |
| `/privacy/` | Privacy Policy (ZIJI) |
| `/terms/` | Terms of Use (ZIJI) |

## Stack

Static HTML + one `css/style.css` design system (black / white / grey + a single restrained accent).
No build step. Deployed via GitHub Pages from the `main` branch.

## Design system

- Accent: `#635bff` (used sparingly — links, the core-question emphasis, footer marks)
- Type: Inter (UI) + Instrument Serif (display/editorial moments)
- Logo + wordmark in the nav; monochrome treatment so it reads on white
- Sections reveal on scroll (progressive enhancement — fully visible without JS)

## Notes

- `.workbuddy/` is local agent memory and is gitignored.
- Before submitting to Apple: fill the real **registered address** and **phone** on `/contact/`,
  and set the **effective dates** on `/privacy/` and `/terms/`.
- D-U-N-S is intentionally NOT published on the site (it is for Apple identity verification only).
