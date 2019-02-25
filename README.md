# Lambda-Git-Flow-for-Dummies-My-Own

Create YOUR OWN version of Repo ---> (Fork)

Add your PM as collaborator

on GitHub:
Settings -> Collaborators -> Add Collaborator (use your PM's handle)
(I'd suggest grabbing the invite tag and DM it to your PM on Slack at this point)

Clone YOUR Repo

back on your machine:
git clone <your-repo-address>

Create a branch (the one you are going to be working on)

cd <repo directory>
git checkout -b 'firstname-lastname'

Push your new branch up to GitHub and make all future pushes to that branch

git push -u origin firstname-lastname

on GitHub:
Compare & Pull Request -> Base: YOUR MASTER (Not the Lambda Master)
compare fork: YOUR FORK

Add your PM as a reviewer on the Pull Request

On the 'Open a Pull Request' page click on Reviewers. If your PM has accepted your invite, then you should be able to select them here. If not, then they haven't accepted the invite, and come back later...

Your PM will merge the work into YOUR Master fork when they have reviewed and approved it.
