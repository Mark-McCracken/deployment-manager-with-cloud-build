# Deploying to GKE

This folder makes it look easy, it's "just" 80 lines of yaml.
Whilst yaml is simple enough once you get the gist, every line here takes about 5 minutes to understand it's implications, and work out what you're aiming for.

The nice thing about this is that there are seemingly no credentials to faff with.
Don't need to specify a project either.
It runs in whatever project you create the cloud build trigger in, with it's default `<projectnumber>@cloudbuild.gserviceaccount.com`

But how do you manage the Cloud Build items in code....

