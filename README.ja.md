<div align="center">

# XXD Panel 344｜ミニチュアの台座

**写真の主役を足もとの地面ごと切り出し、角の丸い台座に立つミニチュア模型にします。**

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 344 · 01 · 田舎の礼拝堂"><br><sub>01 · 田舎の礼拝堂</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 344 · 02 · ワーゲンバス"><br><sub>02 · ワーゲンバス</sub></td>
  </tr>
</table>

<p align="center"><sub>上が元の写真、下がこのスタイルで描き直したものです。</sub></p>

## これは何か

Claude Code や Codex などの AI エージェント向け Skill です。写真を 1 枚渡すと、Panel 344 の原文プロンプトに沿って PNG の完成作品を描きます。

- **どんな絵になるか：** 主役と足もとの小さな地面を切り出し、角の丸い四角い台座に立つミニチュア模型にします。斜め上から見下ろし、台座の縁はすべて見えます。どの塊もずんぐりと丸く角が落とされ、ソフト粘土の小さなフィギュアのようで、木の葉は小さな球の集まり、周りのごちゃごちゃは整然と置かれたいくつかの小物にまとめられます。表面はマットで、柔らかな拡散光と接地部の淡い影だけがあり、色は写真から取ったパステル調の同系色、台座はグレーがかった白です。模型は中央に置かれ、周りは地平線のない清潔な淡い単色の空間です。正面には模型と同じ素材の丸い立体文字が一語だけ付き、写真側には文字を入れません。
- **キーワード：** アイソメトリックのミニチュア · 角丸の四角い台座 · 斜め上からの俯瞰 · 丸い粘土の塊 · パステルの同系色 · 模型に付いた立体文字
- **作れるもの：** 上下比較（上に写真、下にデザイン）、左右比較、デザインのみ、またはスマホ／タブレット／PC／ウォッチの壁紙セット。複数選択でき、比率やピクセル数も自由です。
- **これは違う：** フィルターでもテンプレートでもありません。毎回あなたの写真から描き直し、写真 1 枚ごとに独立したタスクです。

## 3 ステップで始める

**1. インストール。** Claude Code、Codex など Skills 対応のエージェントで使えます：

```bash
npx skills add https://github.com/nevertoday/xxd-panel-344 --skill xxd-panel-344
```

インストール後、エージェントのセッションを開き直してください。このリポジトリを `git clone` して `~/.claude/skills/xxd-panel-344` または `~/.codex/skills/xxd-panel-344` にリンクしても使えます。

**2. エージェントが画像を生成できるか確認。** この Skill 自体は画像モデルを持たず、エージェントの画像生成（GPT Image 2 推奨）を使います。

