
````markdown
<br><br><br>

<div align="center">
  <img src="https://raw.githubusercontent.com/soroushchehresa/github-readme-linkedin/master/linkedin-github.png" width="150" />

  # GitHub Readme LinkedIn
  A serverless application to get dynamically generated images from your LinkedIn profile on your GitHub READMEs!
</div>

<br><br>

## Usage
If you want to use this project on your GitHub profile, fork it and deploy it to your own Vercel instance, then use your instance URLs.

<br>

## Example
```md
<img src="https://github-readme-linkedin-lrdc-cnbkc4fwm.vercel.app/user?username=ibrahimqasmi313" />
````

<br>

## Methods

| URL           | Example                                                                                        | Description                             |
| ------------- | ---------------------------------------------------------------------------------------------- | --------------------------------------- |
| `/experience` | `https://github-readme-linkedin-lrdc-cnbkc4fwm.vercel.app/experience?username=ibrahimqasmi313` | Your LinkedIn experience section.       |
| `/education`  | `https://github-readme-linkedin-lrdc-cnbkc4fwm.vercel.app/education?username=ibrahimqasmi313`  | Your LinkedIn education section.        |
| `/skills`     | `https://github-readme-linkedin-lrdc-cnbkc4fwm.vercel.app/skills?username=ibrahimqasmi313`     | Your LinkedIn skills section.           |
| `/languages`  | `https://github-readme-linkedin-lrdc-cnbkc4fwm.vercel.app/languages?username=ibrahimqasmi313`  | Your LinkedIn languages section.        |
| `/user`       | `https://github-readme-linkedin-lrdc-cnbkc4fwm.vercel.app/user?username=ibrahimqasmi313`       | Your full name, headline, and location. |

<br>

## Parameters

| Name       | Example                              | Description                     | Required |
| ---------- | ------------------------------------ | ------------------------------- | -------- |
| `username` | `?username=ibrahimqasmi313`          | Your LinkedIn username.         | YES      |
| `limit`    | `?username=ibrahimqasmi313&limit=10` | Number of list items to return. | NO       |

```
```






==========================================================================================

## Deploy your own
You can deploy and use this project without any errors on your own [Vercel](https://vercel.com) instance by the following steps:
<details>
 <summary><b>Guide on setting up Vercel 🔨 </b></summary>
 
 1. Go to [vercel.com](https://vercel.com)
 1. Click on `Login`  
   ![](https://files.catbox.moe/tct1wg.png)
 1. Sign in with GitHub by pressing `Continue with GitHub`  
   ![](https://files.catbox.moe/btd78j.jpeg)
 1. Sign into GitHub and allow access to all repositories, if prompted
 1. Fork this repo
 1. Go back to your [Vercel dashboard](https://vercel.com/dashboard)
 1. Select `Import Project`  
   ![](https://i.imgur.com/yzVClIY.png)
 1. Select `Import a Git Repository`  
   ![](https://i.imgur.com/8E96p4U.png)
 1. Select root and keep everything as is, just place your LinkedIn cookie called `li_at` as your environment variable named `LINKEDIN_TOKEN` and click `Deploy`
   ![](https://i.imgur.com/ngBYKat.png)
 1. You're good to go. See your domains to use the API!
</details>

<br>

## Technologies
- [TypeScript](https://github.com/microsoft/TypeScript)
- [Node.js](https://github.com/nodejs/node)
- [Express.js](https://github.com/expressjs/express)
- [Serverless](https://vercel.com)
