## 始まる前に、

Reactの基本を勉強しましょう！ \
[今から始めるReact入門](https://qiita.com/TsutomuNakamura/items/72d8cf9f07a5a30be048)
[新しい React アプリを作る](https://ja.reactjs.org/docs/create-a-new-react-app.html)
- node.jsなどの必要なProgamを設置して、環境を整える必要があります。

## create app

```sh
# create-react-app を install
[frontend-master-sample/movie-search-app-using-React]$ npm install -g create-react-app
[frontend-master-sample/movie-search-app-using-React]$ create-react-app hooked
# or
[frontend-master-sample/movie-search-app-using-React]$ npx create-react-appp hooked
```

## Tutorial を見ながら

[Tutorial page](https://www.freecodecamp.org/news/how-to-build-a-movie-search-app-using-react-hooks-24eb72ddfaf7/) を見ながら実装

```sh
[frontend-master-sample/movie-search-app-using-React]$ cd hooked
[frontend-master-sample/movie-search-app-using-React/hooked]$ mkdir -p src/components
[frontend-master-sample/movie-search-app-using-React/hooked]$ mv src/App.js src/components 
[frontend-master-sample/movie-search-app-using-React/hooked]$ touch src/components/Header.js
[frontend-master-sample/movie-search-app-using-React/hooked]$ touch src/components/Movie.js 
[frontend-master-sample/movie-search-app-using-React/hooked]$ touch src/components/Search.js
```

実装が終わると、実行してみる
```sh
[frontend-master-sample/movie-search-app-using-React/hooked]$ npm start

> hooked@0.1.0 start /Users/yuchulkim/work/frontend-master-sample/movie-search-app-using-React/hooked
> react-scripts start

Compiled successfully!

You can now view hooked in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.3.5:3000

Note that the development build is not optimized.
To create a production build, use yarn build.

```
![image](https://user-images.githubusercontent.com/18433640/87854601-0f53be80-c94e-11ea-9d0d-6c2715fdb314.png)


児童にブラウザが立ち上がる。
もし、立ち上がらない場合、`http://localhost:3000` へアクセス

## 終わりに

もっといいものにしたら、[github](https://github.com/samie820/hooks-movie-app) のソースを見ながら修正してみましょう！

