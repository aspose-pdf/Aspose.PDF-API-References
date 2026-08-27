---
title: "DocSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "Doc 形式へのエクスポート用保存オプション"
type: docs
weight: 220
url: /ja/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Doc 形式へのエクスポート用保存オプション

DocSaveOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| DocSaveOptions() | DocSaveOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| extract_ocr_sublayer_only | この属性は OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 <br/>             |
| try_merge_adjacent_same_background_images | PDF にはページや表セルの背景画像が、<br/>              複数の同一タイル背景画像を隣接させて構成されていることがあります。<br/>              このような場合、対象フォーマットのレンダラー（例: DOCS 形式の MsWord）では、<br/>              背景画像の一部間に目に見える境界が生成されることがあります。<br/>              これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。<br/>               エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界があるように見える場合は、<br/>              この設定を使用して不要な効果を取り除いてください。 <br/>                注意！この品質最適化は通常、変換速度を大幅に低下させます。<br/>              したがって、本当に必要なときにのみこのオプションを使用してください。 |
| mode | 認識モードです。 |
| relative_horizontal_proximity | PDF では、単語が文字や音節を個別に印刷する演算子で内部的に表現されることがあります。<br/>              単語を検出するためには、実際には単語である独立した文字のグループを検出する必要があります。<br/>                この設定は、テキスト要素（文字、音節）間の空白幅を定義し、<br/>              ソース PDF の単語認識時に単語間の距離として扱われます。<br/>              （文字間にこの幅以上の空白が存在する場合、テキスト要素は別々の単語に属するとみなされます）。<br/>              フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。<br/>             注意！この設定は、フォントから最適値を算出できない、特定の稀に使用されるフォントが含まれる場合にのみ使用されます。<br/>             したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。 |
| max_distance_between_text_lines | このパラメータはテキスト行を段落にグループ化するために使用されます。<br/>            2 つの相対テキスト行がどれだけ離れていてもよいかを決定します。テキスト行の高さの数百パーセントで指定されます。 |
| recognize_bullets | 箇条書きの認識を有効にします |
| add_return_to_line_end | 段落または改行を使用します |
| image_resolution_x | 変換された画像の X 解像度です。 |
| image_resolution_y | 変換された画像の Y 解像度です。 |
| format | 出力フォーマット |
| batch_size | バッチ変換がソースおよび宛先フォーマットの組み合わせに適用可能な場合、バッチサイズを定義します。<br/>             |
| memory_save_mode_path | メモリ保存モードで変換する際に、一時データを保持するパス（ファイル名またはディレクトリ名）を定義します。<br/>             |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

