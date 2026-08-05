---
title: "TeXLoadOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "TeX ファイルを PDF ドキュメントに読み込み/インポートするためのオプションを表します。"
type: docs
weight: 1520
url: /ja/python-net/aspose.pdf/texloadoptions/
---

## TeXLoadOptions class

TeX ファイルを PDF ドキュメントに読み込み/インポートするためのオプションを表します。

TeXLoadOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TeXLoadOptions() | TeXLoadOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバック。<br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。<br/>            Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |
| load_format | ファイル形式を表します。この形式は[LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)で記述されています。 |
| job_name | ジョブの名前を取得/設定します。 |
| input_directory | TeX 入力ディレクトリを取得/設定します。 |
| output_directory | TeX 出力ディレクトリを取得/設定します。 |
| repeat | TeX ジョブを 2 回実行する必要があるかどうかを示すフラグを取得/設定します、<br/>            たとえば、入力 TeX ファイルに参照がある場合です。一般に、この動作はエンジンが組版プロセス中にデータを収集し、補助ファイルに保存する際に有用です、<br/>            最初の実行時にすべて保存され、2 回目の実行時にエンジンがそのデータを何らかの形で使用します。 |
| subset_fonts | 出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。 |
| show_terminal_output | コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。 |
| date_time | \year、\month、\day、\time などの日付/時刻プリミティブの特定の値を取得/設定します。 |
| no_ligatures | すべてのフォントで合字を無効にするフラグを取得/設定します。 |
| rasterize_formulas | 数式をラスタライズできるフラグを取得/設定します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

