#GIT
git add .
git commit -m "Prepare release v1.0.0"
git push origin main


git tag -a v1.0.0 -m "Release v1.0.0"
git push origin v1.0.0