# Custom Icon Badges

![stars](https://custom-icon-badges.herokuapp.com/github/stars/DenverCoder1/custom-icon-badges?logo=star "stars")
![issues](https://custom-icon-badges.herokuapp.com/github/issues-raw/DenverCoder1/custom-icon-badges?logo=issue "issues")
![license](https://custom-icon-badges.herokuapp.com/github/license/denvercoder1/custom-icon-badges?logo=repo "license MIT")
[![discord](https://custom-icon-badges.herokuapp.com/discord/819650821314052106?color=7289DA&logo=comments&label=discord&logoColor=white)](https://discord.gg/fPrdqh3Zfu "Dev Pro Tips Discussion & Support Server")

Allows users to more easily use their own icons and logos to [shields.io badges](https://github.com/badges/shields).

## ⚡ How to use

1. Get a badge URL from [shields.io](https://shields.io/).

2. Replace `img.shields.io` with `custom-icon-badges.herokuapp.com`

3. Use any available slug as the logo query parameter.

```md
https://custom-icon-badges.herokuapp.com/badge/custom-badge-blue.svg?logo=paintbrush&logoColor=white
```

Preview:

![img](https://custom-icon-badges.herokuapp.com/badge/custom-badge-blue.svg?logo=paintbrush&logoColor=white)

## 🖼️ Existing logos

The following are examples of existing icons and logos that are already available.

### Octicons

Currently all [Octicons](https://primer.style/octicons/) are supported.

| Slug          | Example                                                                                  |
| ------------- | ---------------------------------------------------------------------------------------- |
| `issue`       | ![img](https://custom-icon-badges.herokuapp.com/badge/Issue-red.svg?logo=issue)          |
| `fork`        | ![img](https://custom-icon-badges.herokuapp.com/badge/Fork-orange.svg?logo=fork)         |
| `star`        | ![img](https://custom-icon-badges.herokuapp.com/badge/Star-yellow.svg?logo=star)         |
| `commit`      | ![img](https://custom-icon-badges.herokuapp.com/badge/Commit-green.svg?logo=commit)      |
| `repo`        | ![img](https://custom-icon-badges.herokuapp.com/badge/Repo-blue.svg?logo=repo)           |
| `pr`          | ![img](https://custom-icon-badges.herokuapp.com/badge/Pull%20Request-purple.svg?logo=pr) |
| `heart`       | ![img](https://custom-icon-badges.herokuapp.com/badge/Heart-D15E9B.svg?logo=heart)       |
| `mail`        | ![img](https://custom-icon-badges.herokuapp.com/badge/Mail-E61B23.svg?logo=mail)         |
| More Octicons | [View all ⇨](https://primer.style/octicons)                                              |

### Miscelanious

| Slug         | Example                                                                                            |
| ------------ | -------------------------------------------------------------------------------------------------- |
| `ceylon`     | ![img](https://custom-icon-badges.herokuapp.com/badge/Ceylon-E39842.svg?logo=ceylon)               |
| `controller` | ![img](https://custom-icon-badges.herokuapp.com/badge/Controller-blue.svg?logo=controller)         |
| `phone`      | ![img](https://custom-icon-badges.herokuapp.com/badge/Phone-green.svg?logo=phone&logoColor=white)  |
| `swi-prolog` | ![img](https://custom-icon-badges.herokuapp.com/badge/Prolog-E61B23.svg?logo=swi-prolog)           |
| Add your own | [Upload icon ⇨](https://custom-icon-badges.herokuapp.com)                                          |

## ➕ Adding a new logo

Upload new icons using the demo site!

The file type can be SVG, PNG, etc. but only SVG format supports the `logoColor` parameter for overriding the color of the logo.

If you think your icon is useful to others, feel free to open a PR to add it to the README above!

Demo site: <https://custom-icon-badges.herokuapp.com>

[![image](https://user-images.githubusercontent.com/20955511/128404656-30af9c39-39a4-4ac8-a4b0-2a077806a94c.png)](https://custom-icon-badges.herokuapp.com)

## 🤗 Contributing

We welcome contributions!

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 📤 Deploying it on your own

Deploying on your own is optional. See the steps below.

<details>
  <summary>Deploy to Heroku</summary>

  1. Sign in to **Heroku** or create a new account at <https://heroku.com>
  2. Click the Deploy button below

  <p align="center">
    <a href="https://heroku.com/deploy?template=https://github.com/DenverCoder1/custom-icon-badges/tree/main">
      <img src="https://www.herokucdn.com/deploy/button.svg" title="Deploy to Heroku" alt="Deploy"/></a>
  </p>

  3. Add the url of a Mongo database as the `DB_URL` config var. The database should have a collection called `icons`. See [getting started](https://docs.atlas.mongodb.com/getting-started/) for more info on setting up a free Mongo Atlas database.

![image](https://user-images.githubusercontent.com/20955511/126066250-108fc119-4bc3-4ba0-9b07-0c7402c5790e.png)

  4. Click **"Deploy App"** at the end of the form
  5. Once the app is deployed, you can use `<your-app-name>.herokuapp.com` in place of `custom-icon-badges.herokuapp.com`
	
</details>

## 💬 Questions?

Feel free to [open an issue](http://github.com/DenverCoder1/custom-icon-badges/issues/new).

## 🤩 Support

💙 If you like this project, give it a ⭐ and share it with friends!

<p align="left">
  <a href="https://www.youtube.com/channel/UCipSxT7a3rn81vGLw9lqRkg?sub_confirmation=1"><img alt="Youtube" title="Youtube" src="https://img.shields.io/badge/-Subscribe-red?style=for-the-badge&logo=youtube&logoColor=white"/></a>
  <a href="https://github.com/sponsors/DenverCoder1"><img alt="Sponsor with Github" title="Sponsor with Github" src="https://img.shields.io/badge/-Sponsor-ea4aaa?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

[☕ Buy me a coffee](https://ko-fi.com/jlawrence)

---

Made with ❤️ and TypeScript

<a href="https://heroku.com/"><img alt="Powered by Heroku" title="Powered by Heroku" src="https://img.shields.io/badge/-Powered%20by%20Heroku-6567a5?style=for-the-badge&logo=heroku&logoColor=white"/></a>
