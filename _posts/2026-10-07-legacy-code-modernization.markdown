---
layout: post
title:  "XShipWars移植事例のドキュメントを公開しました"
date:   2026-10-07 13:30:00 +0900
categories: update
---
ドキュメント「[25年前のゲームを3日で蘇らせた話 — XShipWars 移植事例](/docs/2026-10-07-legacy-code-modernization/)」を公開しました。

公開した[xshipwars](https://github.com/tariki/xshipwars)は、Claude Codeを使って移植しました。自力なら3〜4か月かかると見積もった移植が、3日で手戻りなく終わりました。
このドキュメントでは、次の内容を紹介しています。

- 25年前のコードが、今の環境でどう壊れていたか（古いC++の書き方、64bit対応、消えたライブラリなど）
- 移植の前にCLAUDE.mdとSKILLSをClaude Code自身に書かせた進め方
- 特に効いた4つのルールと、AIが自分で作った確認用スクリプト
- やってみて感じたこと
