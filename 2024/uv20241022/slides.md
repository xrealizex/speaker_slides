---
theme: default
title: Vue.js 学習の振り返り
highlighter: shiki
colorSchema: dark
class: text-center
drawings:
  persist: false
transition: fade-out
mdc: true
htmlAttrs:
  lang: ja
hideInToc: true
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
layout: two-cols
transition: fade-out
hideInToc: true
---

<Title title="hiro（@hiro_xre）" tag="h1" />

<div class="text-xl mt-20">
  <p>toCサービス企業</p>
  <p>Vue.js・TypeScript</p>
  <p>サッカー観戦・美術館・音楽・旅行</p>
  <p>もうすぐエンジニア2年生</p>
</div>

::right::

<CircleIcon class="m-15" src="./public/images/kirua.png" :size="300"/>

---
transition: fade-out
hideInToc: true
---

<Title title="アジェンダ" tag="h1" />
<div class="mt-20">
  <p>1・・・はじめに</p>
  <p>2・・・チュートリアル - ガイド</p>
  <p>3・・・chibivue</p>
  <p>4・・・イベント参加</p>
  <p>5・・・おわりに</p>
</div>

---
layout: center
transition: fade-out
hideInToc: true
---

<Title title="はじめに" tag="h1" />

---
layout: two-cols
transition: fade-out
---

<Title title="はじめに" tag="h1" />
<div class="mt-10">
  <p>Vue.jsの学習を振り返り......</p>
  <p>どのような学習をしてきたか</p>
  <p>どのようなことがあったか</p>
  <p>について話していきます</p>
  <p>気楽に聞いてください！</p>
</div>

::right::

<Tweet id="1823597667974545844" scale="0.75" />

---
layout: center
transition: fade-out
hideInToc: true
---

<Title title="チュートリアル - ガイド" tag="h1" />

---
transition: fade-out
---

<Title title="チュートリアル - ガイド" tag="h1" />

<div class="mt-10">
  <a href="https://ja.vuejs.org/tutorial/#step-1">https://ja.vuejs.org/tutorial/#step-1</a>
  <p>実はチュートリアルのはじめに大事なことが書いてありました</p>
</div>

> このチュートリアルの目的はブラウザーで Vue で作業することがどのような感じなのかいち早く体験してもらうことです。網羅的な内容を目指すものではないため、すべてを理解してから次に進む必要はありません。しかしながら、すべてを完了したあと、各項目についてより詳しく説明しているガイドを必ずお読みください。

ここで大事な部分は
> すべてを完了したあと、各項目についてより詳しく説明しているガイドを必ずお読みください。

です

<p><span class="text-green-600" font-bold>ガイド</span>読んでいますか？</p>

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
hideInToc: true
---

<Title title="つまり？" tag="h1" />

<div class="mt-10" v-click>
  <p><span class="text-green-600" font-bold>今からでも</span>チュートリアル内のリンクを追っていくだけで得られるものがあるはず</p>
  <p>先ほどの例ではcomputed定義とメソッド定義でどのような違いがあるか認識できました！</p>
</div>

---
transition: fade-out
hideInToc: true
---

<Title title="まとめ" tag="h1" />

<div class="mt-10">
  <p>実際ここまで知らなくても動作上は問題ない場合が多いけど......</p>
  <ul>
    <li>Vueが提供してくれているもの（computedなど）の特徴を知っておくことで</li>
    <li>各APIやビルトインの<span class="text-green-600" font-bold>正しい使い方</span>を理解し</li>
    <li>Vueのエコシステムの恩恵を最大限享受できるようになる</li>
    <li>プロダクトがスマートに！</li>
  </ul>
  <br>
  <p>ガイドを読もう</p>
</div>

---
layout: center
transition: fade-out
hideInToc: true
---

<Title title="chibivue" tag="h1" />

---
transition: fade-out
---

<Title title="chibivue" tag="h1" />

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
hideInToc: true
---

<Title title="当時の悩み" tag="h1" />

<div class="mt-10">
  <p>実際難しいです（まだ全然完走できていない）</p>
  <p>しかしそれ以上に楽しいです</p>
  <p>業務では出会わない設計手法・コードが盛りだくさん</p>
  <p><span class="text-green-600" font-bold>ひとりで理解する</span>のは難しい</p>
  <p>どうしよう......🤔</p>
</div>

---
layout: two-cols
transition: fade-out
hideInToc: true
---

<Title title="ペアプロ？" tag="h1" />

