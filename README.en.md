<div align="center">

# XXD Panel 344｜Miniature Plinth

**Cuts out the subject of your photo with a patch of its ground and makes it a miniature model on a rounded plinth.**

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 344 · 01 · Country chapel"><br><sub>01 · Country chapel</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 344 · 02 · Vintage VW bus"><br><sub>02 · Vintage VW bus</sub></td>
  </tr>
</table>

<p align="center"><sub>Top: the original photo. Bottom: the same photo in this style.</sub></p>

## What it is

A Skill for AI agents such as Claude Code and Codex. Give it a photo and it paints a finished PNG following the original Panel 344 prompt.

- **What it looks like:** The subject and a small patch of ground beneath it are cut out and built as a miniature model on a rounded-square plinth, seen from above at an angle with the plinth's whole edge in view. Every block is chunky and rounded like a soft-clay figurine, foliage is made of clusters of tiny balls, and surrounding clutter becomes a few neatly placed small props. The surface is matte, lit only by gentle diffuse light and a faint contact shadow, in a pastel analogous palette drawn from the photo, with a grey-white plinth. The model sits centred in clean, pale, single-colour space with no horizon. One small rounded 3D word in the same material is attached to its front; the photo half carries no text.
- **Keywords:** Isometric miniature · Rounded-square plinth · High angled view · Rounded clay blocks · Pastel analogous palette · 3D word on the model
- **What you can make:** A top–bottom comparison (photo above, design below), a left–right comparison, the design alone, or a wallpaper set for phone, tablet, desktop and watch. Pick several at once, at any ratio or exact pixel size.
- **What it is not:** Not a filter and not a template: every image is redrawn from your photo, and each photo is its own job.

## Get started in three steps

