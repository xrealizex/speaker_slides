---
theme: default
title: Vue.js 学習の振り返り
highlighter: shiki
colorSchema: light
class: text-center
drawings:
  persist: false
transition: fade-out
mdc: true
htmlAttrs:
  lang: ja
---

# <span class="text-green-600">Vue.js</span> 学習の振り返り<carbon-logo-vue />
<div>
  <span class="mr-6">2024/10/22</span>
  <span>hiro</span>
</div>
<div class="abs-br m-6 flex gap-0">
  <a href="https://x.com/hiro_xre" target="_blank" alt="GitHub" title="Open in X"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-x />
  </a>
  <a href="https://github.com/xrealizex" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
---

# アジェンダ
1. はじめに
2. チュートリアル
3. chibivue
4. イベント参加
6. おわりに

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# はじめに
<div class="mt-10">
  <p>Vue.jsの学習を振り返り......</p>
  <p>どのような学習したか</p>
  <p>どのようなことがあったか</p>
  <p>について話していきます</p>
  <p>少しでも参考になるものがあれば幸いです！</p>
</div>

---
transition: fade-out
---

# チュートリアル

https://ja.vuejs.org/tutorial/#step-1

実はチュートリアルのはじめに大事なことが書いてありました
> このチュートリアルの目的はブラウザーで Vue で作業することがどのような感じなのかいち早く体験してもらうことです。網羅的な内容を目指すものではないため、すべてを理解してから次に進む必要はありません。しかしながら、すべてを完了したあと、各項目についてより詳しく説明しているガイドを必ずお読みください。

ここで大事な部分は
> すべてを完了したあと、各項目についてより詳しく説明しているガイドを必ずお読みください。

です

**ガイド**読んでいますか？

---
transition: fade-out
layout: image
image: ./public/images/computed.png
---

---
transition: fade-out
layout: image
image: ./public/images/computed-guide.png
---

---
transition: fade-out
---

# つまり？

何が言いたいかというと...

今からでもチュートリアル内のリンクを追っていくだけで得られるものがあるはず

先ほどの例ではcomputed定義とメソッド定義でどのような違いがあるか認識できました！

---
transition: fade-out
---

# まとめ

実際ここまで知らなくても動作上は問題ない場合が多いけど......

* Vueが提供してくれているもの（computedなど）の特徴を知っておくことで

* 各APIやビルトインの**正しい使い方**を理解し

* Vueのエコシステムの恩恵を最大限享受できる

と思います

プロダクトをどんどんスマートにしていきましょう！

---
transition: fade-out
---

# chibivue

https://ubugeeei.github.io/chibivue/

著者はubugeeei (うぶげ)さん

chibivueとは？

> * Vue.js についての理解を深める
>
>   Vue.js とは何なのか? どのような構成で成り立っているのか?
> * Vue.js の基本的な機能を実装できるようになる
>
>   実際に基本的な機能を実装してみる
> * vuejs/core のソースコードを読めるようになる
>
>   実装と本家のコードとの関連を把握して，実際にどんな実装になっているのかを把握する

何やら難しそう......🤔
---
transition: fade-out
---

# 悩み

実際難しいです（まだ全然完走できていない）

しかしそれ以上に楽しいです

いずれにせよ......

業務では出会わない設計手法・コードが盛りだくさん

ひとりで**完全に理解した**状態になるのは難しい

どうしよう......🤔
---
transition: fade-out
---
# イベント

そんなとき......

著者のubugeeeiさんに直接教えて頂く機会がありました！

私にとって本当に貴重な経験でした（超絶感謝）

---
transition: fade-out
---

# どうだった？

* DI・DIPのおおまかな理解が得られた
* Vue.js/coreのディレクトリ構成が理解できVueがより楽しくなった
  * ドキュメントにない部分で詰まった時にソースコードを読みにいけるようになった
* 普段書かないコードに触れることで思考の幅が広がった
* 刺激になった
* Vueコミュニティに貢献したいと思うようになった

---
transition: fade-out
---

# ちょっと恩返し

恩返しの第一歩として記事を書きました

