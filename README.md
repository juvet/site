Juvet Site
==========

The documentation site for [Juvet](https://github.com/juvet/juvet).

## DESCRIPTION

[Juvet](http://juvet.io) is a the message platform framework built in Elixir and this is the documentation site that lives at juvet.io.

## DEVELOPMENT

There are dependencies that need to be installed via [yarn](https://yarnpkg.com) with the following command:

```
yarn install
```

This site uses [tailwind] for css. You can change the [`tailwind.js`](tailwind.js) to update the css and run the following command:

```
./node_modules/.bin/tailwind build styles.css -o ./dist/styles.css
```

## DEPLOYMENT

This site is hosted on [netlify](https://netlify.com) and is automatically deployed when the master branch is updated.

## CONTRIBUTING

1. Clone the repository `git clone git@github.com:juvet/site`
1. Create a feature branch `git checkout -b my-awesome-feature`
1. Codez!
1. Commit your changes (small commits please)
1. Push your new branch `git push origin my-awesome-feature`
1. Create a pull request `hub pull-request -b juvet:master -h juvet:my-awesome-feature`
