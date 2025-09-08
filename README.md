# Cybersecurity website
## University of Uyo — Cybersecurity Program Website

This repository contains the static website for the University of Uyo Cybersecurity Program. The site is a simple informational site (HTML, CSS, and static assets) that describes the program, lists courses and training, highlights research and labs, and publishes news/updates for students and staff.

Key pages included in this repo:

- `index.html` — Home / landing page
- `about.html` — About the program and university
- `programs.html` — Degree and course programs
- `training.html` — Training and short courses
- `research.html` — Research groups and projects
- `digital-labs.html` — Digital labs and facilities
- `updates.html` — News and announcements

This project is deployed on Vercel.

Built with:

- Static HTML/CSS/JS

Running the site locally
------------------------

Because this is a static site there is no build step. Here are three quick ways to run it locally from the project root.

1) VS Code — Live Server (recommended for quick iteration)

	- Install the Live Server extension.
	- Right-click `index.html` and choose "Open with Live Server".

2) Python 3 built-in HTTP server (works if you have Python installed):

```powershell
# from project root
python -m http.server 8000
# open http://localhost:8000 in your browser
```

3) Node.js — http-server (if you prefer Node):

```powershell
npm install -g http-server
http-server -p 8000
# open http://localhost:8000 in your browser
```

Notes
-----
- `package.json` currently has no start script or build step — this is expected for a static site.
- If you want a development script, I can add a small `npm` script that runs a local static server.

Contact & development
---------------------

If you want me to add a local `npm start` script, CI configuration, or a simple `Dockerfile`, say which option you prefer and I’ll add it.

---

Requirements coverage:

- Update the README with a site description: Done
