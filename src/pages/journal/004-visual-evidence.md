---
title: "Visual Evidence"
pubDate: 2026-02-08
description: "言葉の限界を超えるための、静止画という証拠。"
layout: "../../layouts/BlogPost.astro"
---

# 百聞は一見に如かず

テキストは論理を構築するが、画像は感情を喚起する。
以下は、インターネットの彼方から呼び出した、構造的な建築のイメージである。

![Minimalist Architecture](https://images.unsplash.com/photo-1486718448742-163732cd1544?auto=format&fit=crop&w=1000&q=80)

## ローカル画像の扱い方

もしこれが貴殿自身の撮った写真（例: `my-camera.jpg`）であれば、
ファイルを `public/images/` に置き、以下のように記述するだけでよい。

```markdown
![My HHKB](/images/my-camera.jpg)
```

CSSにより、画像は自動的に記事の幅に合わせてリサイズされ、
適切な余白（マージン）が上下に確保される。
もはやレイアウトの調整に時間を浪費する必要はない。