<div class="mt-10" v-click>
  <p>そんなとき......</p>
  <p>著者の<span class="text-green-600" font-bold>ubugeeeiさん</span>に</p>
  <p>直接教えて頂く機会がありました！</p>
  <p>私にとって本当に貴重な経験でした（超絶感謝）</p>
</div>

::right::

<Tweet id="1796856202569331006" scale="0.95" v-click/>

---
transition: fade-out
hideInToc: true
---

<Title title="どうだった？" tag="h1" />

<div class="mt-10" v-click>
  <ul>
    <li>DI・DIPのおおまかな理解が得られた</li>
    <li>Vue.js/coreのディレクトリ構成が理解できVueがより楽しくなった
      <ul>
        <li><span class="text-green-600" font-bold>ドキュメントにない部分で詰まった時にソースコードを読みにいけるようになった</span></li>
      </ul>
    </li>
    <li>普段書かないコードに触れることで思考の幅が広がった</li>
    <li>刺激になった</li>
    <li>Vueコミュニティに貢献したいと思うようになった</li>
  </ul>
</div>

---
layout: two-cols
transition: fade-out
hideInToc: true
---

<Title title="ちょっと恩返し" tag="h1" />

<div class="mt-10">
  <p>恩返しの第一歩として記事を書きました</p>
  <p>記事を書くことで得られたことは</p>
  <ul>
    <li>理解できたことの整理</li>
    <li>アウトプットによる理解の深堀り</li>
    <li>自身の認知向上</li>
    <li>Vueコミュニティの認知
      <ul>
        <li>Vueコミュニティへの貢献</li>
      </ul>
    </li>
  </ul>
</div>

::right::

<Tweet id="1797837074244210811" scale="0.75" />

---
transition: fade-out
hideInToc: true
---

<Title title="所感" tag="h1" />

<div class="mt-10" v-click>
  <p>自分だけしか知らないなんてことはないですし</p>
  <p><span class="text-green-600" font-bold>コミュニティへの貢献</span>にもなるので</p>
  <p>アウトプットの大切さを実感しました</p>
</div>

---
transition: fade-out
hideInToc: true
---

<Title title="まとめ" tag="h1" />

<div class="mt-10" v-click>
  <ul>
    <li>chibivueを通してVueの内部実装が大まかに分かる
      <ul>
        <li><span class="text-green-600" font-bold>Vueがより楽しくなる</span></li>
      </ul>
    </li>
    <li>分からないことがあったら行動を起こしてみる
      <ul>
        <li>誰かしら助けてくれるはず</li>
        <li>自己成長のチャンスになる</li>
      </ul>
    </li>
    <li>アウトプットしてみる
      <ul>
        <li><span class="text-green-600" font-bold>コミュニティに貢献できる</span></li>
        <li>誰か見てくれている（今回の登壇も記事がきっかけでした）</li>
      </ul>
    </li>
  </ul>
</div>

---
transition: fade-out
hideInToc: true
---

<Title title="補足" tag="h1" />

<div class="mt-10">
  <p>chibivueにはDiscord Serverがあります！</p>
  <a href="https://discord.gg/aVHvmbmSRy">https://discord.gg/aVHvmbmSRy</a>
  <p><span class="text-green-600" font-bold>参加するだけで</span>得られることが多いです</p>
  <p>参加しない理由がないです</p>
  <p>何が得られるかは是非ご自身の目でご確認を！</p>
</div>

---
layout: center
transition: fade-out
hideInToc: true
---

<Title title="イベント参加" tag="h1" />

---
transition: fade-out
---

<Title title="イベント参加" tag="h1" />

<div class="mt-10">
  <p>以下の目的を持ってイベントに参加していました</p>
  <br>
  <ul v-click>
    <li>エンジニアとしてキャリアスタートしたばかりで知り合いがいない
      <ul>
        <li>知り合いが欲しい</li>
      </ul>
    </li>
    <li>社内のエンジニアとしか技術的な交流がない
      <ul>
        <li>価値観や技術レベルを俯瞰したい</li>
      </ul>
    </li>
    <li>自己学習のモチベーションが続かない
      <ul>
        <li>刺激や危機感を得たい</li>
      </ul>
    </li>
    <li>無理のないスケジュールで
      <ul>
        <li>イベント参加を苦にしたくない</li>
      </ul>
    </li>
  </ul>
</div>

---
layout: two-cols
transition: fade-out
hideInToc: true
---

<Title class="text-green-600" title="Vue.js v-tokyo Meetup #19" tag="h1" />

