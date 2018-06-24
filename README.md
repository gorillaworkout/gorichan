# gorichan
About This Site: on progress
Used Tags & Syntaxes : <html></html> 
<head></head>
<body></body>
# Start a new feature
git checkout -b new-feature master

# Edit some files
git add <file>
git commit -m "Start a feature"

# Edit some files
git add <file>
git commit -m "Finish a feature"

# Merge in the new-feature branch
git checkout master
git merge new-feature
git branch -d new-feature