**1. Install.** Works with Claude Code, Codex and other agents that support Skills:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-344 --skill xxd-panel-344
```

Then restart your agent session. You can also `git clone` this repository and link the folder to `~/.claude/skills/xxd-panel-344` or `~/.codex/skills/xxd-panel-344`.

**2. Make sure your agent can generate images.** This Skill has no image model of its own; it uses your agent's image generation, preferably GPT Image 2.

- Codex works as is when its built-in image generation is on.
- Claude Code and other agents without built-in image generation need an OpenAI-compatible image API. It takes about five minutes: see [Setting up image generation](#setting-up-image-generation).

Not sure? Just try it. If images can't be generated, the Skill stops and tells you before doing any work.

**3. Send a photo and say one sentence:**

> Use xxd-panel-344 to turn this photo into a 3:4 top–bottom poster with an English title.

If your request is complete, it starts right away; anything you left out (layout, ratio, text) it asks about, usually in one or two questions. Results are PNGs in a new folder under `~/Desktop/xxd/xxd-panel-344/`.

## Which photos work best

**Works well**

- Subjects that can be lifted out on their own: a small house, a car, a tower, a tree
- Small shops or corners with a lived-in feel: a café front, a newsstand, a corner of a balcony
- Photos with weak composition, messy backgrounds or a small subject, which get cut onto a plinth with the distance removed

**Not a good fit**

- Requests to keep a whole street, landscape or full interior, since only one element is modelled
- Photos where a person's likeness or real materials must show, since everything becomes a rounded figurine
- Requests for a straight-on front elevation, flat vector art, shiny plastic or saturated candy colours

## Samples

Each image below is a finished result this Skill made from one photo. The top–bottom and left–right sets use different photos.

### Top–bottom: photo above, design below

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 344 · 01 · Country chapel"><br><sub>01 · Country chapel</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 344 · 02 · Vintage VW bus"><br><sub>02 · Vintage VW bus</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 344 · 03 · Red tractor"><br><sub>03 · Red tractor</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 344 · 04 · Windmill"><br><sub>04 · Windmill</sub></td>
  </tr>
</table>

<details>
<summary>Show 16 more</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 344 · 05 · Treehouse"><br><sub>05 · Treehouse</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 344 · 06 · Alpaca"><br><sub>06 · Alpaca</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 344 · 07 · Rowing boat"><br><sub>07 · Rowing boat</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 344 · 08 · Overwater hut"><br><sub>08 · Overwater hut</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 344 · 09 · Flower shop"><br><sub>09 · Flower shop</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 344 · 10 · Steam locomotive"><br><sub>10 · Steam locomotive</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 344 · 11 · Camel"><br><sub>11 · Camel</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 344 · 12 · Skateboard"><br><sub>12 · Skateboard</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 344 · 13 · Hedgehog"><br><sub>13 · Hedgehog</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 344 · 14 · Water mill"><br><sub>14 · Water mill</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 344 · 15 · Fire hydrant"><br><sub>15 · Fire hydrant</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 344 · 16 · Camping tent"><br><sub>16 · Camping tent</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 344 · 17 · Classic car"><br><sub>17 · Classic car</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 344 · 18 · Greenhouse"><br><sub>18 · Greenhouse</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 344 · 19 · Islet"><br><sub>19 · Islet</sub></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 344 · 20 · Elephant"><br><sub>20 · Elephant</sub></td>
  </tr>
</table>

</details>

### Left–right: photo left, design right

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 344 · 21 · Vending machine"><br><sub>21 · Vending machine</sub></td>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 344 · 22 · Lighthouse"><br><sub>22 · Lighthouse</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 344 · 23 · Water tower"><br><sub>23 · Water tower</sub></td>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 344 · 24 · Traffic light"><br><sub>24 · Traffic light</sub></td>
  </tr>
</table>

<details>
<summary>Show 16 more</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 344 · 25 · Clock tower"><br><sub>25 · Clock tower</sub></td>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 344 · 26 · Panda"><br><sub>26 · Panda</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 344 · 27 · Squirrel"><br><sub>27 · Squirrel</sub></td>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 344 · 28 · Latte"><br><sub>28 · Latte</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 344 · 29 · Succulent pot"><br><sub>29 · Succulent pot</sub></td>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 344 · 30 · Street saxophonist"><br><sub>30 · Street saxophonist</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 344 · 31 · Bicycle by a wall"><br><sub>31 · Bicycle by a wall</sub></td>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 344 · 32 · Colourful cottage"><br><sub>32 · Colourful cottage</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 344 · 33 · Snowman"><br><sub>33 · Snowman</sub></td>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 344 · 34 · Pumpkin"><br><sub>34 · Pumpkin</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 344 · 35 · Stag"><br><sub>35 · Stag</sub></td>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 344 · 36 · Raspberry cake"><br><sub>36 · Raspberry cake</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-37.png" alt="XXD Panel 344 · 37 · Cherry blossom branch"><br><sub>37 · Cherry blossom branch</sub></td>
    <td width="50%"><img src="./assets/examples/sample-38.png" alt="XXD Panel 344 · 38 · Carousel"><br><sub>38 · Carousel</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-39.png" alt="XXD Panel 344 · 39 · Horse"><br><sub>39 · Horse</sub></td>
    <td width="50%"><img src="./assets/examples/sample-40.png" alt="XXD Panel 344 · 40 · Sheep"><br><sub>40 · Sheep</sub></td>
  </tr>
</table>

</details>

## Just say it

No parameters to memorise. Say what you want:

| You want | Say |
|---|---|
| Top–bottom comparison | Make a 3:4 top–bottom comparison |
| Left–right comparison | Make a 16:9 left–right comparison, photo on the left |
| Design only | Just the design, no photo, 9:16 portrait |
| A wallpaper set | Make matching wallpapers for phone, tablet, desktop and watch |
| Several ratios | Make this one at 1:1, 3:4 and 16:9 |
| Your own text | Use the title “Let the wind pass through” exactly as written |
| No text | No text at all |
| Text language | Write the text in Japanese |
| A whole folder | Turn every photo in this folder into a top–bottom comparison |
| Same as last time | Use my settings from last time |

Prefer the command line? The flags map one to one:

```text
/xxd-panel-344 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale en-US
/xxd-panel-344 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-344 ./photos --mode left-right --size 16:9 --text prompt --locale ja-JP
```

All flags are listed under [Parameters](#parameters).

## FAQ

**Does the original photo have to appear?** No. Ask for “design only” or a wallpaper set and the whole canvas is design.

**Who writes the text?** By default the image model writes it from your photo; you only choose the language. Give your own words and they are used exactly; or ask for no text. Anything that looks factual (places, dates, numbers) comes only from you or from what is visible in the photo, never invented.

**What if I don't like the result?** Say “one more”. It redraws from the original photo instead of editing the last result, so every attempt is different.

**Do photos in a batch mix together?** No. Each photo is generated on its own and never borrows another photo's colours, text or layout. Settings are asked once for the whole batch.

**Where do my photos go?** Only to the image model your agent uses. The Skill uploads nothing elsewhere and never prints endpoints or keys.

**How does this relate to other Panels?** XXD Panels are a family of styles, one per number, fully independent; install only the ones you like. To have AI recommend a style for a photo, or compare several at once, use the catalog [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all).

## Original prompt

This style is defined entirely by Xiaoxiaodong's [original prompt](references/original-prompt/zh-CN.md) (in Chinese). The Skill only appends the layout, size and text settings you choose; it never summarises, translates or rewrites the prompt.

Reading translations (for reading only; never sent to the image model): [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## Setting up image generation

You need an OpenAI-compatible API that serves `gpt-image-2` (or a compatible model) and its API key. This creates a separate config and leaves your Codex settings alone:

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # or your compatible endpoint
env_key = "XXD_IMAGE_API_KEY"
EOF

# add to ~/.zshrc or ~/.bashrc so your agent can read them
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=your-key' >> ~/.zshrc
```

