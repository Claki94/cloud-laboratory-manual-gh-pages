# Manual deployment with Github pages:

1. Create the Github repository with the project we want to deploy with Github pages.
2. From the master/main branch create a branch called gh-pages.
3. Execute the production build of the project.
4. Delete all the files except the dist folder with the production bundling.
5. Move the content of dist to the root folder of the project.
6. Commit and publish the branch with the changes.
7. Github will automatically start to execute the workflow on the new branch to publish the Github page.
