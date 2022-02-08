# Deployment-Steps-for-deploying-a-REACTAPP-in-netlify
A complete guide to deploy a react app on to netlify

- 1. create a react app and go inside the particular folder.
```js
create-react-app <app_name>
```
```js
cd <app_name>
```
- 2. First Step to deploy:
```js
    npm run build
```
- 3. Add this command to packet.json in the last before one curly bracket
```js
    "homepage" : "."
```
- 4. Try to run ```npm run buid``` command again.
- 5. then create one file namely ```_redirects``` inside the buid folder.
- 6. download netlify cli
```js
    npm i netlify-cli -g
```
- 7. Run the following command to deploy on netlify
```js
    netlify deploy
```
- 8. Run the following command for deploying on the production level
```js
    netlify deploy --prod
```
```Note:~``` Use the publish directory to the build folder.
