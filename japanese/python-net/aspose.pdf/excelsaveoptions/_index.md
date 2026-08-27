---
title: "ExcelSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "Excel 形式へのエクスポート用保存オプション"
type: docs
weight: 330
url: /ja/python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Excel 形式へのエクスポート用保存オプション

ExcelSaveOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| ExcelSaveOptions() | ExcelSaveOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| extract_ocr_sublayer_only | この属性は OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 <br/>             |
| try_merge_adjacent_same_background_images | PDF にはページや表セルの背景画像が、<br/>              複数の同一タイル背景画像を隣接させて構成されていることがあります。<br/>              このような場合、対象フォーマットのレンダラー（例: DOCS 形式の MsWord）では、<br/>              背景画像の一部間に目に見える境界が生成されることがあります。<br/>              これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。<br/>               エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界があるように見える場合は、<br/>              この設定を使用して不要な効果を取り除いてください。 <br/>                注意！この品質最適化は通常、変換速度を大幅に低下させます。<br/>              したがって、本当に必要なときにのみこのオプションを使用してください。 |
| minimize_the_number_of_worksheets | 結果のブックでシート数を最小化する必要がある場合は true を設定します。<br/>            デフォルト値は false です。これは各 PDF ページを個別のシートとして保存することを意味します。 |
| insert_blank_column_at_first | ワークシートの最初の列として空白列を挿入する必要がある場合は true を設定します。<br/>            デフォルト値は false です。これは空白列が挿入されないことを意味します。 |
| uniform_worksheets | ドキュメント全体で均一な列分割を使用する場合は true を設定します。 <br/>            デフォルト値は false です。これはページごとに列分割が独立することを意味します。 |
| format | 出力フォーマット |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

