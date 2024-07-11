# weaup-web

## Deployment
Execute the commands below on cli
1. `npm i - firebase-tools -D`
2. `node_modules/.bin/firebase login`. Use the beetles shared account.
3. `node_modules/.bin/firebase deploy`

> [!NOTE]
> If you encounter the error below, run `node_modules/.bin/firebase login --reauth`, then `node_modules/.bin/firebase deploy`
>
> 
> `Error: Assertion failed: resolving hosting target of a site with no site name or target name. This should have caused an error earlier`
