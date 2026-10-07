# Workspace Wall: mock-up

Clickable mock-up of a smart-display dashboard that shows one tile per meeting room, with environmental metrics (temperature, humidity, TVOC index, noise) and space utilization (people count, use today, ghosted meetings) from Cisco Spaces and Webex RoomOS devices.

**Live page:** https://ciscocollabai.github.io/workspace-wall/

- **All data is simulated.** "Westpark Office" and its rooms are fictional, and the page makes no external requests.
- The comfort ranges are Cisco's "excellent" values from *[Utilization and environmental metrics for workspaces](https://help.webex.com/article/nc6od6r)*.
- The filters (workspaces, floor, condition, metrics, per-tile settings) are saved only in your browser.

## Files
- `mockup/index.html`: the page (vanilla JS, no dependencies)
- `mockup/fonts/`: Barlow, self-hosted, SIL Open Font License 1.1 (`OFL.txt`)
- `.github/workflows/pages.yml`: publishes the page to GitHub Pages on every push to `main`