Reopen your terminal and agent, then check once from this Skill's folder:

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true` means it works. The check only reports readiness; it never prints the endpoint or key. If your Codex already generates images through a compatible API, skip this step.

## Parameters

| Flag | Values |
|---|---|
| `--mode` | `top-bottom` · `left-right` · `design-only` · `wallpaper-pack` (phone, tablet, desktop, watch); combine freely |
| `--size` | `auto` recommended · `source` match the photo · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · exact pixels such as `2160x3840`; combine freely |
| `--text` | `prompt` written from the photo · `exact` your words (with `--copy "…"`) · `none` no text |
| `--locale` | text language, e.g. `zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` a matching set · `independent` four separate designs |
| `--wallpaper-size` | device pixels, e.g. `phone=1440x3200,desktop=3840x2160` |
| `--out` | another output root (default `~/Desktop/xxd/xxd-panel-344/`) |
| `--prefs` | `last` reuse · `edit` start from last time · `new` choose again · `off` don't remember this time · `clear` forget |

- With every value given, nothing is asked; otherwise only the missing values are. Pass a folder instead of `photo.jpg` to batch.
- Combinations are generated one by one: 2 modes × 3 sizes = 6 images, each composed for its own canvas rather than cropped.
- Comparisons are exactly 50:50. Usually the model paints only the design half and a script places the untouched photo beside it, so the split is centred and the photo is unchanged.
- Files are named like `source-001-street-top-bottom-3x4-1152x1536.png`, all in one flat task folder.
- Only layout, size, text mode and language are remembered, never photos, copy or keys.

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Xiaoxiaodong multi-platform membership · CNY 699/year

> **Advertising disclosure:** The QR code, membership, and paid-service links below are XXD promotional information. Scanning or purchasing is entirely optional and does not affect access to this open-source project.

One annual membership unlocks three benefits together: **Knowledge Planet + the XXD Member Prompt Library + membership for all General Skills**. They are included in one membership; no separate purchase is required.

<!-- xxd-panel-command-system:start -->

### How the Skills work together

| Level | Included | What it does |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detects available numbered Skills, recommends them by image, theme, or use, and organizes multi-style and batch tasks. |
| **Soldier** | `xxd-panel-NNN` | Each numbered Skill follows its own original brief and aesthetic to complete the specific task assigned by the General. |

<!-- xxd-panel-command-system:end -->

### What you receive

1. **One-to-one WeChat AI learning and project support**
   Add Xiaoxiaodong on WeChat via the QR code below to discuss AI learning, tools, and real projects one to one, with practical guidance and answers. Representative questions may be organized into member resources.
2. **A growing member prompt library**
   The [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) currently contains about 32,000 prompts and will keep expanding, with a goal of exceeding 100,000.
3. **All General Skills and usage support**
   One membership covers every General Skill, with usage guidance and Q&A when you need help.
4. **Priority for high-need requests**
   Frequently requested, high-need prompts and Skills are reviewed and developed first where appropriate.

### How to join

- [Activate membership on the member website](https://vip.xiaoxiaodong.ai/).
- Or scan the QR code below to add Xiaoxiaodong on WeChat for one-to-one activation support.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Contact Xiaoxiaodong" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## License

This project—including the Skill, prompts, scripts, documentation, and accompanying sample images—is licensed under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the full legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

In plain language:

- Individuals may use it for study, research, experimentation, testing, hobby projects, and private entertainment. Charities, educational institutions, public research, safety or health organisations, environmental organisations, and government institutions may also use it.
- For **noncommercial purposes**, you may use, copy, modify, create derivative works, and share it. When sharing, you must also provide this license (or the link above) and every `Required Notice:` statement supplied by the author.
- It may not be used in commercial products or services, paid delivery, sale of access or licences, or any use expected to lead to commercial application. Obtain separate written permission from the copyright holder before commercial use.
- The agreement grants only the copyright licence and limited patent licence expressly stated. It grants no trademarks, brand names, or other unstated rights, and you may not sublicense your licence to others.
- After written notice of a violation, you must return to compliance and take practical remedial steps within 32 days, or the licences terminate immediately. A written patent-infringement claim also terminates the patent licence.
- The material is provided “as is”, without warranty to the extent permitted by law. Users bear the risks and potential losses arising from its use.
