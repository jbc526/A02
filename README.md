# A02

<body>

<strong>GitHub</strong> is an online platform where users will have the opportunity to store, share, and collaborate on code. If your document is lost or serious bugs are introduced, GitHub will allow you to to revert to the previous version. 

GitHub uses <strong>Git</strong> which is a version control system that allows you to track differences and changes made in files which are uploaded to or downloaded from GitHub for storage and collaboration. 

To create a GitHub account, visit the website https://github.com to sign up for GitHub using your email address and creating your own password! 

Once you have your new GitHub account, click the plus sign icon on the top right corner of the page and click "New Repository". This is where you will enter a <strong>repository</strong> name, add a description of your new repository (optional), and either set your repository as "Public" or "Private". Lastly, checkmark the "Add a README file" under "Initialize this repository with:" and click Create Repositiory at the bottom of the page. 

To install Git on your desktop, it will depend on the operating system of your desktop whether it is Linux, MacOS, or Windows, as the process of installing git will be different. Visit the website https://git-scm.com/book/en/v2/Getting-Started-Installing-Git and follow the instructions based off of your specific operating system. 

For any operating systems, in order to verify if you have successfully installed git, you can open the command line terminal and type in <i>git --version</i>. 

Next, you can, of choice, either download Webstorm at https://www.jetbrains.com/student/ or Visual Studio Code at https://code.visualstudio.com/download .
I use Visual Studio Code, which is an IDE where developers can write, test, and debug code. If you do decide to use Visual Studio Code, download from the link above. Once you have it installed, open the software and it will lead you to a welcome page. 

Under the start heading, click on <strong>Clone</strong> Git Repository and a search bar will pop up on the top of the page. This is where you can provide the URL to the repository you have created, allow you to pick a repository source, or click on the "Clone from GitHub" button. If you click the "Clone from GitHub" button, you will see the urls to your repositories and click/search which repository you want to use. After you click on your repository, the README.md file will pop up. Add any details/information you'd like to the README.md file. 

Next, open the terminal within Visual Studio Code. 

To verify if you can see the modified file, 
type in <i>git status</i>.

To add the changes to the local repository and to verify the command was successful, type in <i> git <strong>commit</strong> -a -m "Updated README.md"</i>. 

Last but not least, to <strong>push</strong> the local content to GitHub. 
type in <i>git push</i>. You should be able to see the changes are updated in GitHub! 

<h3>Definitions</h3>
Branch - A parallel or separate version of the main repository. 

Clone- To make a copy of a repository from a remote source like Github 

Commit- A snapshot along the timeline of a Git project and will have message describing the changes. 

Fetch- The command that will commit or recieve the changes.updates from remote repository into your local repository. In other words, you will see what others have been working on. 

Git- Version control system that allows you to track differences in files. 

GitHub- Cloud-based platform where users will have the opportunity to store, share, and collaborate on code. 

Push- Push command will allow you to upload local repository content to remote repository. 

Pull- Downloads the content from a remote repository and update the local repository to match the remote repository content. It will copy from remote repo directly into working directory. 

Repository- Like an online storage space for any files such as your codes which will keep everything organized and tracks all the changes you make. 

Remote- A shared repository amongst a team to exchange their changes.  

Merge- Places together the changes from different branches into one. 

Merge Conflict- An event whereas Git cannot solve the differences in code between two commits. 

Directions References: 
1.https://docs.google.com/presentation/d/1u3bTSQd_LApYwtuWcQ-UDXqrz0RTVaNNtV51UM0Myv4/edit#slide=id.g2fd649dd694_1_0 
(SLIDES FROM IT 202 PROFESSOR ROSEMINA VOHRA)
2.Intro to GitHub-20190218.pptx (Slides from Canvas Files in Week 03)

Definition References: 
1.https://www.w3schools.com/git/git_branch.asp?remote=github
2.https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
3.https://www.atlassian.com/git/tutorials/saving-changes/git-commit#:~:text=Commits%20can%20be%20thought%20of,committed%20to%20the%20local%20repository.
4.https://www.atlassian.com/git/tutorials/syncing/git-push#:~:text=The%20git%20push%20command%20is,exports%20commits%20to%20remote%20branches.
5.https://www.git-tower.com/learn/git/glossary/remote#:~:text=A%20remote%20in%20Git%20is,of%20the%20project's%20current%20state.
6.https://www.git-tower.com/learn/git/glossary/remote#:~:text=A%20remote%20in%20Git%20is,of%20the%20project's%20current%20state.




</body>