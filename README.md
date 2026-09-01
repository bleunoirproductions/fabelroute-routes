# Fabelroute routes

Test hosting for finished Fabelroute routes, one folder each, served by GitHub
Pages at `https://bleunoirproductions.github.io/fabelroute-routes/<route>/`.

**Temporary.** Routes belong at `https://routes.fabelroute.com/<route>/` once
that hosting is set up; this repo exists so the download, the page and the QR
can be walked through against a real host in the meantime. Every address here
is baked into a QR image, so anything printed from this repo has to be
reprinted when the routes move.

Each folder is exactly what `Tools/publish-route.sh` in the Fabelroute repo
writes: `route.json` and `audio/` as the Editor exported them, plus the
route's own page and its QR. The recipe is `docs/publishing-a-route.md` there.

`.nojekyll` stops GitHub from running Jekyll over it, which would otherwise
decide for itself which files are worth serving.
