# Kahuto Pacific — Standard Survey Procedures

Single repository serving all survey forms via GitHub Pages.
The root `index.html` is the hub (the page everyone bookmarks).

## Structure
```
index.html                                   Hub — Standard Survey Procedures
lidar-photogrammetry/
  equipment/index.html                        Step 1 — Equipment Checklist
  pre-survey/index.html                       Step 2 — Pre-Survey Checklist
  on-site/index.html                          Step 3 — On-Site Survey Checklist
  post-survey/index.html                      Step 4 — Post-Survey Checklist
```

## Deploy (once)
1. Create a GitHub repo and upload everything here (keep the folders).
2. Settings -> Pages -> Source: main branch, / (root).
3. Hub is then at https://<user>.github.io/<repo>/  -- bookmark that.

## Add a new form later
1. Put the form at  the-service/the-step/index.html
2. In the hub index.html, add one line to the SERVICES array (path + status:'live').
