# BBK Demo Dashboards

BuiltByKlaw client demo dashboards. One URL — swap the active dashboard per call.

## Dashboards
- `doug-santos.html` — Mortgage pipeline, referral partners, loan tracking
- `ryan-fulmer.html` — Fire & alarm jobs, certificate tracker, compliance alerts
- `griffin-clark.html` — X-Factor events, partnership touchpoints, BBK leads

## To swap for a demo call
Copy the client file to index.html and push:
```
cp doug-santos.html index.html && git add . && git commit -m "demo: doug santos" && git push
```
Netlify deploys in ~60 seconds. Same URL, new content.
