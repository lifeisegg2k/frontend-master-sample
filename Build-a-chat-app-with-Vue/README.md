## 始まる前に、

- Vue.js 基本事項 
    > [Vue.js の全て](https://jp.vuejs.org/index.html)
- Vuex 基礎
    > [Vuex 基礎中の基礎でｽﾞﾝﾄﾞｺｷﾖｼ!!!](https://qiita.com/omochironn/items/85dc011f646f1223bcdf)

## create app

```sh
# Vue CLI を install
[frontend-master-sample/Build-a-chat-app-with-Vue]$ npm install -g @vue/cli
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated @hapi/joi@15.1.1: joi is leaving the @hapi organization and moving back to 'joi' (https://github.com/sideway/joi/issues/2411)
npm WARN deprecated @hapi/bourne@1.3.2: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/topo@3.1.6: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/address@2.1.4: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/hoek@8.5.1: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated chokidar@2.1.8: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.
npm WARN deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
/Users/yuchulkim/.nodebrew/node/v12.16.1/bin/vue -> /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/bin/vue.js

> fsevents@1.2.13 install /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/node_modules/fsevents
> node install.js

No receipt for 'com.apple.pkg.CLTools_Executables' found at '/'.

No receipt for 'com.apple.pkg.DeveloperToolsCLILeo' found at '/'.

No receipt for 'com.apple.pkg.DeveloperToolsCLI' found at '/'.

gyp: No Xcode or CLT version detected!
gyp ERR! configure error 
gyp ERR! stack Error: `gyp` failed with exit code: 1
gyp ERR! stack     at ChildProcess.onCpExit (/Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/npm/node_modules/node-gyp/lib/configure.js:351:16)
gyp ERR! stack     at ChildProcess.emit (events.js:311:20)
gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:275:12)
gyp ERR! System Darwin 19.5.0
gyp ERR! command "/Users/yuchulkim/.nodebrew/node/v12.16.1/bin/node" "/Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js" "rebuild"
gyp ERR! cwd /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/node_modules/fsevents
gyp ERR! node -v v12.16.1
gyp ERR! node-gyp -v v5.0.5
gyp ERR! not ok 

> core-js@3.6.5 postinstall /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/node_modules/core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)


> @apollo/protobufjs@1.0.4 postinstall /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/node_modules/@apollo/protobufjs
> node scripts/postinstall


> nodemon@1.19.4 postinstall /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/node_modules/nodemon
> node bin/postinstall || exit 0

Love nodemon? You can now support the project via the open collective:
 > https://opencollective.com/nodemon/donate


> ejs@2.7.4 postinstall /Users/yuchulkim/.nodebrew/node/v12.16.1/lib/node_modules/@vue/cli/node_modules/ejs
> node ./postinstall.js

Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)

+ @vue/cli@4.4.6
added 1231 packages from 678 contributors in 124.375s
[frontend-master-sample/Build-a-chat-app-with-Vue]$ vue create vue-chatkit


Vue CLI v4.4.6
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, Router, Vuex, Linter
? Use history mode for router? (Requires proper server setup for index fallback in production) Yes
? Pick a linter / formatter config: Basic
? Pick additional lint features: Lint on save
? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files
? Save this as a preset for future projects? No
? Pick the package manager to use when installing dependencies: Yarn


Vue CLI v4.4.6
✨  Creating project in /Users/yuchulkim/work/frontend-master-sample/Build-a-chat-app-with-Vue/vue-chatkit.
⚙️  Installing CLI plugins. This might take a while...

yarn install v1.22.4
info No lockfile found.
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 🔨  Building fresh packages...
success Saved lockfile.
✨  Done in 68.09s.
🚀  Invoking generators...
📦  Installing additional dependencies...

yarn install v1.22.4
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 🔨  Building fresh packages...

success Saved lockfile.
✨  Done in 11.73s.
⚓  Running completion hooks...

📄  Generating README.md...

🎉  Successfully created project vue-chatkit.
👉  Get started with the following commands:

 $ cd vue-chatkit
 $ yarn serve

➜  Build-a-chat-app-with-Vue git:(Build-a-chat-app-with-Vue) ✗ 

```

## Tutorial を見ながら

[Tutorial page](https://www.sitepoint.com/pusher-vue-real-time-chat-app/) を見ながら実装

ここで問題発生！！！
`CharKit` サービスが中止されてます。
別の `TalkJS` ってやつがあるらしいですが、ちょっと調べなきゃならので、
まず、ここで中止