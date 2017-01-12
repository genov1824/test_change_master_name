Change default name "master", to custom name:
      1. Rename your master locally: git branch -m custom_name
      2. Push the new branch: git push origin custom_name
      3. Change custom_name to the be the default branch from GitHub settings
      4. Remove the old master branch: git push origin :master
