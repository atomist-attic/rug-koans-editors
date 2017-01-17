# Embarking on your Rug Koans Journey using Buttons

First, if you haven't already please ensure that you have the [Rug CLI][rug-cli] [installed][rug-cli-install]. Instructions on [how to install the Rug CLI are provided][rug-cli-install]. Even though you're going to use buttons to execute the Rug editors against your project on GitHub, you'll still likely want to run `rug test` locally to ensure you're completed each Koan.

[rug-cli]: https://github.com/atomist/rug-cli
[rug-cli-install]: http://docs.atomist.com/rug/rug-cli/rug-cli-install/]

You can begin your journey within an existing project on GitHub but it is strongly recommended that you start by creating a new GitHub project for your work using the [Rug Koans project][rug-koans-project] Rug generator. The following button is the one you need to create your new project workspace for your Rug Koans:

[<img src="http://images.atomist.com/button/start-the-rug-koans-tutorial.png" width="440" alt="Start your Rug Koans Journey"/>](https://api.atomist.com/v1/projects/generators/232f8cf4-da4d-4e9d-adf0-290b2b07667a)

Once you have a project all set you'll probably want to clone it locally and then it's time to start your journey proper...

## How to work through the Koans using Buttons

Every Koan comes with three main stages: `Start`, `See Solution` and `Apply Solution`. The three stages are executed and written in Rug and you'll use corresponding buttons for each of the stages.

To see how you move through these stages for each Koan the following will walk you through how to do that for Step 1.

### Starting a Koan

To get started you need the starter files for your Koan. At a minimum, this will be a Rug test that will be failing but it is typically more than that.

To do this you simply click on the following button and it will apply your edits to the indicated repository on GitHub:

[<img src="http://images.atomist.com/button/start-koan.png" width="216" alt="Start this Rug Koan"/>](https://api.atomist.com/v1/projects/editors/a219b2a6-3d1f-4445-858f-af9059a8f935)

After the editor has run you'll have access to the files you need to get started so you'll likely need to do a `git pull` to your local copy. Each of the files contains comments where your edits are needed, starting with a rug test, which in the case of Step 1 is `.atomist/tests/Step1.rt`.

Each Koan is typically accompanied by links to where you can learn about the features that are being explored as part of your journey.

A Koan ends when the `rug test` command succeeds.

### Seeing the Solution

If you get really stuck, each Koan comes with a means of seeing what the solution is supposed to look like *alongside* your working files.

To see the solution for Step 1 you'd use the following button:

[<img src="http://images.atomist.com/button/see-koan-solution.png" width="267" alt="See this Rug Koan Solution"/>](https://api.atomist.com/v1/projects/editors/73f2146b-9851-4115-862d-ffc9a9257d5e)

### Applying the Solution

If you get really, *really* stuck, each Koan comes with a means of overwriting your working files with the solution so you can move happily.

To apply the solution for Step 1 you'd use the following button:

[<img src="http://images.atomist.com/button/apply-koan-solution.png" width="267" alt="Apply this Rug Koan Solution"/>](https://api.atomist.com/v1/projects/editors/e2aa28cc-d2e5-4a9a-9273-4680bd15438a)


### Moving onto the next Koan

Once you have completed a Koan it's time to circle back round to run the next editor to apply the starting point for your next step on the journey. In the case of Step 1 and moving to Step 2 that would mean clicking the following button:

[<img src="http://images.atomist.com/button/start-koan.png" width="267" alt="Start the next Rug Koan"/>](https://api.atomist.com/v1/projects/editors/9277d901-f391-498b-8b7d-b17074cf8273)

## Time to begin...

[Now you're all set to begin your Rug Koans journey using buttons...](koansbuttons.md)

---
Created by [Atomist][atomist].
Need Help?  [Join our Slack team][slack].

[atomist]: https://www.atomist.com/
[slack]: https://join.atomist.com/
