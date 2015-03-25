HOW TO DEPLOY

Note: goappengine should be installed
go should be in the environment variables path

1. Open command line
	1.1 Go back to Github folder
	1.2 click in navigation bar
	1.3 type "cmd"
	1.4 Command line will appear in Github directory
2. Type "goapp deploy BookPeddlerWebsite/" or whatever the folder's name is

C:\Users\stell_000\Documents\GitHub>goapp deploy Resume
05:05 PM Application: jennifer-garner-711; version: 1
05:05 PM Host: appengine.google.com
05:05 PM
Starting update of app: jennifer-garner-711, version: 1
05:05 PM Getting current resource limits.
05:05 PM Scanning files on local disk.
05:05 PM Cloning 9 application files.
05:05 PM Uploading 1 files and blobs.
05:05 PM Uploaded 1 files and blobs.
05:05 PM Compilation starting.
05:05 PM Compilation: 1 files left.
05:05 PM Compilation completed.
05:05 PM Starting deployment.
05:05 PM Checking if deployment succeeded.
05:05 PM Deployment successful.
05:05 PM Checking if updated app version is serving.
05:06 PM Completed update of app: jennifer-garner-711, version: 1
05:06 PM Uploading PageSpeed configuration.

C:\Users\stell_000\Documents\GitHub>

3. If prompted to login, enter stellaluna.711@gmail.com for email and current password for that account for password


IF CHANGES NOT TAKING EFFECT
Go to Google Developers Console
Go to Compute -> App Engine -> Versions
and make sure the latest version is selected as the default

ctrl - shift - r to force reload, stripping cache