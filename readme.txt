
osascript -e 'tell application "QuickTime Player" to set rate of document 1 to 0.62'
git add .
git commit -m "first commit before react"
git branch -M main
git remote add origin https://github.com/perlov3301/danilecbootstrap.git
git push -u origin main

echo "# danilec" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tecsun9700/danilec.git
git push -u origin main