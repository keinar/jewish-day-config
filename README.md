# jewish-day-config

The "Jewish Day" app reads `dedications.json` from this repository. Edit it here on GitHub, and installed apps update within about 3 hours, with no new release.

- `dedications`: `text`, `from`, `to` (dates in `YYYY-MM-DD` format, inclusive). All active dedications are shown, the shortest first.
- `offers`: the dedication buttons (`period`: day / week / month, `title`, `price`, `url` starting with `https://`).
- A broken line is skipped. If the file isn't valid JSON, the app keeps the last copy it received.
