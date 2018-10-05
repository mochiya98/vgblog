---
title: Treasure2018に参加した
date: 2018-10-06 19:29:05
---
日本語得意じゃないのでJavaScriptで書きました
~~正直JS書いてるの2時間ぐらい、本体の記事描くのに時間掛かった~~
Edited: いくら演出込みで内容とはいえ、流石に読む側のユーザー体験悪すぎたので2倍速にしました。~~こういうのがあるからメインコンテンツにアニメーション付けるのはUX的にギルティなんですよね本来。背景とか読むのに影響しない所で使おう！~~

## treasure2018

{% raw %}<noscript>{% endraw %}

### day1/2 Go言語

- アツイGo言語推し
- TDDのススメ
	- 伝わらないt_wadaネタ
- 実習
	- SEGVつらい
- 焼肉弁当
	- おいしい
- 「コンフォートゾーンの外側」
	- by 小賀さん
- ポップコーン
	- おいしかった
	- 珍しい味付き、抹茶とかいちごとか

### day3 フロントエンド(React)

- 水を得た魚!
	- (JS大好き)
- チョコケーキ
	- おいしかった

### day4 WebAPI

What is REST?
- 設計は適材適所
- 共通認識が大事
	- すべての解
- たこやき
	- ?
	- (にしか見えないシュークリーム)
		- おいしかった
- コロッケ
	- ?
	- (そっくりなレアチーズケーキ)
		- おいしかった

### day5 中間課題

- Weblioランダムでブレスト
	- 今ならこれはしない
- API設計
- ChupaChupsタワー
	- すごい多い
	- あま～い
- LT会にて登壇
	- 「言語を[愛]するということ」

### day6/7(土日)

ひたすらGoのテスト書いてた

### day8 発表とセキュリティ

- 発表
	- みんなすごい作品
- セキュリティ
	- 脆弱性絶対見つけるマン
		- XSS!
		- SQLInjection!
		- SessionHijack!
	- たまたまXSS
		- 偶然なら仕方ない
		- ヲタクなのでこの手の話好き
- 食べ物
	- THE BAUMBAR
	- だいだい

### day9 データベース

- 設計とE-R図
- 無限に悩める!!!
- うまい棒
	- の山
	- 最終日までお世話に

### day10 チーム開発(講義)

- teaming
- スクラム開発体験
	- 楽しい＆ためになる
- かき氷
	- おいしかった

### day11 AWSセットアップ/アイデア出し

- AWS完全に理解してそうな人の解説
- アイデア出し、とても参考になった

### 残りはチーム制作

- 良いメンバーだった!
	- 最高!
	- 仲良くできて良かった

### まとめ

- みんな良い人＆つよい
	- 360°スゴイ
- かけがえのない経験
	- 人類、一度はtreasure参加すべき

{% raw %}</noscript>{% endraw %}

{% asset_path canvas %}

{% raw %}
<style>
.post-content ul{list-style-type:none;padding-left:1em;margin:0;}
.post-content ul>li{position:relative;top:0;left:0;}
.post-content ul>li:before{content:"＊";position:absolute;top:0;left:-1rem;color:#42b983;}
#drawcanvas-container{text-align:center;}
.drawcanvas-manager,.drawcanvas-manager *{margin:0;padding:0}
.drawcanvas-manager{position:relative;top:0;left:0;display:inline-block;}
.drawcanvas-manager>canvas{display:block;max-width:100%;}
.drawcanvas-manager>canvas:nth-child(2){position:absolute;top:0;left:0;}
</style>
<div id="drawcanvas-container"></div>
{% endraw %}

### わいわい

楽しかったし、とても貴重な経験ができました
エンジニアは是非参加すべき

### おまけ: 食べ物集

#### カカオの花
{% asset_img kakao.jpg カカオの花 %}
[カカオの花](https://www.laterre.com/products/products_000204.html)

#### たこ焼きにしか見えないシュークリーム　スペシャル
{% asset_img stakosp640.gif たこ焼きにしか見えないシュークリーム　スペシャル %}
[たこ焼きにしか見えないシュークリーム　スペシャル](https://www.tora-ya.co.jp/i/10065-2)

#### コロッケそっくりなレアチーズケーキ
{% asset_img skoroke640.gif コロッケそっくりなレアチーズケーキ %}
[コロッケそっくりなレアチーズケーキ](https://www.tora-ya.co.jp/i/10066)

#### THE BAUMBAR
{% asset_img hero_baumbar.jpg THE BAUMBAR %}
[THE BAUMBAR](https://tokyo-campanella.com/products/baumbar.html)

#### 橙 daidai
[橙 daidai](https://tabelog.com/tokyo/A1317/A131705/13009763/)

<script src="{% asset_path draw.js %}"></script>
