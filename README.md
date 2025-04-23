# Hugo + GitHub Pages + GitHub Actions = ❤️

This repository is a **self-contained template** to deploy a
[Hugo static site](https://gohugo.io/), hosted on [GitHub](https://github.com), and deployed to [GitHub Pages](https://pages.github.com)
hosting, using the continuous integration available through
[GitHub Actions](https://actions.github.com)—all for free.

The theme used by this template is [Stack](https://github.com/CaiJimmy/hugo-theme-stack) 📚, "_Card-style Hugo theme designed for bloggers_" by [@CaiJimmy](https://github.com/CaiJimmy).

## ⚙️ Quick Start

Launching a website with this template will take 5-10 minutes:

1. 🪪 [**Register** a GitHub account](https://github.com/join) if you don't already have one.

2. 🪄 **Instantiate** this template repository [by clicking the green "Use this template" button above](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template).

3. 👮 **Enable write permissions for GitHub Actions**, [by setting the permission level of `GITHUB_TOKEN` to "Read and write permissions", as described in the documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#configuring-the-default-github_token-permissions).

4. 📰 Go to the page of your repository, and [select the `gh-pages` branch as a **publishing source**](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch), to publish the website on GitHub Pages.

5. 🛠️ Edit the file `config.yanl` to change the value of `baseURL`: It must reflect **the absolute URL of your website**, including the protocol (`https://`), the domain name, and the path to the root of your website (this is usually `https://<your GitHub username>.github.io/<the name of the repository>`, for instance the original website for this template is [https://jlumbroso.github.io/hugo-stack-template/](https://jlumbroso.github.io/hugo-stack-template/)). Once you commit this change, the website will be automatically deployed to GitHub Pages! 🥳🎉

6. 📝 Update the `README.md` so it doesn't look like you just instantiated the template! 😁

Once you are done, you can visit [Stack's documentation](https://stack.jimmycai.com/) to learn how to customize your website.

### ⚜️ Using a custom domain

Optionally, instead of publishing on a `github.io` subdomain, you can publish on a custom domain. To do so, you need to:

- Edit the file `.github/workflows/gh-pages.yml` to change the value of `CNAME` to your custom domain name.

- Edit the file `config.toml` to change the value of `baseURL` to your custom domain name.

## ✍️ Credits

This template was created by [**@jlumbroso**](https://github.com/jlumbroso), based on the [Stack](https://github.com/CaiJimmy/hugo-theme-stack). The theme is licensed GPLv3, and the template is licensed MIT.
