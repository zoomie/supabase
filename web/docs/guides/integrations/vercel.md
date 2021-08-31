---
id: vercel
title: 'Vercel'
description: Add Apple OAuth to your Supabase project
---

Vercel integrations extend and automate your workflow by connecting your Vercel projects to database tools like Supabase. This guide will explain how to set up the Vercel Supabase integration with your projects hosted on Vercel or how to create new projects on Vercel with Supabase settings already set up.

The Vercel Supabase integration has two main use cases:

1. **Pre-existing projects**

   Add the correct environment variables into multiple pre-existing Vercel projects

2. **New project deploy**

   Deploy a Vercel project, with the correct environment variables and also apply the postgres schema to your Supabase project.
   Usually these projects can be launched with the blue Vercel 'Deploy' buttons you might see on the Supabase website or in Readme files in GitHub example projects.

## Getting started

First, if you don't already have an account on Vercel, you will need to do the following:

- Go to https://vercel.com/
- Sign up (_we recommend using your GitHub account_)
- Create a team

## New project deploy

Some of the GitHub example projects for Supabase will have a 'Deploy' button. These links will redirect your browser to Vercel, which will then take you through the process of setting up your new project.

![vercel deploy button in GitHub readme](/img/guides/integrations/vercel/vercel-deploy-button-in-readme.png)

On the Vercel website, you will need to input a name for your new Vercel project and also the team for the project. If you have only just registered your account with Vercel, the team should be pre-selected with the team you created earlier.

<!-- ![vercel deploy button in GitHub readme](/img/guides/integrations/vercel/vercel-deploy-button-new-name.png) -->

Now add the `anon` key of your Supabase project, and also the `public url`.
Both of these values can be found in the [Supabase dashboard](https://app.supabase.io) in the Settings -> API page of your Supabase project.

![vercel deploy button in GitHub readme](/img/guides/integrations/vercel/vercel-deploy-config-env-vars.png)
![vercel deploy button in GitHub readme](/img/guides/integrations/vercel/vercel-deploy-deployed.png)

## Pre-existing projects

![vercel integration market](/img/guides/integrations/vercel/vercel-integration-marketplace-supabase.png)

## Steps

coming soon...

## Resources

coming soon...
