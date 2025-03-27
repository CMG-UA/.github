# CMG-UA Github manual

This is the github page of the Center of Medical Genetics (CMG) from UZA and University of Antwerp. If you are new here and want to collaborate on some projects take a look at these best practises and how our flow is.

more information about the CMG can be found on the [website of CMG](https://www.genetica-antwerpen.be/en/)

## Best Practices

All the code of CMG needs to be placed on Github and not only on the server.

**GITHUB IS NOT A DATA-STORAGE! Nothing larger than 50MB should be commited here.**

- Always try to keep code documented
- Each project has one repository with a dedicated README.md
- Use the special repositories for code that is commenly used

## How to use Github

A nice cheatsheet for reference is the following one [Github education cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf).

### Some commands that you will need:

To make a branch where you can make changes on the code without changing the original:
`$ git checkout -b <branch_name>`

To check the status of your local branch: `$ git status`

To add the changes you have made to github: `$ git add <your_changes>`

To commit the changes after you have added them and give some usefull information about the changes:
`$ git commit -m "<usefull message about what the commit is>"`

To put the changes on the Github page: `$ git push`

### Adding your code to the main branch

When you are done with your branch and you want these to be with the main branch, you need to make a **pull request** on the Github page of CMG.

This can be done by going to the project and the branch your code is one, clicking on **Contribute**, checking compare and then clicking on **Open pull request**.

**NEVER PUSH TO THE MAIN BRANCH!**

### If you have an issue

You can make an issue on the github page by the branch you have to issue on. Try always to be so complete as possible so that the person who is solving the issue has all the necessary information.

Your question will be registered. Don't hesitate to ask questions, these conversations can also be helpfull for other people later on.

You can do this by clicking on the **issue** button next to the code button. Then click on **New issue**.

### Wanting something from another's project 

If you want something from another's project but their hands are tied? Then you can fork the project to make your own copy repo. Update it accordingly and make a pull request of the feature when it is ready.

### Special repositories for commonly used code

If you have code that you think is generic, you should put it in a common library to help your colleagues.

This code needs to be:

- Well-documented (README.md)
- Tested (strongly recommended)

If you want to use a special repositoy, you can submodule these into your own project, this creates something like a soft link to the special repository.

## Collab flow

This is the kind of flow you want to follow when working with GitHub. The chart give a perfect simple overview:

1. Make your own branch from the project
2. Do a git clone local of the branch
3. Make changes to the original code or add your code
4. Add, commit, push changes to your own branch
5. When ready: merge the master branch with your own local version 
6. Fix issues if there are after mergin
7. When fixed: Do pull request with the main branch

![GitHub Flow](https://media.geeksforgeeks.org/wp-content/uploads/20220214111138/GitHubFlow.jpg) (source: https://www.geeksforgeeks.org/git-flow-vs-github-flow/)

Kind regards,  
Bioinformatics team
