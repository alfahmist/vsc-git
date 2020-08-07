# vsc-git
bikin git dari visual studio code

more info : https://code.visualstudio.com/docs/editor/github

1. Install

Untuk lihat file yang akan di commit(perubahan), stage, dan sudah di commit <br>

Name: GitHub Pull Requests and Issues <br>
Id: github.vscode-pull-request-github <br>
Description: Pull Request and Issue Provider for GitHub <br>
Version: 0.18.0 <br>
Publisher: GitHub <br>
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github <br>

(optional) 

plugin GUI untuk lihat Repository, File History, Line History, Compare Commit, Search Commit  <br>

Name: GitLens — Git supercharged <br>
Id: eamodio.gitlens <br>
Description: Supercharge the Git capabilities built into Visual Studio Code — Visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate <br> and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more <br>
Version: 10.2.2 <br>
Publisher: Eric Amodio <br>
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens <br>

2.  setting email dan nama

$ git config --global user.name "John Doe"

$ git config --global user.email johndoe@example.com <br>


echo "# a" >> README.md <br> <br>
git init <br>
git add README.md <br>
git commit -m "first commit" <br>
git remote add origin https://github.com/alfahmist/a.git <br>
git push -u origin master<br>
