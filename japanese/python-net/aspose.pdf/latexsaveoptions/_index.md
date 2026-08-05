---
title: "LaTeXSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "TeX 形式へのエクスポート用保存オプションです。"
type: docs
weight: 800
url: /ja/python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

TeX 形式へのエクスポート用保存オプションです。

LaTeXSaveOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| LaTeXSaveOptions() | LaTeXSaveOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | None |
| save_format | None |
| close_response | None |
| extract_ocr_sublayer_only | この属性は OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 <br/>             |
| try_merge_adjacent_same_background_images | PDF にはページや表セルの背景画像が、<br/>              複数の同一タイル背景画像を隣接させて構成されていることがあります。<br/>              このような場合、対象フォーマットのレンダラー（例: DOCS 形式の MsWord）では、<br/>              背景画像の一部間に目に見える境界が生成されることがあります。<br/>              これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。<br/>               エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界があるように見える場合は、<br/>              この設定を使用して不要な効果を取り除いてください。 <br/>                注意！この品質最適化は通常、変換速度を大幅に低下させます。<br/>              したがって、本当に必要なときにのみこのオプションを使用してください。 |
| out_directory_path | プロパティ |
| pages_count | 変換後のページ数を返します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| add_font_encs(font_encs) | フォントエンコーディングをフォントエンコーディングリストに追加します |
| clear_font_encs() | フォントエンコーディングリストをクリアします |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