<div class="mt-5">
  <p>2024/03/06(水) @株式会社オプティム</p>
  <p>メインセッション: Vue 3.4</p>
  <br>
  <p>はじめて参加したオフラインイベント</p>
  <p>この頃はセッションの内容をあまり理解できていなかった</p>
  <p>Xで交流のあった方何人かと顔合わせできた</p>
  <p>雰囲気を楽しんでいた</p>
</div>

::right::

<Tweet id="1765316995904606552" scale="0.85" />

---
transition: fade-out
hideInToc: true
---

<Title title="どうだった？" tag="h1" />

<div class="mt-10" v-click>
  <ul>
    <li>純粋に楽しかった</li>
    <li><span class="text-green-600" font-bold>温たかいコミュニティ</span>だなと感じた</li>
    <li>自身の情報感度の低さを痛感した</li>
    <li>自身の技術力の低さを痛感した</li>
  </ul>
  <p>次も行きたい！</p>
  <p>もっと頑張らないと！</p>
</div>

---
layout: two-cols
transition: fade-out
hideInToc: true
---

<Title class="text-green-600" title="Vue.js v-tokyo Meetup #21" tag="h1" />

<div class="mt-5">
  <p>2024/07/26(金) @Pleasanter Lounge</p>
  <p>メインセッション: Nuxt4</p>
  <br>
  <p>Vue関連では2回目の参加となったイベント</p>
  <p>Nuxtなんもわからん状態だったので必死にキャッチアップした記憶</p>
  <p>各セッションの内容が大体分かるようになっていて少し成長を感じた</p>
  <p>知り合いも少し増えていた</p>
</div>

::right::

<Tweet id="1816063578866352515" scale="0.95" cards="hidden"/>

---
transition: fade-out
hideInToc: true
---

<Title title="どうだった？" tag="h1" />

<div class="mt-10" v-click>
  <ul>
    <li>コミュニティの温たかさを<span class="text-green-600" font-bold>再認識</span>した</li>
    <li>技術面でも楽しめるようになっていた</li>
    <li>情報感度が上がっていた</li>
  </ul>
  <p>セッション楽しい！</p>
  <p>コミュニティ楽しい！</p>
</div>

---
layout: two-cols
transition: fade-out
hideInToc: true
---

<Title class="text-green-600" title="Vue Fes Japan 2024" tag="h1" />

<div class="mt-5">
  <p>2024/10/19(土)</p>
  <p>@大手町プレイス ホール＆カンファレンス</p>
  <br>
  <p>今年一番のイベント</p>
  <p>全てにおいて最高に楽しかった</p>
  <p>スタッフとして参加したのははじめて</p>
</div>

::right::

<Tweet id="1847453039223066870" scale="1.00" />

---
transition: fade-out
hideInToc: true
---

<Title title="どうだった？" tag="h1" />

<div class="mt-10" v-click>
  <ul>
    <li>会場が大きくてびっくりした</li>
    <li>参加者が多くてびっくりした</li>
    <li>熱量がすごくてびっくりした</li>
    <li>海外の著名人が近くにいてびっくりした</li>
    <li>びっくりし過ぎて気を失ってしまった</li>
  </ul>
</div>

---
transition: fade-out
hideInToc: true
---

<Title title="支えてくれている人がいる" tag="h1" />

<div class="mt-10" v-click>
  <p>これだけの規模のイベントを準備・実行するにはどれだけの時間や苦労がかかるか</p>
  <p><span class="text-green-600" font-bold>仕事もある中で</span>イベント準備もしてくれている</p>
  <p>そういった方々がいる中で楽しさや便利さを享受している</p>
  <p>こういったことは自身で体験しないと感じられにくい</p>
</div>

---
transition: fade-out
hideInToc: true
---

<Title title="まとめ" tag="h1" />

<div class="mt-10" v-click>
  <p>イベント参加を通して支えてくれている方々の存在に気づけた</p>
  <p>気づけたなら支える側になりたい</p>
  <p>コミュニティ支援もOSSコントリビュートも</p>
  <p><span class="text-green-600" font-bold>できることから</span>はじめたい</p>
  <p>これを聞いて頂いている方も是非Vueコミュニティへ！</p>
  <p>人としても成長できると思います！</p>
</div>

---
layout: center
transition: fade-out
hideInToc: true
---

<Title title="おわりに" tag="h1" />

---
transition: fade-out
---

<Title title="おわりに" tag="h1" />

<div class="mt-10">
  <p>何をするにしてもアウトプットが大切</p>
  <p>なんだかんだ人とのつながりが大切</p>
  <p>コミュニティ支援は小さなことでも大切</p>
</div>

---
layout: center
transition: fade-out
hideInToc: true
---

<Title title="END" tag="h1" />
