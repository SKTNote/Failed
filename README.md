### Let's make Github Blog!

`REBUIDING GITHUB BLOG`




























### Launch your Static Site using Devlopr in minutes :rocket:

To get started follow this [Tutorial](https://devlopr.netlify.app/get-started)

```sh
수정 중...
```

### Github Actions

This Project uses this custom built action for deploying jekyll to github, available in Marketplace - [Jekyll Deploy Action](https://github.com/marketplace/actions/deploy-jekyll-site)
### Demo (Hosted Apps)

- Github Pages Demo - [here](https://sanketkundu.github.io/)
- Firebase Demo - [here](https://devlopr.web.app)
- Netlify Demo - [here](https://devlopr.netlify.com)
- Vercel Demo - [here](https://devlopr-jekyll.vercel.app/#/)
- Heroku Demo - [here](https://devlopr-jekyll.herokuapp.com)

#### Features :

- Local CMS Admin Support using [Jekyll Admin](https://jekyll.github.io/jekyll-admin/)
- Onine CMS Admin Support using [Netlify CMS](https://sujaykundu.com/blog/how-to-setup-netlify-cms-with-github-pages-hosted-jekyll-blog/),Forestry, Siteleaf, CloudCannon, Cosmic, Contentful
- Supports Latest [Jekyll 4.x](https://jekyllrb.com) and [Bundler](https://bundler.io)
- Stylesheet built using Sass
- Comments using [Hyvor](https://talk.hyvor.com/) and [Disqus](https://disqus.com/)
- SEO-optimized
- Real Time Search - [Algolia](https://sujaykundu.com/blog/adding-real-time-search-to-jekyll-site-using-algolia/)
- Sell Stuff (Ecommerce) in your Blog using [Snipcart](https://snipcart.com/)
- Send Newsletters using [Mailchimp](https://mailchimp.com/)
- Contact Forms Support for [Getform](https://getform.io), [Formspree](https://formspree.io/)
- Coding Activity using [Wakatime](https://wakatime.com/)
- Hosting Support for [Github Pages](https://pages.github.com), [Netlify](https://netlify.com), [Vercel](https://vercel.com), [Heroku](https://heroku.com), [AWS Amplify](aws.amplify.com), [Firebase](https://firebase.com)
- CI/CD Support using [Travis CI](https://sujaykundu.com/blog/deploy-jekyll-blog-using-github-pages-and-travis-ci/), [Buddy](https://buddy.works/) , [Circle CI](https://circleci.com/)

#### Jekyll Admin
You can easily manage the site locally using the Jekyll admin : [http://localhost:4000/admin](http://localhost:4000/admin)

![Jekyll Admin](https://github.com/sujaykundu777/devlopr-jekyll/blob/master/assets/img/jekyll-admin.PNG?raw=true)

## Recent Release Changes (v 0.4.7):

- Minor Bug fixes and optimizations
- [Added Support for Multi Authors](https://devlopr.netlify.app/blog/added-multi-author-support/#/)
- [Added Support for Math Symbols](https://devlopr.netlify.app/blog/added-latex-equations-support/#/)

You can check out for all changelogs [here](https://www.buymeacoffee.com/sujaykundu/release-v-0-4-7)

## Pull the latest changes

```s
git remote -v
git remote add upstream https://github.com/sujaykundu777/devlopr-jekyll.git
git fetch upstream
git checkout master
git merge upstream/master
git push
```

## Using Docker :

Building the Image :

`docker build -t my-devlopr-jekyll-blog .`

Running the container :

`docker run -d -p 4000:4000 -it --volume="$PWD:/srv/jekyll" --name "my_blog" my-devlopr-jekyll-blog:latest jekyll serve --watch`

## Using Docker Compose :

### Development :

You can run the app in development mode : (your changes will be reflected --watch moded)

Serve the site at http://localhost:4000 :

`docker-compose -f docker-compose-dev.yml up --build --remove-orphans`

### Production :

You can run the app in production mode : (your changes will be reflected --watch moded)

Serve the site at http://localhost:4000 :

`docker-compose -f docker-compose-prod.yml up --build --remove-orphans`

Stop the app :
`docker-compose -f docker-compose-prod.yml down`
Once everything is good and ready to go live -

`docker-compose -f docker-compose-prod.yml up --build --detach`

## Contributors:

This project exists thanks to all the people who contribute.

Contributions are more than just welcome. Fork this repo and create a new branch, then submit a pull request

- 1.Fork it [http://github.com/sujaykundu777/devlopr-jekyll/fork](http://github.com/sujaykundu777/devlopr-jekyll/fork )

- 2.Create your feature branch
`git checkout -b my-new-feature`

- 3.Commit your changes
`git commit -am 'Add some feature'`

- 4.Push to the branch
`git push origin my-new-feature`

- 5.Create new Pull Request

## Support this Project:

Back this project by Donating to our [Open Collective](https://opencollective.com/devlopr-jekyll/donate) or if you like my work[Buymeacoffee](https://buymeacoffee.com/sujaykundu).

Thanks to all our Backers ! 🙏 [Become a Backer](https://opencollective.com/devlopr-jekyll/donate)

<a href="https://opencollective.com/devlopr-jekyll#backers" target="_blank"><img src="https://opencollective.com/devlopr-jekyll/backers.svg?width=890" /></a>

<a href="https://opencollective.com/devlopr-jekyll#backers" target="_blank"><img src="https://opencollective.com/devlopr-jekyll/tiers/backer.svg?avatarHeight=36" /></a>

### For Help :

You can contact me, if you need any help via [Email](mailto:sujaykundu777@gmail.com). If you like the project. Don't forget to :star: !

## Licence

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT). You can do anything you want, including projects for your clients, as long as you mention an attribution back (credit links in footer). See the [Licence](https://github.com/sujaykundu777/devlopr-jekyll/blob/master/LICENSE) file

