Backup scripts using S3CMD
==========================

I use these scripts on my Amazon hosted server to back up my git repositories and mongo database.

You will need to run the s3cmd configuration tool in order to allow this to work on your own server.

I've scheduled my scripts 'git-backup' and 'mongo-backup' to run through cron, example can be found here:
http://jimib.co.uk/code/project/s3cmd/