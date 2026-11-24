# ufh-bench-runner

Runs the UFH layout benchmark (up to 144 runs) on GitHub's free runners, 20 at a time.

This repo holds only the workflow. The code, the floor plans and the results live in a private repo, which the workflow reaches
with a secret token. Each run's output is encrypted before it is stored, and the log shown here has one line per run.

Start it from **Actions -> UFH benchmark -> Run workflow** (people with write access to this repo only).
