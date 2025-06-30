---
title: "Modus Compare"
description: ""
html_class: "bg-white"
body_class: "gap-3 bg-white"
data_bs_theme: "light"
hide_css_inspector: true
---

| Component | Light Theme                               | Dark Theme                                  | <small>No JS</small>             | <small>No CSS</small>                 |
| --------- | ----------------------------------------- | ------------------------------------------- | -------------------------------- | ------------------------------------- |
| Alerts    | [Classic Light](alerts-classic-light/)    | [Classic Dark](alerts-classic-light/)       | [Test](alerts-classic-no-js/)    | [Test](alerts-classic-dark-no-js/)    |
| Badges    | [Classic Light](badges-classic-light/)    | [Classic Dark](badges-classic-light/)       | [Test](badges-classic-no-js/)    | [Test](badges-classic-dark-no-js/)    |
| Buttons   | [Classic Light](buttons-classic-dark/)    | [Classic Dark](buttons-classic-dark-no-js/) | [Test](buttons-classic-no-js/)   | [Test](buttonss-classic-dark-no-js/)  |
| Chips     | [Classic Light](chips-classic-light/)     | [Classic Dark](chips-classic-light/)        | [Test](chips-classic-no-js/)     | [Test](chips-classic-dark-no-js/)     |
| Dropdowns | [Classic Light](dropdowns-classic-light/) | [Classic Dark](dropdowns-classic-light/)    | [Test](dropdowns-classic-no-js/) | [Test](dropdowns-classic-dark-no-js/) |
| Navbars   | [Classic Light](navbars-classic-light/)   | [Classic Dark](navbars-classic-light/)      | [Test](navbars-classic-no-js/)   | [Test](navbars-classic-dark-no-js/)   |

| Kitchen Sinks                            | Light Theme                                        | Dark Theme                                       | <small>No JS</small> | <small>No CSS</small> |
| ---------------------------------------- | -------------------------------------------------- | ------------------------------------------------ | -------------------- | --------------------- |
| Modus Web Components v1                  | [Classic Light](v1/)                               | [Classic Dark](v1-no-js/)                        | [Test](v1-no-css/)   | [Test](v1-no-css/)    |
| Modus Web Components v2                  | [Classic Light](wc2-classic-light/)                | [Classic Dark](wc2-classic-dark/)                | [Test](wc2-no-css/)  | [Test](wc2-no-css/)   |
| Modus Web Components v2 (with Preflight) | [Classic Light](wc2-classic-light-with-preflight/) | [Classic Dark](wc2-classic-dark-with-preflight/) |                      |                       |

<style>
  table {
    border: 1px solid rgba(128, 128, 128, 0.2);
    max-width: 500px;
    padding: 1rem;
    width: 100%;
    margin-bottom: 2rem;
    margin-left: auto;
    margin-right: auto;
  }
  table td,
  table th {
    padding: 0.5rem;
  }
  table th {
    background-color: rgba(128, 128, 128, 0.1);
  }
  table td:nth-of-type(1) {
   width: 45%;
  }

  table td:nth-of-type(4),
  table td:nth-of-type(5) {
    opacity: 0.6;
    font-size: 0.8rem;
  }
  a[href*="chips"],
  a[href*="dropdowns"],
  a[href*="navbars"] {
    pointer-events: none;
    opacity: 0.5;
    filter: grayscale(100%);
  }
</style>
