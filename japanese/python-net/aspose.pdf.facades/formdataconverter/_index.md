---
title: "FormDataConverter"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "データをある形式から別の形式へ変換するクラスを表します。<br/>            fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。<br/>            また、OLEDB/OdbcDB のデータを fdf/xml/xfdf のデータに変換できます。<br/>            fdf を \"hard-named\" タグ付きの xml に変換することもできます。"
type: docs
weight: 100
url: /ja/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

データをある形式から別の形式へ変換するクラスを表します。<br/>            fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。<br/>            また、OLEDB/OdbcDB のデータを fdf/xml/xfdf のデータに変換できます。<br/>            fdf を "hard-named" タグ付きの xml に変換することもできます。

FormDataConverter 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FormDataConverter() | FormDataConverter クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| create_missing_field | ConvertToDataTable は、テーブルに存在しない場合、必須フィールドを作成します。 |
| replace_existing_table | ImportIntoDatabase は、プロパティが true に設定されている場合、既存のテーブルを削除し、新しいテーブルを作成します。 |
| clear_table_before_export | ExportFromData はデータのエクスポート前にテーブルをクリアします。 |
| create_missing_table | ImportIntoDatabase は、テーブルが存在しない場合に作成します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | XML のインポート/エクスポート用データファイルを FDF 形式に変換します。 |
| convert_fdf_to_xml(source_fdf, dest_xml) | FDF ファイルを XML に変換します。 |
| convert_to_data_table(source_streams, source_type) | strems のファイルをテーブルに変換します。 |
| import_into_data_base(connect_string, db_type) | テーブルからデータベースへデータをインポートします。 |
| export_from_data_base(connect_string, db_type) | データベースからテーブルへデータをエクスポートします。 |
| convert_to_streams(dest_stream, dest_type) | テーブル内のデータをストリームに変換します。 |
| conver_to_streams(dest_stream, dest_type) | このメソッドは廃止されています。代わりに ConvertToStreams() を使用してください。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

