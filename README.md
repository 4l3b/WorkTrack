# WorkTrack

**WorkTrack** is a browser-based tool for recording daily work sessions.

<img src="worktrack.png" alt="WorkTrack interface" width="35%">

---

## Features

- Log expected work duration, expected break duration, and clock-in time
- Calculates:
  - Expected clock-out time
  - Remaining time in the workday
- Adjusts calculations if:
  - A session ends early
  - Work continues into overtime
- Stores session data locally, so it persists across page reloads
- JSON export/import:
  - Download a log of your work history
  - Upload a previous log
  - Clear stored data
- Cockpit-style UI modeled after the Flight Management Computer of the iconic McDonnell Douglas MD-11 aircraft

Example JSON log output:
```json
{
  "07-01-2025": [
    {
      "clockIn": "08:51:31",
      "clockOut": "17:21:11",
      "workTime": "08:00:02",
      "breakStart": "13:27:26",
      "breakEnd": "13:57:04",
      "breakTime": "00:29:38"
    }
  ]
}
```

---

## Tech Stack

- **HTML**: Structure
- **CSS**: Styling
- **JavaScript**: Time calculations, data storage, and JSON export/import

---

## Usage

Open the app on the [GitHub Pages site](https://4l3b.github.io/WorkTrack/) to launch it in your browser. The app runs as a popup, and instructions for logging work sessions, tracking breaks, and exporting/importing JSON logs are available within the launching interface.

---

WorkTrack © 2025 by Alessandro Bigolin - [CC BY-NC-SA 4.0].

See LICENSE file: [https://github.com/4l3b/WorkTrack/blob/main/LICENSE].
