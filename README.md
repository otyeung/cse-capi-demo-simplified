# cse-capi-demo-simplified

### Run the apps locally using npm

```
npm i
npm start
```

The apps runs on port 3000. Open chrome browser and open "http://localhost:3000" to launch the apps

### Deploy the apps to Github Pages

Modify package.json file set homepage value to your respository "https://<username>.github.io/cse-capi-demo-simplified/"

Commit the changes and deploy React apps to Github

```
git add
git commit -m "setup gh-pages"
git push
npm run deploy
```

Github will build the production apps and deploy to 'gh-pages' branch, your web apps will be served at "https://<username>.github.io/cse-capi-demo-simplified/"

### Deploy the apps to Vercel

Modify package.json file by removing homepage property, or you must set it to the production URL from Vercel (which will be generated automatically during deployment process)

Install Vercel CLI via npm and run vercel in command line, you will be asked to login your account at first time :

```
npm i -g vercel
vercel
```

You will be asked a few simple questions (choose default options), the web apps will be deployed to your vercel account. It'll give you a preview URL, to deploy to production, type the following command :

```
vercel --prod
```

Open chrome browser, type the production URL to launch the apps.
