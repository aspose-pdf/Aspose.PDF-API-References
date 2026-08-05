---
title: "SvgSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "SVG 形式へのエクスポート用保存オプションです。"
type: docs
weight: 1460
url: /ja/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

SVG 形式へのエクスポート用保存オプションです。

SvgSaveOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| SvgSaveOptions() | SvgSaveOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| extract_ocr_sublayer_only | None |
| try_merge_adjacent_same_background_images | None |
| treat_target_file_name_as_directory | このオプションは、対象ディレクトリを作成するかどうかを定義します<br/>             （まだ存在しない場合）要求された出力ファイルと同じ名前のディレクトリを<br/>             出力ファイル自体の代わりに作成します。<br/>             これにより、そのディレクトリにはページのすべての出力 SVG 画像が含まれます（以下に説明するように）。<br/>               いいえの場合、最初のページ以外のページの出力ファイルは要求されたディレクトリに正確に作成され、<br/>            メインの出力ファイルとして扱われますが、ファイル名に _[2...n] のサフィックスが付加され、<br/>             それはページ番号で定義されます。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義した場合、<br/>             出力には複数のページの svg ファイルが含まれ、<br/>             それらのページファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などになります。 |
| compress_output_to_zip_archive | 出力を 1 つの zip アーカイブとして作成するかどうかを指定します。<br/>             複数ページのソースドキュメントのページ用 svg ファイルの命名規則については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。これらの規則は zip 圧縮された出力ファイルセットにも適用されます。 |
| scale_to_pixels | 出力ドキュメントを組版ポイントからピクセルへスケールするかどうかを指定します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

