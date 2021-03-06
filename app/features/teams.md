---
description: Collaborate with your colleagues using our private teams
---

# Teams

Use our private teams feature to collaborate on private projects. If you'd like to set up a private team, please message us at contact@wandb.com. 

## Common Questions

### Get access to private teams

If you're at a company, we have enterprise plans. Check the [pricing page](https://www.wandb.com/pricing) for more details. 

If you're an academic, we offer free private teams. Check the [academic page](https://www.wandb.com/academic) to apply for an account upgrade.

### Create a new team

Once you have the feature enabled, create a new team on your [Settings](https://app.wandb.ai/settings) page in the app. The name will be used in the URL of all your team projects, so make sure you pick something short and descriptive, since you won't be able to change it later. 

### Move runs to a team

It's easy to move runs between projects you have access to. On the project page:

1. Click the table tab to expand the runs table
2. Click the checkbox to select all runs
3. Click "Move" to select the destination project. This can be in your personal account or any team that you're a member of.

### Send new runs to a team

In your script, set the entity to your team. "Entity" just means your username or team name. Create an entity \(personal account or team account\) in the web app before sending runs there.

```python
wandb.init(entity="example-team")
```

### Invite team members

You can invite new members to your team on your team settings page:  
app.wandb.ai/teams/&lt;your-team-here&gt;

### See privacy settings

You can see the privacy settings of all team projects on the team settings page:  
app.wandb.ai/teams/&lt;your-team-here&gt;

Here's what the settings look like. In this screenshot the toggle is on, which means all projects in the team are only visible to the team.

![](../../.gitbook/assets/image%20%2814%29.png)

