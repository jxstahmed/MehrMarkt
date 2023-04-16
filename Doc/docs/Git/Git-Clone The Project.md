

### Cloning the project:
<hr/>

#### Fork the repository:
1. visit <a href="https://github.com/Shaco74/SWE-MehrMarkt" target="_blank"> the repository</a>.
2. fork it:
 <img src="../../static/img/Git Clone Tutorial/Fork.png"/>
 
3. uncheck *copy the main branch only*
   <img src="../../static/img/Git Clone Tutorial/copy all branches.png"/>
   (this will create a copy of the project on your github account)
   <img src="../../static/img/Git Clone Tutorial/Fork result.png"/>


#### Clone the fork into your Intellij IDE:

1. Open your Intellij IDE:
 File / New / Project from Version Control
   <img src="../../static/img/Git Clone Tutorial/version control.png"/>
2. under GitHub click on use token
   <img src="../../static/img/Git Clone Tutorial/use token.png"/>
3. Now go to your GitHub account to get the token:
Click on your profile / settings / developer settings / Personal access token / Tokens(classic) / Generate new Token (classic).
**check all the felds and choose No Expiration**
4. Copy the resulted link back into your intellij IDE:
 <img src="../../static/img/Git Clone Tutorial/token.png"/>
<img src="../../static/img/Git Clone Tutorial/cloning from intellij.png"/>
Now you'll see all your repositories. Choose your path below and clone it.
5. Sync the fork: under **Git/GitHub/Sync fork**
<img src="../../static/img/Git Clone Tutorial/Sync fork.png"/>

6. add your Feature Branch:
right click on upstream develop branch -> new Branch from upstream/develop
<img src="../../static/img/Git Clone Tutorial/Feature branch.png"/>
   <img src="../../static/img/Git Clone Tutorial/Feature branch Hello World.png"/>


### Pull request


<hr/>
This is just an example of the future work

1. add a file hello.txt (make sure you're on Feature_Hello_World Branch)
<img src="../../static/img/Git Clone Tutorial/hello.txt.png"/>
2. Commit your changes. Commits are only local changes that will be pushed later into your repository
CTRL + k (Strg + k) 
<img src="../../static/img/Git Clone Tutorial/commit.png" /> 
_adding hello.txt_ is the commit message, it's so important for organizing commits, make sure it's understandable and efficient.
Then **_Commit and Push_**
3. Now when you open your GitHub repository, you'll find this:
<img src="../../static/img/Git Clone Tutorial/compare and pull request.png"/>
This is the pull request, if you click on it, the request will be currently sent to us for checking and approval. 
