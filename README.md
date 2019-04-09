# Welcome to the Hyperstack Sandbox

This a Hyperstack project *sandbox* with everything you need
to get started running Hyperstack in the incredible [GitPod cloud IDE](https://gitpod.io).

Simply click this link to launch the project in gitpod:

> [Launch Now In GitPod](https://gitpod.io/#https://github.com/hyperstack-org/hyperstack-sandbox)

Once launched, the project will install all the needed software,
and in a few minutes you will see your App come up in the preview window.
The first load is a bit slow as all your resources are
compiled, so be patient.

Once the preview is up find the
`  app/hyperstack/components/app.rb`
file and change the greeting string from
`  "Hello world from Hyperstack and Gitpod!"`
to something of your choice, save the file (CTRL/CMD-s)
and you should see the preview updated.

* To stop the application type ctrl-c.
* To restart the app type `bundle exec foreman start`
* To open a new terminal console look for the tiny square icon on the far right of the terminal area.
* To run a rails console open a new console and type `bundle exec rails c`
* Initially you will be in the `experiment-1` branch, so you can always go back to `master` if needed.

## Forking the Repo

GitPod clones and then continously backs up a copy of the sandbox in your Github account, so for most experiments you don't
need to do anything else.  You can for example create new branches for different experiments etc.

In fact to make this easy, the repo is initialized with a master branch, and an experiment-1 branch.  Keep master as a clean backup
so you can do a `git diff master` if needed.

*However* you may want to Fork your own copy of this repo, which is fine.  The only thing you will need to do is to
point to your new repo when launching GitPod:

`https://gitpod.io/#https://github.com/...your repo name here...`

For ease of use you may want to update the link at the top of this readme when you fork.  That's it.

## Using your own workstation instead of GitPod

If you want to use your own workstation for development then simply follow the standard [Hyperstack install instructions.](https://github.com/hyperstack-org/hyperstack/tree/edge/install)
