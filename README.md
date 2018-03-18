# test-repository
This is a test repository for learning the basics of Git and Github.

cd ~
mkdir test-repository
cd test-repository
echo "# test-repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ctbenergy/test-repository.git
git push -u origin master