## Webアプリ開発塾カリキュラム

### A. React導入

参照サイト: https://ja.reactjs.org/docs/getting-started.html

#### 確認ポイント

1. [チュートリアル](https://ja.reactjs.org/tutorial/tutorial.html)を完了する
2. [MAIN CONCEPTS](https://ja.reactjs.org/docs/hello-world.html)を完了する
3. 習った範囲で自分でゼロから何か作ってみる

#### 備考

- codepenの代わりにcodesandboxを使用することがおすすめ

### B. React Hooks

参考サイト: https://ja.reactjs.org/docs/hooks-intro.html

#### 確認ポイント

1. [1](https://ja.reactjs.org/docs/hooks-intro.html), [2](https://ja.reactjs.org/docs/hooks-overview.html), [3](https://ja.reactjs.org/docs/hooks-state.html), [4](https://ja.reactjs.org/docs/hooks-effect.html), [5](https://ja.reactjs.org/docs/hooks-rules.html)を読んで理解する
2. 基本のフックを使って簡単なアプリを作ってみる
3. [6](https://ja.reactjs.org/docs/hooks-custom.html), [7](https://ja.reactjs.org/docs/hooks-reference.html), [8](https://ja.reactjs.org/docs/hooks-faq.html)に目を通す
4. カスタムフックを作ってみる（上記で作ったアプリを元にしても良い）

#### 備考

- クラスコンポーネントで書かれたコードをフックを使って関数コンポーネントに書き直してみることは学習や実務では意味がある（しかし、理解する上では対応づけは必須ではない）

### C. React Redux

参考サイト: https://react-redux.js.org

#### 確認ポイント

1. [Basic Tutorial](https://react-redux.js.org/introduction/basic-tutorial)を大まかに理解する
2. [Redux](https://redux.js.org/introduction/getting-started)のドキュメントを参照し、概要を理解する
3. [React Redux Hooks API](https://react-redux.js.org/api/hooks)を理解する
4. Hooks APIを使って何か作ってみる
5. [Redux Style Guide](https://redux.js.org/style-guide/style-guide)を大まかに理解する

#### 備考

- Hooks以前の書き方は学ぶ必要はないが、現状ではいいドキュメント構成になっていない
- Reduxを活用するには、DevToolsの利用やmiddlewareの理解がポイントである（今回のカリキュラム外）

### D. React Tracked

参考サイト: https://react-tracked.js.org

#### 確認ポイント

1. [Quick Start](https://react-tracked.js.org/docs/quick-start)で動作を確認する
2. [Basic Tutorial](https://react-tracked.js.org/docs/tutorial-01)を動作させ理解する
3. [Intermediate Tutorial](https://react-tracked.js.org/docs/tutorial-03)を動作させ理解する
4. 学んだことを応用して何か作ってみる
5. [Recipes](https://react-tracked.js.org/docs/recipes)を参照し、概要を理解する

#### 備考

- Global stateとして使う場合は、React Reduxの概念や考え方が参考になる
- React Trackedの利用法は、Pure React(Context + Hooks)での場合と同様のため、React Trackedを使わないとしても応用できる
