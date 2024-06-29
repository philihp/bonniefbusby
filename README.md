This is the source code of the website of Bonnie F Busby.

## Getting Started

If you're reading this, I'm going to assume you've come here to make changes, update, and maintain this blog. To get started, you'll probably want to checkout the repo and run it locally.

To get started, you'll want to install

* [Brew](https://brew.sh)
* [Xcode Command Line Tools](https://mac.install.guide/commandlinetools/3)
* [Node](https://nodecli.com/nodejs-nodenv), installed with nodenv

From there, you want to install this repo

```bash
git clone git@github.com:philihp/bonniefbusby.git
cd bonniefbusby
npm install
```

And once you've done that, then every time you want to dev just do

```bash
npm run dev
```

and open [http://localhost:3000](http://localhost:3000) with your browser

## Deploy

This website is deployed with Vercel. Simply committing your changes and pushing to the main branch should be enough to trigger this.