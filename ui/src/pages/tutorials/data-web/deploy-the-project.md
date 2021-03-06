---
title: "Deploy the project"
description: "In this section, you'll learn how to save and get data on the web using the WeDeploy API Client."
buttonTitle: "I deployed the project"
tutorialTitle: "Getting started with WeDeploy Data on the web"
parentId: "data-web"
layout: "tutorial"
time: 50
weight: 7
---

#### Deploy the project

With the API Client connected and our methods added, we now just need to deploy the project so we can start saving and fetching data.

Within `tutorial-data-web` on your command line, add a git remote by running:

```xml
git remote add wedeploy http://git.wedeploy.com/<your-project-id>.git
```

Then make a first commit. 
1. `git add .`
2. `git commit -m "Awesome commit"`
3. `git push wedeploy master`

Once pushed, WeDeploy will immediately start building and deploying your project.


