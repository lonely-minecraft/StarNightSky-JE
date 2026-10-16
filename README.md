# StarNightSky JE

マインクラフト Java版の夜空に、本物の星空を映すリソースパックです。
星座線や星座名の入った夜空が、太陽や月と一緒に回ります。

Resource packs for Minecraft Java Edition that show a real star sky at night. They need the [Nuit](https://modrinth.com/mod/nuit) mod. Constellation names are in Japanese.

これはマインクラフトの公式の製品ではありません。Mojang や Microsoft が認めたものでも、関わっているものでもありません。
NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.

統合版は [StarNightSky BE](https://github.com/lonely-minecraft/StarNightSky-BE) にあります。

## ダウンロード

夜空の種類ごとに、別々のパックになっています。使いたいものを1つ選んでください。

| 夜空 | ダウンロード(最新版) | 大きさ |
|---|---|---|
| 星だけ | [StarNightSky.zip](https://github.com/lonely-minecraft/StarNightSky-JE/releases/latest/download/StarNightSky.zip) | 0.1MB |
| 星＋星座線 | [StarNightSky_Line.zip](https://github.com/lonely-minecraft/StarNightSky-JE/releases/latest/download/StarNightSky_Line.zip) | 0.5MB |
| 星＋星座線＋星座名 | [StarNightSky_Line_Name.zip](https://github.com/lonely-minecraft/StarNightSky-JE/releases/latest/download/StarNightSky_Line_Name.zip) | 0.7MB |
| 星＋星座線＋星座名＋星座絵 | [StarNightSky_Line_Name_Art.zip](https://github.com/lonely-minecraft/StarNightSky-JE/releases/latest/download/StarNightSky_Line_Name_Art.zip) | 3MB |
| 天の川の見える本物の星空(NASA) | [RealNightSky.zip](https://github.com/lonely-minecraft/StarNightSky-JE/releases/latest/download/RealNightSky.zip) | 9MB |

これまでの版は、[Releases](https://github.com/lonely-minecraft/StarNightSky-JE/releases) にあります。

## 必要なもの

このパックだけでは、夜空は変わりません。次の MOD が必要です。

- [Fabric](https://fabricmc.net/)
- [Fabric API](https://modrinth.com/mod/fabric-api)
- [Nuit](https://modrinth.com/mod/nuit)

## 動作を確認した環境

- Java版 26.2 + Fabric + Nuit で動作を確認しました。
- ほかのバージョンや、NeoForge 版の Nuit では確認していません。

## 入れ方

1. Fabric、Fabric API、Nuit を入れます。
2. ダウンロードした zip を、展開せずに、マインクラフトの `resourcepacks` フォルダに入れます。
   (「設定」→「リソースパック」→「パックフォルダーを開く」で開けます。)
3. 「設定」→「リソースパック」で、入れたパックを有効にします。
4. ワールドに入り、夜になるのを待ちます。

パックは1つだけ有効にしてください。2つ以上を有効にすると、上にあるパックの夜空だけが映ります。

## 知っておいてほしいこと

- マインクラフトの太陽に合わせて、「赤道で見た星空」にしています。日本で見る星空とは、傾きが違います。
- 毎晩、同じ星空が回ります。季節による星空の移り変わりはありません。
- 星空が映るのは、オーバーワールドの晴れた夜だけです。
- マインクラフトにもともとある星(架空の星)は、映らなくなります。太陽と月は、そのまま見えます。
- 星座名は日本語です。東や西の低い空では、星座名が横倒しに見えます。
- 星座絵は、北半球の中緯度から見える範囲の星座にだけあります。南の空の一部には、絵がありません。

## クレジットとライセンス

このパックは、次の素材を使っています。くわしくは [CREDITS.txt](CREDITS.txt) を見てください。それぞれの zip の中にも、そのパックで使った素材の `CREDITS.txt` が入っています。

| 素材 | 出典 | ライセンス |
|---|---|---|
| 星のデータ | Yale Bright Star Catalogue, 5th Revised Ed.(Hoffleit & Warren 1991)、CDS | — |
| 星座線と星座名 | [d3-celestial](https://github.com/ofrohn/d3-celestial)、Copyright (c) 2015 Olaf Frohn | [BSD 3-Clause](LICENSE_d3-celestial.txt) |
| 星座名の文字 | Noto Sans JP | SIL Open Font License 1.1 |
| 星座絵 | シドニー・ホール『ウラニアの鏡』(Urania's Mirror、1824年)。[Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Urania%27s_Mirror) のスキャン画像 | パブリックドメイン |
| 天の川の星空 | [NASA/Goddard Space Flight Center Scientific Visualization Studio](https://svs.gsfc.nasa.gov/4851)、Gaia DR2: ESA/Gaia/DPAC | — |

## 謝辞

このパックは、FlashyReese さんの MOD [Nuit](https://modrinth.com/mod/nuit) があるおかげで、夜空を映すことができます。Nuit は MIT ライセンスで公開されています。このパックに Nuit は含まれていません。

Thanks to FlashyReese for [Nuit](https://modrinth.com/mod/nuit), the mod that makes these skies possible. Nuit is not included in these packs.

## 作者

damun-craft.com
<https://damun-craft.com/>
