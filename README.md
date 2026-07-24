# PACE in the Classroom

Built for the **NASA Space Apps Challenge 2024**. The brief was to make data
from NASA's PACE mission — Plankton, Aerosol, Cloud, ocean Ecosystem — legible
to school students rather than to remote-sensing specialists.

PACE measures ocean colour and atmospheric aerosols. The science is genuinely
interesting and the raw data is genuinely unapproachable, so the gap this fills
is a teaching one: give students something they can explore in a browser, and
give teachers something they can actually run a lesson from.

## The site

Six pages, each with a distinct job:

| Page | Purpose |
|---|---|
| `index.html` | Entry point — the mission, and why ocean colour tells you about plankton |
| `mission-control.html` | Walkthrough of the instruments and what each one observes |
| `datalab.html` | Interactive exploration of PACE observations |
| `project.html` | Creative corner — student activities and project prompts |
| `resource.html` | Teacher resources: lesson framing and background reading |
| `about.html` | The team and the challenge entry |

## Running it

Static HTML with no build step and no dependencies. Open `index.html`
directly, or serve the directory if you want a proper origin:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Notes

This is a hackathon artefact and is preserved as submitted. Content about the
PACE mission is drawn from NASA's public materials; NASA imagery and mission
data are in the public domain.

Mission background: <https://pace.oceansciences.org/>