[vuejs/core のソースコードを探検する楽しさ](https://zenn.dev/comm_vue_nuxt/articles/413285d321e495)

記事を書くことで得られたことは

* 理解できたことの整理
* アウトプットによる理解の深堀り
* 自身の認知向上
* Vueコミュニティの認知（Vueコミュニティへの貢献）

---
transition: fade-out
---

# 所感

自分だけしか知らないなんてことはないですし

コミュニティへの貢献にもなるので

アウトプットの大切さを実感しました

---
transition: fade-out
---

# まとめ

何が言いたいかというと......

* chibivueを通してVueの内部実装が大まかに分かる
  * Vueがより楽しくなる
* 分からないことがあったら行動を起こしてみる
  * 誰かしら助けてくれるはず
  * 自己成長のチャンスになる
* アウトプットしてみる
  * コミュニティに貢献できる
  * 誰か見てくれている（今回の登壇も記事がきっかけでした）

---
transition: fade-out
---

# 補足

chibivueにはDiscord Serverがあります！

https://discord.gg/aVHvmbmSRy

参加するだけで得られることが多いです

参加しない理由がないです

何が得られるかは是非ご自身の目でご確認を！

---
transition: fade-out
---

# イベント参加

以下の目的を持ってイベントに参加していました

* エンジニアとしてキャリアスタートしたばかりで知り合いがいない
  * 知り合いが欲しい
* 社内のエンジニアとしか技術的な交流がない
  * 価値観や技術レベルを俯瞰したい
* 自己学習のモチベーションが続かない
  * 刺激や危機感を得たい
* 無理のないスケジュールで
  * イベント参加を苦にしたくない

---
transition: fade-out
---

# イベント - 1

Vue.js v-tokyo Meetup #19

2024/03/06(水) @株式会社オプティム

メインセッション: Vue 3.4

はじめて参加したオフラインイベント

この頃はセッションの内容をあまり理解できていなかった

Xで交流のあった方何人かと顔合わせできた

雰囲気を楽しんでいた

---
transition: fade-out
---

# どうだった？

* 純粋に楽しかった
* 温たかいコミュニティだなと感じた
* 自身の情報感度の低さを痛感した
* 自身の技術力の低さを痛感した

次も行きたい！

もっと頑張らないと！

---
transition: fade-out
---

# イベント - 2

Vue.js v-tokyo Meetup #21

2024/07/26(金) @Pleasanter Lounge

メインセッション: Nuxt4

Vue関連では2回目の参加となったイベント

Nuxtなんもわからん状態だったので必死にキャッチアップした記憶

各セッションの内容が大体分かるようになっていて少し成長を感じた

知り合いも少し増えていた

---
transition: fade-out
---

# どうだった？

* コミュニティの温たかさを再認識した
* 技術面でも楽しめるようになっていた
* 情報感度が上がっていた

セッション楽しい！

コミュニティ楽しい！

---
transition: fade-out
---

# イベント - 3

Vue Fes Japan 2024

2024/10/19(土) @大手町プレイス ホール＆カンファレンス

今年一番のイベント

全てにおいて最高に楽しかった

スタッフとして参加したのははじめて

---
transition: fade-out
---

# どうだった？

* 会場が大きくてびっくりした
* 参加者が多くてびっくりした
* 熱量がすごくてびっくりした
* 海外の著名人が近くにいてびっくりした
* びっくりし過ぎて気を失ってしまった

---
transition: fade-out
---

# 支えてくれている人がいる

これだけの規模のイベントを準備・実行するにはどれだけの時間や苦労がかかるか

仕事もある中でイベント準備もしてくれている

そういった方々がいる中で楽しさや便利さを享受している

---
transition: fade-out
---

# 支える側になる

そういったことに気づけたなら支える側になりたい

コミュニティ運営もOSSコントリビュートも

できることからはじめたい

これを聞いて頂いている方も是非Vueコミュニティへ！

---
transition: fade-out
---

# まとめ

何が言いたいかというと......


---

# Components

<div grid="~ cols-2 gap-4">
<div>

You can use Vue components directly inside your slides.

We have provided a few built-in components like `<Tweet/>` and `<Youtube/>` that you can use directly. And adding your custom components is also super easy.

```html
<Counter :count="10" />
```

<!-- ./components/Counter.vue -->
<Counter :count="10" m="t-4" />

Check out [the guides](https://sli.dev/builtin/components.html) for more.

</div>
<div>

```html
<Tweet id="1390115482657726468" />
```

<Tweet id="1390115482657726468" scale="0.65" />

</div>
</div>

<!--
Presenter note with **bold**, *italic*, and ~~striked~~ text.

Also, HTML elements are valid:
<div class="flex w-full">
  <span style="flex-grow: 1;">Left content</span>
  <span>Right content</span>
</div>
-->

---
class: px-20
---

# Themes

Slidev comes with powerful theming support. Themes can provide styles, layouts, components, or even configurations for tools. Switching between themes by just **one edit** in your frontmatter:

<div grid="~ cols-2 gap-2" m="t-2">

```yaml
---
theme: default
---
```

```yaml
---
theme: seriph
---
```

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-default/01.png?raw=true" alt="">

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-seriph/01.png?raw=true" alt="">

</div>

Read more about [How to use a theme](https://sli.dev/guide/theme-addon#use-theme) and
check out the [Awesome Themes Gallery](https://sli.dev/resources/theme-gallery).

---

# Clicks Animations

You can add `v-click` to elements to add a click animation.

<div v-click>

This shows up when you click the slide:

```html
<div v-click>This shows up when you click the slide.</div>
```

</div>

<br>

<v-click>

The <span v-mark.red="3"><code>v-mark</code> directive</span>
also allows you to add
<span v-mark.circle.orange="4">inline marks</span>
, powered by [Rough Notation](https://roughnotation.com/):

```html
<span v-mark.underline.orange>inline markers</span>
```

</v-click>

<div mt-20 v-click>

[Learn more](https://sli.dev/guide/animations#click-animation)

</div>

---

# Motions

Motion animations are powered by [@vueuse/motion](https://motion.vueuse.org/), triggered by `v-motion` directive.

```html
<div
  v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }"
  :click-3="{ x: 80 }"
  :leave="{ x: 1000 }"
>
  Slidev
</div>
```

<div class="w-60 relative">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-square.png"
      alt=""
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-circle.png"
      alt=""
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-triangle.png"
      alt=""
    />
  </div>

  <div
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Slidev
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 30, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

[Learn more](https://sli.dev/guide/animations.html#motion)

</div>

---

# LaTeX

LaTeX is supported out-of-box. Powered by [KaTeX](https://katex.org/).

<div h-3 />

Inline $\sqrt{3x-1}+(1+x)^2$

Block
$$ {1|3|all}
\begin{aligned}
\nabla \cdot \vec{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \vec{B} &= 0 \\
\nabla \times \vec{E} &= -\frac{\partial\vec{B}}{\partial t} \\
\nabla \times \vec{B} &= \mu_0\vec{J} + \mu_0\varepsilon_0\frac{\partial\vec{E}}{\partial t}
\end{aligned}
$$

[Learn more](https://sli.dev/features/latex)

---

# Diagrams

You can create diagrams / graphs from textual descriptions, directly in your Markdown.

<div class="grid grid-cols-4 gap-5 pt-4 -mb-6">

```mermaid {scale: 0.5, alt: 'A simple sequence diagram'}
sequenceDiagram
    Alice->John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
B[Text] --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```

```plantuml {scale: 0.7}
@startuml

package "Some Group" {
  HTTP - [First Component]
  [Another Component]
}

node "Other Groups" {
  FTP - [Second Component]
  [First Component] --> FTP
}

cloud {
  [Example 1]
}

database "MySql" {
  folder "This is my folder" {
    [Folder 3]
  }
  frame "Foo" {
    [Frame 4]
  }
}

[Another Component] --> [Example 1]
[Example 1] --> [Folder 3]
[Folder 3] --> [Frame 4]

@enduml
```

</div>

Learn more: [Mermaid Diagrams](https://sli.dev/features/mermaid) and [PlantUML Diagrams](https://sli.dev/features/plantuml)

---
foo: bar
dragPos:
  square: 691,32,167,_,-16
---

# Draggable Elements

Double-click on the draggable elements to edit their positions.

<br>

###### Directive Usage

```md
<img v-drag="'square'" src="https://sli.dev/logo.png">
```

<br>

###### Component Usage

```md
<v-drag text-3xl>
  <carbon:arrow-up />
  Use the `v-drag` component to have a draggable container!
</v-drag>
```

<v-drag pos="663,206,261,_,-15">
  <div text-center text-3xl border border-main rounded>
    Double-click me!
  </div>
</v-drag>

<img v-drag="'square'" src="https://sli.dev/logo.png">

###### Draggable Arrow

```md
<v-drag-arrow two-way />
```

<v-drag-arrow pos="67,452,253,46" two-way op70 />

---
src: ./pages/imported-slides.md
hide: false
---

---

# Monaco Editor

Slidev provides built-in Monaco Editor support.

Add `{monaco}` to the code block to turn it into an editor:

```ts {monaco}
import { ref } from 'vue'
import { emptyArray } from './external'

const arr = ref(emptyArray(10))
```

Use `{monaco-run}` to create an editor that can execute the code directly in the slide:

```ts {monaco-run}
import { version } from 'vue'
import { emptyArray, sayHello } from './external'

sayHello()
console.log(`vue ${version}`)
console.log(emptyArray<number>(10).reduce(fib => [...fib, fib.at(-1)! + fib.at(-2)!], [1, 1]))
```

---
layout: center
class: text-center
---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
