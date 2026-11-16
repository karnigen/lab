# Lab applications

A collection of small applications and experiments published with GitHub Pages.

## Applications

- [AI Off-Peak Schedule](./ai-offpeak/) — view fixed pricing hours for DeepSeek and Ollama.

## Publish with GitHub Pages

In the `karnigen/lab` repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose the `main` branch and the `/(root)` folder, then save.

After publishing, visit <https://karnigen.github.io/lab/>.

## AI Off-Peak Schedule

The schedule is defined in [ai-offpeak/schedule.json](./ai-offpeak/schedule.json) and published with the site. The chart shows the weekday and weekend schedules, UTC hours, your local time, and the current-time marker.

Chinese public holiday dates are stored in [ai-offpeak/china-public-holidays.json](./ai-offpeak/china-public-holidays.json), a local snapshot of the Nager.Date public API for 2026 and 2027. Update this file as new yearly data becomes available. The dates are shown below the chart; DeepSeek is off-peak all day on those dates. The date matching “TODAY” uses China Standard Time. The holiday list contains public holiday dates, not substitute workdays or full extended holiday periods.

The schedule and holiday calendar are public static files, so they are the same in every browser. They are not editable or personalized in the browser. Times and peak intervals are defined in UTC.
