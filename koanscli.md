# Embarking on your Rug Koans Journey using the Rug CLI Only

First, if you haven't already please ensure that you have the [Rug CLI][rug-cli] [installed][rug-cli-install]. Instructions on [how to install the Rug CLI are provided][rug-cli-install].

[rug-cli]: https://github.com/atomist/rug-cli
[rug-cli-install]: http://docs.atomist.com/rug/rug-cli/rug-cli-install/]

You can begin your journey within an existing project but it is strongly recommended that you start by creating a new project for your work using the [Rug Koans project][rug-koans-project] Rug generator. The instructions on how to run that generator are in the [projects README][rug-koans-project].

Once you have a project all set it's time to start your journey proper...

## How to work through the Koans using Rug CLI

Every Koan comes with three main: `Start`, `See Solution` and `Apply Solution`. The three stages are executed written in Rug and so you'll use the CLI to set them up for every Koan.

To see how you move through these stages for each Koan the following will walk you through how to do that for Step 1.

### Starting a Koan

To get started you need the starter files for your Koan. At a minimum, this will be a Rug test that will be failing but it is typically more than that.

To get the starter files for Step 1 you would do the following:

```
$ cd yourprojectdirectory
$ rug edit atomist-rugs:rug-koans-editors:Step1
```

After the editor has run you'll have access to the files you need to get started. Each of the files contains comments where your edits are needed, starting with a rug test, which in the case of Step 1 is `.atomist/tests/Step1.rt`.

Each Koan is typically accompanied by links to where you can learn about the features that are being explored as part of your journey.

A Koan ends when the `rug test` command succeeds.

### Seeing the Solution

If you get really stuck, each Koan comes with a means of seeing what the solution is supposed to look like *alongside* your working files.

To see the solution for Step 1 you'd execute:

```
$ cd yourprojectdirectory
$ rug edit atomist-rugs:rug-koans-editors:Step1SeeSolution
```

### Applying the Solution

If you get really, *really* stuck, each Koan comes with a means of overwriting your working files with the solution so you can move happily.

To apply the solution for Step 1 you'd execute:

```
$ cd yourprojectdirectory
$ rug edit atomist-rugs:rug-koans-editors:Step1OverwriteWithSolution
```

### Moving onto the next Koan

Once you have completed a Koan it's time to circle back round to run the next editor to apply the starting point for your next step on the journey. In the case of Step 1 that would mean then executing the following:

```
$ cd yourprojectdirectory
$ rug edit atomist-rugs:rug-koans-editors:Step2
```
