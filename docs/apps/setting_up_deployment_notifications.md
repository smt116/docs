page_title: Setting Up Deployment Notifications
page_author: Risa B. (converted by Britt)
page_description: Knowledge base article to instruct users on how to they can use the deployment web hook for notifications 
page_keywords: deployment notification slack hipchat campfire brutus cli 

## Deployment notifications

You are able to integrate with [Slack](https://slack.com/) to display notifications such as when deployments have started and when they’ve ended. This is a handy way to apprise teams of when coworkers deploy.

On Ninefold, it’s super easy to do.  You’ll only need to use our [awesome CLI](http://help.ninefold.com/getstarted/how_to_install_and_utilize_the_cli/)!

Once you have the CLI installed, run in terminal:

	$ ninefold webhooks create SERVICE URL

where __SERVICE__ is the team communication platform, and __URL__ is the URL generated by their system.

Once you’ve got it set up, you’ll see our Brutus -- the shaved yak -- make an appearance letting you know your deployments are completing.
