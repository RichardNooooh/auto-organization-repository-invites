
#### CURRENTLY DOES NOT WORK. ATTEMPTING DEPLOY ONLY EXHIBITS THE SIMILAR BEHAVIOR AS THE ORIGINAL REPO.
GitHub first checks if the invited individual is a member or outside collaborator of the organization.
If the individual is in fact a member, then the API should properly bring that individual into the repo. Otherwise, the individual is first invited to the organization.

One possible solution would be to ask the user to keep the app open on their browser, and have the app wait and check if the individual has accepted the invitation. Then it could bring the user into the repo.



# Automated Github Organization Invites [![Code Climate](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites/badges/gpa.svg)](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites) [![Issue Count](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites/badges/issue_count.svg)](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites)

> Quickly host a webpage allow people to click and receive and invite to your Github Organization

<p align="center">
  <img src="auto-invites-example.png"/>
</p>

### Features

* Validates submitted Github usernames
* Links in your Github Organization's avatar/image
* Lightweight

### Get It Right Now

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

All you have to do is

1. Click **Deploy to Heroku**
2. Fill in the **Environment Variables** when prompted. These will be a *[Github Access Token](https://github.com/blog/1509-personal-api-tokens)*, which should have Organisation priviledges enabled, and a *Github Organisation name*, and a *background color*. The choices are `{blue,green,grey,pink,red,white}`. If you don't enter one of those strings it defaults to 'white'.

#### All Done! Just share the Heroku App's URL to people and they'll be able to get themselves an invite to your organisation.


#### Credit To *[Code, Applied To Life](https://medium.com/code-applied-to-life/automated-github-organization-invites-3e940aa27040#.sikfvzyaj)* for their efforts which were used as a base for this.

#### CURRENTLY DOES NOT WORK. ATTEMPTING DEPLOY ONLY EXHIBITS THE SIMILAR BEHAVIOR AS THE ORIGINAL REPO.
GitHub first checks if the invited individual is a member or outside collaborator of the organization.
If the individual is in fact a member, then the API should properly bring that individual into the repo. Otherwise, the individual is first invited to the organization.



