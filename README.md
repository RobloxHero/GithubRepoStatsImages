# GithubRepoStatsImages
![2,0](https://github.com/RobloxHero/MemoryStoreServerPopulating/blob/main/GitHub-Images/Profile.svg)
![2,0](https://github.com/RobloxHero/MemoryStoreServerPopulating/blob/main/GitHub-Images/IssuesList.svg)
## Installation
- Download this repo and add the files to your repo.
- Create a Fine Grained Personal Access Token
  
  ```Github Settings > Developer Settings > Personal access tokens > Fine grained token```
- Copy the token you created
- Create an Action Secret
  
  ```Read access to code, commit statuses, deployments, discussions, issues, metadata, and pull requests```

  ```Read and Write access to code```
  
  ```Select Your Repository to use the token with```
  
  ```Repository Settings > Secrets and variables > New Repository Secret```
- Name your secret ROBLOX_IMAGES_ACCESS_TOKEN
- Then paste your Access Token into secret
- Create a Milestone named Version 1.0  <-- Important the Milestone is a placeholder, do not add any issues to it. Just name it Version(Then Whatever you want)
- Create a milestone you want to add Issues to.
- Create a Label named Version 1.0 <-- Inmportant The version label needs to be the same as your placeholder Milestone
- Then Create a Issue, Attach the issue to your milestone, And add the Version LABEL <-- to it.

  Do NOT Add anything to the Version Milestone Placeholder

## How to use
You should be able to see the action in the actions menu.

You can click run action to genereate your images.

The action also runs any time an issue is updated or you push into the repo.

You will see a folder named Github-Images containing your SVG images in your repo.

