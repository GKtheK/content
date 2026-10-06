# content

**This repository is public.** Anything committed and pushed here is
visible to anyone on the internet, and stays in git history even after it's
deleted. Only put files here that are meant to be publicly reachable by URL
(e.g. an image linked from an email or web page).

- Never commit credentials, `.env` files, client data, reports, or work in
  progress — those belong in a private repo.
- Before pushing, check `git diff --cached --stat` and confirm with the
  user that every file is meant to be public.
- There is no build, test, or deploy step; files are served as-is from
  GitHub.
