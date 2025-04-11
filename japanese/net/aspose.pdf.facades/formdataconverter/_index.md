---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormDataConverter クラス。データをある形式から別の形式に変換するクラスを表します。fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。また、OLEDB/OdbcDB のデータを fdf/xml/xfdf のデータに変換することもできます。fdf を "ハードネーム" タグ付きの xml に変換できます。
type: docs
weight: 4320
url: /ja/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter クラス

データをある形式から別の形式に変換するクラスを表します。fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。また、OLEDB/OdbcDB のデータを fdf/xml/xfdf のデータに変換することもできます。fdf を "ハードネーム" タグ付きの xml に変換できます。

```csharp
public sealed class FormDataConverter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData はデータエクスポートの前にテーブルをクリアします。 |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable は、テーブルに存在しない場合に必要なフィールドを作成します。 |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase は、存在しない場合にテーブルを作成します。 |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase は、既存のテーブルを削除し、このプロパティが true に設定されている場合は新しいテーブルを作成します。 |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | 中間データコンテナである DataTable を取得または設定します。データをある形式から別の形式に変換する前に定義する必要があります。DataTable の Columns と TableName を定義する必要があります。TableName はデータベース内のテーブルの名前です。各列の ColumnName は pdf の資格のあるフィールド名です。各列の Caption はデータベース内のテーブルの列名です。フィールド名がテーブルの列名と同じ場合、Caption は指定する必要はありません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | このメソッドは廃止予定です。代わりに ConvertToStreams() を使用してください。 |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | ストリームのファイルをテーブルに変換します。 |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | テーブル内のデータをストリームに変換します。 |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | データベースからテーブルにデータをエクスポートします。 |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | テーブルからデータベースにデータをインポートします。 |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | FDF ファイルを XML に変換します。 |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | XML インポート/エクスポートフォームデータファイルを FDF 形式に変換します。 |

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)