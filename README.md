# nw-site-stats-releases

Built release zips of NetWise Site Stats for NetWise council sites. The source is private; this repo holds no code.

Client sites poll `nw-site-stats.json` on `raw.githubusercontent.com` — not the GitHub API, which is rate-limited per IP and fails silently. See `includes/update-checker.php` in the source repo.
