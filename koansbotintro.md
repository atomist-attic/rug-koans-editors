# Embarking on your Rug Koans Journey using the Atomist Bot

First, if you haven't already please ensure that you have the [Rug CLI][rug-cli] [installed][rug-cli-install]. Instructions on [how to install the Rug CLI are provided][rug-cli-install]. Even though you're going to use buttons to execute the Rug editors against your project on GitHub, you'll still likely want to run `rug test` locally to ensure you're completed each Koan.

[rug-cli]: https://github.com/atomist/rug-cli
[rug-cli-install]: http://docs.atomist.com/rug/rug-cli/rug-cli-install/]

You can begin your journey within an existing project on GitHub using the Atomist Bot but it is strongly recommended that you start by creating a new GitHub project for your work using the [Rug Koans project][rug-koans-project] Rug generator. To create your new project workspace for your Rug Koans using the Bot simply type the following in a channel where the Bot has been invited:

```
@atomist generators rug
```

Then click on the `Generate Project` button for the `NewRugKoansProject` project.

Once you have a project all set you'll probably want to clone it locally and then it's time to start your journey proper...

## How to work through the Koans using the Atomist Bot

Every Koan comes with three main stages: `Start`, `See Solution` and `Apply Solution`. The three stages are executed and written in Rug and you'll use corresponding buttons for each of the stages.

To see how you move through these stages for each Koan the following will walk you through how to do that for Step 1.

### Starting a Koan

To get started you need the starter files for your Koan. At a minimum, this will be a Rug test that will be failing but it is typically more than that.

First you need to ask what editors are out the for the Rug Koans:

```
@atomist editors rug koans
```

That will display the list of Rugs and now you should be able to click on the `atomist-rugs.rug-koans-editors.Step1` `Edit Project` button so you'll then be taken through a conversation to add the starter files to your project.

After the editor has run you'll have access to the files you need to get started so you'll likely need to do a `git pull` to your local copy. Each of the files contains comments where your edits are needed, starting with a rug test, which in the case of Step 1 is `.atomist/tests/Step1.rt`.

Each Koan is typically accompanied by links to where you can learn about the features that are being explored as part of your journey.

A Koan ends when the `rug test` command succeeds.

### Seeing the Solution

If you get really stuck, each Koan comes with a means of seeing what the solution is supposed to look like *alongside* your working files.

To see the solution for Step 1 you'd execute the following command again to see the editors available to the Bot:

```
@atomist editors rug koans
```

And then you can click on the `Edit Project` button for the `atomist-rugs.rug-koans-editors.Step1SeeSolution` editor to add those new files to your project.

### Applying the Solution

If you get really, *really* stuck, each Koan comes with a means of overwriting your working files with the solution so you can move happily.

To apply the solution for Step 1 you'd click on the `Edit Project` button for the `atomist-rugs.rug-koans-editors.Step1OverwriteWithSolution` editor to apply those new files to your project.


### Moving onto the next Koan

Once you have completed a Koan it's time to circle back round to run the next editor to apply the starting point for your next step on the journey. In the case of Step 1 and moving to Step 2 that would mean clicking on the `atomist-rugs.rug-koans-editors.Step2` `Edit Project` button so you'll then be taken through a conversation to add the next step's starter files to your project.

---
Created by [Atomist][atomist].
Need Help?  [Join our Slack team][slack].

[atomist]: https://www.atomist.com/
[slack]: https://join.atomist.com/
