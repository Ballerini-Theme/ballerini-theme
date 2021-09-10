# ❤️ Contributing
First we would like to thank you for contributing and for helping to improve our project.

Here we have a set of steps and guidelines to make the contribution of our Ballerini Theme project as simple as possible. We tried to clarify the process of adding new themes or adapting this theme to other IDEs, applications or tools. I hope this guide will be helpful in your journey of contributing young padawan.
## 🌐 Language
Although the project was created by native Portuguese speakers, it will be mandatory to use the English language while contributing in a Ballerini Theme repository.
### For native English speakers
Please use simple words and sentences. Don't make fun of non-native English speakers. If you find something wrong with the way they express themselves, try to encourage newcomers and those who are learning English.

Our philosophy is: create an environment in which people feel comfortable to learn.
## 💡 Creating a new themes
To create and upload a new theme, you need to follow the following steps:
1. Create a new repository based on the [template](https://github.com/Ballerini-Theme/template). <br>
  a) The branch name must be `main`, for more information read the [newspaper article](https://www.zdnet.com/article/github-to-replace-master-with-main-starting-next-month/). <br>
  b) The repository name must follow the lowercase notation and must only contain the applications/tools name. E.g. `visual-studio-code`.
2. Build the new theme by using the [Ballerini Theme Color Palette](https://github.com/Ballerini-Theme/ballerini-theme#color-palette). <br>
  a) You can be using all the colors or just the ones you needed to create the theme.
3. Submit and issue with a link to your repository. As soon as the theme is accepted, we will move the repository under the Ballerini Theme organization.
4. Open a PR (Pull Request) to add the theme to the main repository (this one). Add it under its respective category (if it doesn't exist, you can create one). Also, make sure it is in alphabetical order. <br>
5. Finally, after your theme is under the organization, update all links to match the new repository `<URL>`.
6. If you think you can improve your theme, share it with others who also use it for that application, so that more people can use it and contribute together.
## 📎 Maintaining a theme
After your theme is under the Ballerini Theme organization, you're responsible for maintaining it. It's your responsibility to answer issues, review PR's and always keep it up-to-date.

Below you can find some guidelines which we follow:

- Always open pull requests when updating the theme (the `main` branch is protected by default);
- Review issues and PRs periodically;
- When you're going to add a new theme maintainer, add it in the README (team section) and the CODEOWNERS file in .github;
- Share the theme on forums, Twitter and communities, to spread the word about your theme;
- In case you have any questions, reach out to [Alpha Vylly](https://github.com/AlphaLawless)
## 🎈 For organization owners
This section is for owners of the Ballerini Theme organization in GitHub. It covers instructions on how to add a new theme and some responsibilities.
### Adding new theme
To add a new theme to the organization, you need to review the proposed theme and make sure it follows the template and the color pallete.

When the theme is ready to be added to the organization, you need to:
1. Create a new team on the organization for the application. <br>
  a) The team name is the application name; <br>
  b) The team description is the application name more theme maintainers;
2. Invite the theme creator to that team and ask to transfer the repository.
3. When the transfer is completed, add the repository to the created team. <br>
  a) Set the repository permission to write.
4. Go to the theme repository and then: <br>
  a) Disable wikis and projects (we don't use them); <br>
  b) Disable packages (in the same place where we change description); <br>
  c) Add tags (theme, dark-brown-theme, ballerini-theme, ballerini, etc. ); <br>
  d) Add description (✨ Ballerini Theme for ); <br>
  e) Add Open Graph Image (this is the [link for Figma](https://www.figma.com/file/UuIbTrfOv2hjnW5MoZi64N/Ballerini-Theme/duplicate), use it to generate an image); <br>
  f) Add protection rule for the `main` branch (check the `Require pull request reviews before merging` and `Require review from CODEOWNERS`); <br>
  g) Close the issue and add a `Completed` label; <br>
  h) Ask the owner to add the new theme on the main repository; <br>
  i) The theme is ready ❤️;