---
title: "EpubSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "EPUB 形式へのエクスポート用保存オプション"
type: docs
weight: 320
url: /ja/python-net/aspose.pdf/epubsaveoptions/
---

## EpubSaveOptions class

EPUB 形式へのエクスポート用保存オプション

EpubSaveOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| EpubSaveOptions() | EpubSaveOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| extract_ocr_sublayer_only | この属性は OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 <br/>             |
| try_merge_adjacent_same_background_images | PDF にはページや表セルの背景画像が、<br/>              複数の同一タイル背景画像を隣接させて構成されていることがあります。<br/>              このような場合、対象フォーマットのレンダラー（例: DOCS 形式の MsWord）では、<br/>              背景画像の一部間に目に見える境界が生成されることがあります。<br/>              これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。<br/>               エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界があるように見える場合は、<br/>              この設定を使用して不要な効果を取り除いてください。 <br/>                注意！この品質最適化は通常、変換速度を大幅に低下させます。<br/>              したがって、本当に必要なときにのみこのオプションを使用してください。 |
| content_recognition_mode | PDF ファイル（通常は固定レイアウトです）が変換されるとき、<br/>            変換エンジンは、グルーピングと多層解析を実行して復元しようとします、<br/>            元の文書作成者の意図を再現し、フロー レイアウトで結果を生成します。<br/>               このプロパティは、その変換を特定の目的に合わせて調整します<br/>            コンテンツ認識の望ましい方法です。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

