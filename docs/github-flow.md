# Create a Branch
![Create a branch](https://lucamezzalira.files.wordpress.com/2014/03/screen-shot-2014-03-08-at-23-07-361.png?w=650&h=230)

When you're working on a project, you're going to have a bunch of different features or ideas in progress at any given time – some of which are ready to go, and others which are not. Branching exists to help you manage this workflow.
When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the master branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.
# Add Commits
![Add Commits](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8GGkZMiXUwrFkmUBHKWDfqSL10B77zn6Fsk7Xlz5FqD4KrTNT)

Once your branch has been created, it's time to start making changes. Whenever you add, edit, or delete a file, you're making a commit, and adding them to your branch. This process of adding commits keeps track of your progress as you work on a feature branch.Commits also create a transparent history of your work that others can follow to understand what you've done and why. Each commit has an associated commit message, which is a description explaining why a particular change was made. Furthermore, each commit is considered a separate unit of change. This lets you roll back changes if a bug is found, or if you decide to head in a different direction.

# Open a Pull Request
![open a pull request](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBpIKxMVNNwqL_pz4ZnIBJ0CRnR6chrckgH1tBHPOfbKLx0q6P)

Pull Requests initiate discussion about your commits. Because they're tightly integrated with the underlying Git repository, anyone can see exactly what changes would be merged if they accept your request.You can open a Pull Request at any point during the development process: when you have little or no code but want to share some screenshots or general ideas, when you're stuck and need help or advice, or when you're ready for someone to review your work. By using GitHub's @mention system in your Pull Request message, you can ask for feedback from specific people or teams, whether they're down the hall or ten time zones away.

# Discuss and review your code
![Discuss and review your code](Data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAXYAAACHCAMAAAA1OYJfAAABU1BMVEX////x8fHD1+zm7vfS4fFxnc9ckMrSqMOTLXD6+vr06/HcvdH5+fn19fVBg8Tu7u7n2OHRs8Xu4+mFAFuPIGsddL6+j6vo6Ojz9/u6z+eKAGIYcr3d6PTv9PosesCWt9wzfcKwc5iEq9azyuWlweDh6/X/+fBjl83v6+WYudydpsc8h8y53vKKr9hrptrC1eq2trbW1taSkpLgyNd3pNO5gKTIyMjL5faotdOgT4JKiMarZ5GPUpOOM3n97Nz23cyztsqxXnPYtraGmsevkLa/udumfardwMCSFWCwnMh4kcVjicPZ8/vfvbSSJGXq0cbIyuD///FbiriAkMOeyuy/d32ebo7Ol5SMI3TOpam6pcOhRnqYUn6VZ6GfSYClWYnNnr3EjJODM4O5coGkR2rIt9LHmqyYKmKNlMJZfcFAkM/k/P+dQm+hcKGaW5N/AEp/AGWIp5bxAAAMbklEQVR4nO2da2ObRhaGEQJsyRZWJI/DdYQFFpETRduKNDFuEjdO0tRuLm3SzW032bTJtk27u/3/n3YYdAckNAIkS/N8sK1hGNDL4cyZMwxmmGlIuq4Xptai+HhqSXO3otcEA6jQddgETmn1MXkRqlC0rfmUbwGDt+S2VXdV4SChU1tdWBG4LattNm0ILfJmJBu09O7fpgipwU/GUl2u+6fGA4e4HdcYUloSVC66KgWpXh/61CTW3QEjOhdcQ4+qSmE4dVRnC5D5GQ7vd2L3r6EO6hOqrzuCyzCNU/tav8CBRP0qL6IfP/DMg++ZkoxbqKnU3KNgQZthvrrGnPVLDmCToJ0CqHm/Dk1HavBtGzekmsmc4wpSh+hH0TmpDYp4IVCL03p3ABeB6Xv2K+o15kqN+Q1Xd3ktqvq64/KeQCfgxUBjy2DHa7EILu9pyUZQA/me7MyJ6LdmC1xU9XXHwGZ+YkAZ/fJH9TI0o2ofRMreAtJAdug7dd5N55xXAD9uOYG86rRvtRxPOxSThNflkJr5cHQT4GHpFWCZh70Qxrb1iOprj9HCsqvIM6g28+kmtnZuvpen a pull request](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBpIKxMVNNwqL_pz4ZnIBJ0CRnR6chrckgH1tBHPOfbKLx0q6P)

Once a Pull Request has been opened, the person or team reviewing your changes may have questions or comments. Perhaps the coding style doesn't match project guidelines, the change is missing unit tests, or maybe everything looks great and props are in order. Pull Requests are designed to encourage and capture this type of conversation.You can also continue to push to your branch in light of discussion and feedback about your commits. If someone comments that you forgot to do something or if there is a bug in the code, you can fix it in your branch and push up the change. GitHub will show your new commits and any additional feedback you may receive in the unified Pull Request view.

# Deploy
![merge](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBpIKxMVNNwqL_pz4ZnIBJ0CRnR6chrckgH1tBHPOfbKLx0q6P)

Once your pull request has been reviewed and the branch passes your tests, you can deploy your changes to verify them in production. If your branch causes issues, you can roll it back by deploying the existing master into production.
# Merge
![merge](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBpIKxMVNNwqL_pz4ZnIBJ0CRnR6chrckgH1tBHPOfbKLx0q6P)

Now that your changes have been verified in production, it is time to merge your code into the master branch.Once merged, Pull Requests preserve a record of the historical changes to your code. Because they're searchable, they let anyone go back in time to understand why and how a decision was made.
