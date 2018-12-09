# hello-world
Following the github tutorial is reasonably simple.
However, it focusses on using github, and using git from the 
command line is a different thing. So that is a seaparete
project altogether.
So the flow in the command line is like this:
git clone <url>
cd <new-directory>
git branch more-edits
git checkout more-edits
Make changes to README.md and save
git add README.md
git commit -m "more edits to README.md"
git push --set-upstream origin more-edits

Here you will be asked to sign in to github. In this case it was my own repository which was used, so I could make the sign in. How this works for closed repositories I don't yet know.

git asked me to identify myself, which I did stating my email and full name. This was done using the --global notation, so should work everywhere? At least on this machine. Where is this information stored?

