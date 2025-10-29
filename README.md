How to update the official repo (forgedcreativex)

You need to push explicitly to upstream:

git add .
git commit -m "Your commit message"
git push upstream main


This will push your changes to the official repo.

Meanwhile, git push or git push origin main will only push to your backup repo.

✅ Workflow summary

Update personal backup (optional):

git push origin main


Update official repo:

git push upstream main