- Codex は内蔵の画像生成が有効ならそのまま使えます。
- Claude Code など内蔵の画像生成がないエージェントは、OpenAI 互換の画像 API が必要です。5 分ほどで設定できます：[画像生成の設定](#画像生成の設定)。

わからなければそのまま試してください。生成できない場合は、作業を始める前に Skill が止まって知らせます。

**3. 写真を送って、ひとこと：**

> xxd-panel-344 でこの写真を 3:4 の上下比較ポスターにして、日本語のタイトルを付けて。

指示がそろっていればすぐ生成し、足りない点（レイアウト、比率、文字）は 1〜2 問ほど質問します。完成した PNG は `~/Desktop/xxd/xxd-panel-344/` の新しいフォルダに保存されます。

## 向いている写真

**向いている**

- 単体で切り出せる主役：小さな家、車、塔、一本の木
- 暮らしの気配がある小さな店や一角：カフェの店先、新聞スタンド、ベランダの隅
- 構図が平凡、背景が散らかっている、主役が小さい写真（台座に切り出し、遠景を省きます）

**あまり向いていない**

- 通り全体、風景全体、室内全体を残したい場合（一つの単体だけを模型にします）
- 人物の顔立ちや本物の素材感を見せたい写真（すべて丸いフィギュアに統一されます）
- 正面からの立面、フラットなベクター、つやのあるプラスチック、彩度の高いキャンディカラーを求める場合

## サンプル

下の画像はすべて、この Skill が写真 1 枚から作った完成作品です。上下比較と左右比較では別の写真を使っています。

### 上下比較：上が写真、下がデザイン

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 344 · 01 · 田舎の礼拝堂"><br><sub>01 · 田舎の礼拝堂</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 344 · 02 · ワーゲンバス"><br><sub>02 · ワーゲンバス</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 344 · 03 · 赤いトラクター"><br><sub>03 · 赤いトラクター</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 344 · 04 · 風車"><br><sub>04 · 風車</sub></td>
  </tr>
</table>

<details>
<summary>さらに 16 枚を見る</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 344 · 05 · ツリーハウス"><br><sub>05 · ツリーハウス</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 344 · 06 · アルパカ"><br><sub>06 · アルパカ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 344 · 07 · 小舟"><br><sub>07 · 小舟</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 344 · 08 · 水上コテージ"><br><sub>08 · 水上コテージ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 344 · 09 · 花屋の店先"><br><sub>09 · 花屋の店先</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 344 · 10 · 蒸気機関車"><br><sub>10 · 蒸気機関車</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 344 · 11 · ラクダ"><br><sub>11 · ラクダ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 344 · 12 · スケートボード"><br><sub>12 · スケートボード</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 344 · 13 · ハリネズミ"><br><sub>13 · ハリネズミ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 344 · 14 · 水車小屋"><br><sub>14 · 水車小屋</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 344 · 15 · 消火栓"><br><sub>15 · 消火栓</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 344 · 16 · キャンプのテント"><br><sub>16 · キャンプのテント</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 344 · 17 · クラシックカー"><br><sub>17 · クラシックカー</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 344 · 18 · ガラスの温室"><br><sub>18 · ガラスの温室</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 344 · 19 · 小島"><br><sub>19 · 小島</sub></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 344 · 20 · ゾウ"><br><sub>20 · ゾウ</sub></td>
  </tr>
</table>

</details>

### 左右比較：左が写真、右がデザイン

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 344 · 21 · 自動販売機"><br><sub>21 · 自動販売機</sub></td>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 344 · 22 · 灯台"><br><sub>22 · 灯台</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 344 · 23 · 給水塔"><br><sub>23 · 給水塔</sub></td>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 344 · 24 · 信号機"><br><sub>24 · 信号機</sub></td>
  </tr>
</table>

<details>
<summary>さらに 16 枚を見る</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 344 · 25 · 時計塔"><br><sub>25 · 時計塔</sub></td>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 344 · 26 · パンダ"><br><sub>26 · パンダ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 344 · 27 · リス"><br><sub>27 · リス</sub></td>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 344 · 28 · ラテ"><br><sub>28 · ラテ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 344 · 29 · 多肉植物の鉢"><br><sub>29 · 多肉植物の鉢</sub></td>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 344 · 30 · 路上のサックス奏者"><br><sub>30 · 路上のサックス奏者</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 344 · 31 · 壁際の自転車"><br><sub>31 · 壁際の自転車</sub></td>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 344 · 32 · カラフルな小さな家"><br><sub>32 · カラフルな小さな家</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 344 · 33 · 雪だるま"><br><sub>33 · 雪だるま</sub></td>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 344 · 34 · カボチャ"><br><sub>34 · カボチャ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 344 · 35 · 雄ジカ"><br><sub>35 · 雄ジカ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 344 · 36 · ラズベリーケーキ"><br><sub>36 · ラズベリーケーキ</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-37.png" alt="XXD Panel 344 · 37 · 桜の枝"><br><sub>37 · 桜の枝</sub></td>
    <td width="50%"><img src="./assets/examples/sample-38.png" alt="XXD Panel 344 · 38 · メリーゴーラウンド"><br><sub>38 · メリーゴーラウンド</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-39.png" alt="XXD Panel 344 · 39 · ウマ"><br><sub>39 · ウマ</sub></td>
    <td width="50%"><img src="./assets/examples/sample-40.png" alt="XXD Panel 344 · 40 · ヒツジ"><br><sub>40 · ヒツジ</sub></td>
  </tr>
</table>

</details>

## こう言えば OK

パラメータを覚える必要はありません。そのまま伝えてください：

| やりたいこと | こう言う |
|---|---|
| 上下比較 | 3:4 の上下比較にして |
| 左右比較 | 16:9 の左右比較で、左に写真 |
| デザインのみ | 写真なしでデザインだけ、9:16 縦長 |
| 壁紙セット | スマホ、タブレット、PC、ウォッチの壁紙を統一感のあるセットで |
| 複数の比率 | 同じ写真で 1:1、3:4、16:9 を 1 枚ずつ |
| 自分の文字 | タイトルは「風の通り道」、一字も変えないで |
| 文字なし | 文字は一切入れないで |
| 文字の言語 | 文字は英語で |
| フォルダごと | このフォルダの写真を全部上下比較にして |
| 前回と同じ | 前回の設定で |

コマンドラインが好みなら、パラメータは上と一対一で対応します：

```text
/xxd-panel-344 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ja-JP
/xxd-panel-344 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-344 ./photos --mode left-right --size 16:9 --text prompt --locale en-US
```

すべてのパラメータは[パラメータ一覧](#パラメータ一覧)にあります。

## よくある質問

**元の写真は必ず入りますか？** いいえ。「デザインだけ」や壁紙なら、画面全体がデザインになります。

**文字は誰が書くのですか？** 既定では画像モデルが写真を見て書き、あなたは言語だけを選びます。自分の文字を指定すれば一字も変えずに使い、文字なしにもできます。事実に見える情報（地名、日付、数字）は、あなたが渡したものか写真に写っているものだけを使い、作りません。

**気に入らなかったら？** 「もう 1 枚」と言ってください。前の結果を直すのではなく元の写真から描き直すので、毎回違う結果になります。

**まとめて処理すると混ざりませんか？** 混ざりません。写真ごとに個別に生成し、ほかの写真の色、文字、構図を借りません。設定は一括で 1 回だけ聞きます。

**写真はどこに送られますか？** エージェントが使う画像モデルにだけ送られます。Skill はほかへアップロードせず、接続先やキーも表示しません。

**ほかの Panel との関係は？** XXD Panel は番号ごとに 1 つのスタイルで、互いに独立しています。好きなものだけ入れてかまいません。写真に合うスタイルを AI に選ばせたい、複数を比べたいときは、カタログ [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all) を使ってください。

## 原文プロンプト

このスタイルは小小東が書いた[原文プロンプト](references/original-prompt/zh-CN.md)（中国語）だけで決まります。Skill はあなたが選んだレイアウト、サイズ、文字の設定を末尾に足すだけで、要約・翻訳・書き換えはしません。

参考訳（読むためのもので、画像生成には使いません）：[English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 画像生成の設定

`gpt-image-2`（または互換モデル）を提供する OpenAI 互換 API とその API キーが必要です。次の手順は別の設定ファイルを作るので、Codex 本体の設定には影響しません：

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # または互換エンドポイント
env_key = "XXD_IMAGE_API_KEY"
EOF

# ~/.zshrc か ~/.bashrc に書き、エージェントからも読めるようにする
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=あなたのキー' >> ~/.zshrc
```

ターミナルとエージェントを開き直してから、この Skill のフォルダで一度確認します：

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true` なら成功です。結果は使えるかどうかだけで、接続先やキーは表示されません。Codex がすでに互換 API で画像を生成できるなら、この手順は不要です。

## パラメータ一覧

| パラメータ | 値 |
|---|---|
| `--mode` | `top-bottom` 上下比較 · `left-right` 左右比較 · `design-only` デザインのみ · `wallpaper-pack` 4 端末の壁紙；複数選択可 |
| `--size` | `auto` おすすめ · `source` 写真に合わせる · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · ピクセル指定（例 `2160x3840`）；複数選択可 |
| `--text` | `prompt` 写真から書く · `exact` あなたの文字（`--copy "…"` と併用） · `none` 文字なし |
| `--locale` | 文字の言語。例：`zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` 統一感のあるセット · `independent` 4 枚それぞれ独立 |
| `--wallpaper-size` | 端末ごとのピクセル。例：`phone=1440x3200,desktop=3840x2160` |
| `--out` | 出力先のルートを変更（既定は `~/Desktop/xxd/xxd-panel-344/`） |
| `--prefs` | `last` 前回どおり · `edit` 前回から変更 · `new` 選び直す · `off` 今回は記録しない · `clear` 記録を消す |

- 値がそろっていれば質問せず、足りないものだけを聞きます。`photo.jpg` の代わりにフォルダを渡すと一括処理になります。
- 組み合わせは 1 枚ずつ生成します。2 モード × 3 サイズ = 6 枚で、どれも切り抜きではなくキャンバスごとに構図を組み直します。
- 比較画像は正確に 50:50 です。通常はモデルがデザイン側だけを描き、スクリプトが元の写真をそのまま隣に並べるので、境目は中央で写真も変わりません。
- ファイル名は `source-001-street-top-bottom-3x4-1152x1536.png` のような形式で、すべて 1 つのタスクフォルダに平置きされます。
- 記録するのはレイアウト、サイズ、文字の方式と言語だけで、写真、文字、キーは残しません。

<!-- xxd-readme-ads:start -->
## XXD について

XXD は Xiaoxiaodong のブランド名略称です。本プロジェクトの作成・管理：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## Xiaoxiaodong マルチプラットフォーム会員 · 年額 CNY 699

> **広告表示：** 以下のQRコード、会員および有料サービスのリンクはXXDの広告情報です。スキャンや購入は任意であり、オープンソースの利用には影響しません。

年額会員ひとつで、**Knowledge Planet＋XXD会員プロンプトライブラリ＋すべてのGeneral Skills会員**の3つを利用できます。別々に購入する必要はありません。

<!-- xxd-panel-command-system:start -->

### Skills の連携方法

| 区分 | 含まれるもの | 役割 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 利用可能な番号付きSkillsを検出し、画像・テーマ・用途から推薦し、複数スタイルや一括タスクを整理します。 |
| **Soldier** | `xxd-panel-NNN` | 各番号が固有の原文プロンプトと美学に従い、Generalから割り当てられた具体的な作業を完成させます。 |

<!-- xxd-panel-command-system:end -->

### 会員の内容

1. **WeChatでの一対一AI学習・プロジェクト相談**
   下のQRコードからXiaoxiaodongのWeChatを追加し、AI学習、ツール、実際のプロジェクトについて一対一で相談できます。代表的な質問は会員向けコンテンツに整理されます。
2. **継続更新する会員プロンプトライブラリ**
   [XXD会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)には現在約3.2万件のプロンプトがあり、10万件超を目標に継続して拡充します。
3. **すべてのGeneral Skillsと利用サポート**
   ひとつの会員で全General Skillsを利用でき、使い方に困ったときは案内やQ&Aを受けられます。
4. **必要性の高い要望を優先**
   会員から寄せられた頻度と必要性の高いプロンプトやSkillsは、優先して検討・開発します。

### 開設方法

- [会員サイトから自分で開設](https://vip.xiaoxiaodong.ai/)できます。
- または下のQRコードからXiaoxiaodongのWeChatを追加し、一対一で開設サポートを受けられます。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Xiaoxiaodongへの連絡" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## ライセンス

本プロジェクト（Skill、プロンプト、スクリプト、文書、付属サンプル画像を含む）は **PolyForm Noncommercial License 1.0.0** の下で提供されます。完全な法的条文は [LICENSE](LICENSE)、公式ページは <https://polyformproject.org/licenses/noncommercial/1.0.0> を参照してください。

分かりやすく言うと：

- 個人は学習、研究、実験、テスト、趣味のプロジェクト、私的娯楽に使用できます。慈善団体、教育機関、公的研究・安全・保健機関、環境保護団体、政府機関も使用できます。
- **非商業目的**であれば、使用、複製、変更、派生物の作成、共有が可能です。共有時には本ライセンス（または上記リンク）と、作者が示したすべての `Required Notice:` 文を添付する必要があります。
- 商用製品・サービス、有料納品、アクセス権やライセンスの販売、商業利用につながることが予想される用途には使用できません。商用利用には著作権者から別途書面による許可を得てください。
- 本契約が付与するのは明記された著作権ライセンスと限定的な特許ライセンスだけです。商標、ブランド名、その他明記されていない権利は付与されず、ライセンスを第三者へ再許諾することもできません。
- 書面で違反通知を受けた場合、32 日以内に遵守状態へ戻り、実際の是正措置を取らなければライセンスは直ちに終了します。特許侵害を書面で主張した場合も特許ライセンスが終了します。
- 内容は法律が認める範囲で「現状のまま」提供され、保証はありません。利用に伴うリスクと損失は利用者が負います。
