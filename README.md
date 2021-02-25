## Github-Bot

Github bots are basically bots that augment the software development process on Github and are formally known as **Github Apps**. 
  * These apps are first-class actors, which means that they can do pretty much anything on Github(one can say that they are at par with a user).

  * Usually, the GitHub apps are built using *Node* or *Python* because of the community support, the availability of tools, and other factors. 
  
  * In this project, we will use a framework for building Github bots called [**Probot**](https://github.com/probot/probot), which utilizes **Node.js**.

## Applications:

 * Made with Probot:

   * Stale – A github app to close stale issues and PRs.
   * Welcome – A github app to welcome new contributors
   * Reminders – Set reminder on issues and PRs

 * Github Marketplace:

   * imgbot – An app to optimize images on github
   * circleci – An app for continuous integration

##Setting up Basic App

 * Step 1: Go to console.
 * Step 2: Create a new folder and name it of your choice.
 * Step 3: Go to the newly made folder.
 * Step 4: Type *‘npx create-probot-app app_name’* in the console to start setting up the basic app.
 * Step 5: Now answer the prompts that appear during the setup. This setup is fairly simple.
