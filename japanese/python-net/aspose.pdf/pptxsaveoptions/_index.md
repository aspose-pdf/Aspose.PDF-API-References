---
title: "PptxSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "SVG 形式へのエクスポート用保存オプションです。"
type: docs
weight: 1290
url: /ja/python-net/aspose.pdf/pptxsaveoptions/
---

## PptxSaveOptions class

SVG 形式へのエクスポート用保存オプションです。

PptxSaveOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PptxSaveOptions() | PptxSaveOptions クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| extract_ocr_sublayer_only | この属性は OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 <br/>             |
| try_merge_adjacent_same_background_images | PDF にはページや表セルの背景画像が、<br/>              複数の同一タイル背景画像を隣接させて構成されていることがあります。<br/>              このような場合、対象フォーマットのレンダラー（例: DOCS 形式の MsWord）では、<br/>              背景画像の一部間に目に見える境界が生成されることがあります。<br/>              これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。<br/>               エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界があるように見える場合は、<br/>              この設定を使用して不要な効果を取り除いてください。 <br/>                注意！この品質最適化は通常、変換速度を大幅に低下させます。<br/>              したがって、本当に必要なときにのみこのオプションを使用してください。 |
| slides_as_images | true に設定すると、すべてのコンテンツが画像として認識されます（ページごとに1つ）。 |
| image_resolution | 画像解像度（dpi）を取得または設定します。デフォルトは 192 dpi です。 |
| separate_images | true に設定すると、画像が他のすべてのグラフィックから分離されます。 |
| optimize_text_boxes | テキスト列の認識を切り替えます |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

