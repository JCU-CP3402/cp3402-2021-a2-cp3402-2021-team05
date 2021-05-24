The deployment workflow for this project goes by the following:

Firstly you would need to get invited as collaborator for both the local environment and theme repository on Github.

Both repository has main and beta branch, where main is for the live server and beta is for the staging server.

Do a pull from the local environment and the theme github repository from the beta branch of the repository.

Run the site and load the theme on a local environment using Vagrant to maintain the virtualbox environment.

Commit any changes to the beta branch of both the repositories.

Export a backup file of the site.

Upload the backup file into the staging server of the project.

Other members will then review the staging server for the changes and if there are any errors in the staging server.

If everything is okay, the leader will then merge the beta branch into the main branch and export a backup file of the
staging server and upload it into the live server.