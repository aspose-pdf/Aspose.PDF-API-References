---
title: "SvgLoadOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "SVG ファイルを PDF ドキュメントにロード/インポートするオプションを表します。"
type: docs
weight: 1450
url: /ja/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

SVG ファイルを PDF ドキュメントにロード/インポートするオプションを表します。

SvgLoadOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| SvgLoadOptions() | SvgLoadOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバック。<br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。<br/>            Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |
| load_format | ファイル形式を表します。この形式は[LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)で記述されています。 |
| page_info | ドキュメントの読み込み時に適用されるページ情報を取得または設定します。<br/>            NOTE このパラメーターは ConversionEngine == ConversionEngines.NewEngine の場合にのみ機能します |
| adjust_page_size | PDF ページサイズを SVG サイズに合わせます |
| conversion_engine | 変換中に使用される変換エンジンを選択できます。<br/>            現在、新しいエンジンは B テスト段階にあり、この値はデフォルトで <br/>            ConversionEngines.LegacyEngine に設定されます |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

