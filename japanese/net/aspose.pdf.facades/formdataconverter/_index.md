---
title: "クラス FormDataConverter"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.FormDataConverter クラス。データをある形式から別の形式に変換するクラスを表します。fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。また、OLEDB/OdbcDB のデータを fdf/xml/xfdf に変換することも可能です。fdf をハードネームタグ付きの xml に変換することができます。"
type: docs
weight: 4440
url: /ja/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

データをある形式から別の形式へ変換するクラスを表します。fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。また、OLEDB/OdbcDB のデータを fdf/xml/xfdf に変換することも可能です。fdf を \"hard-named\" タグ付きの xml に変換することができます。

```csharp
public sealed class FormDataConverter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData はデータエクスポートの前にテーブルをクリアします。 |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable はテーブルに存在しない場合、必要なフィールドを作成します。 |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase はテーブルが存在しない場合、テーブルを作成します。 |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | このプロパティが true に設定されている場合、ImportIntoDatabase は既存のテーブルを削除し、新しいテーブルを作成します。 |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | 中間データコンテナである DataTable を取得または設定します。データをある形式から別の形式に変換する前に必ず定義する必要があります。DataTable の Columns と TableName を定義してください。TableName はデータベース内のテーブル名です。各列の ColumnName は PDF の完全修飾フィールド名です。各列の Caption はデータベース内テーブルの列名です。フィールド名がテーブル列名と同じ場合、Caption を指定する必要はありません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | このメソッドは廃止予定です。代わりに ConvertToStreams() を使用してください。 |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | ストリームのファイルをテーブルに変換します。 |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | テーブル内のデータをストリームに変換します。 |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | データベースからテーブルへデータをエクスポートします。 |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | テーブルからデータベースへデータをインポートします。 |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | FDF ファイルを XML に変換します。 |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | XML インポート/エクスポートフォームデータファイルを FDF 形式に変換します。 |

### 関連項目

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


