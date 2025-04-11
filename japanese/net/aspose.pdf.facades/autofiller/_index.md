---
title: Class AutoFiller
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.AutoFiller クラス。データベースまたは他のデータソースからデータを受け取り、それをテンプレート PDF の設計されたフィールドに埋め込み、最終的に新しい PDF ファイルまたはストリームを生成するクラスを表します。ストリームまたは PDF ファイルとしての入力の 2 つのテンプレートファイル入力モードがあります。出力モードは 4 種類あり、1 つのマージストリーム、1 つのマージファイル、多くの小さなストリーム、多くの小さなファイルがあります。System.Data.DataTable に含まれるリテラルデータを受け取ることができます。
type: docs
weight: 4150
url: /ja/net/aspose.pdf.facades/autofiller/
---
## AutoFiller クラス

データベースまたは他のデータソースからデータを受け取り、それをテンプレート PDF の設計されたフィールドに埋め込み、最終的に新しい PDF ファイルまたはストリームを生成するクラスを表します。ストリームまたは PDF ファイルとしての入力の 2 つのテンプレートファイル入力モードがあります。出力モードは 4 種類あり、1 つのマージストリーム、1 つのマージファイル、多くの小さなストリーム、多くの小さなファイルがあります。System.Data.DataTable に含まれるリテラルデータを受け取ることができます。

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AutoFiller](autofiller/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | 多くの小さなファイルが生成される場合の基本ファイル名を取得または設定します。生成されたファイルは「BasicFileName0」、「BasicFileName1」、...のようになります。別のプロパティ [`GeneratingPath`](./generatingpath/)GeneratingPath と連携します。 |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | 多くの小さな PDF ファイルが生成される場合の小さな PDF ファイルの生成パスを取得または設定します。別のプロパティ [`BasicFileName`](./basicfilename/)BasicFileName と連携します。4 つの出力モードの 1 つです。 |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | 多くの出力ストリームを取得または設定します。4 つの出力モードの 1 つです。 |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | フラット化されないフィールドを設定します。このプロパティが設定されていない場合、すべてのフィールドがフラット化されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | PDF ドキュメントをバインドします。 |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | PDF ファイルをバインドします。 |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | PDF ファイルをバインドします。 |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | オブジェクトと出力ストリームを閉じます。 |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | オブジェクトと出力ストリームを閉じます。 |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | DataTable 型のデータをインポートします。データテーブルの各列の名前は、テンプレート PDF のフィールド名と大文字と小文字を区別して同じでなければなりません。 |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | すべての PDF を保存します。 |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | すべての PDF を保存します。 |

## 例

```csharp
[C#]
//Note: mail.pdf is a template pdf which has seven text fields. NorthWind.mdb is the microsoft access db.
////Common part: Get the data from the database NorthWind.mdb fill it into the DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Construct the data table.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Connect to the database source and query the data.
mDbConnection = new OleDbConnection();
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + 
DbPath + "NorthWind.mdb";
mQueryCommand = new OleDbCommand();
mQueryCommand.Connection = mDbConnection;
mDbConnection.Open();


mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;";
mDbDataAdapter = new OleDbDataAdapter(mQueryCommand);
		
mDbDataAdapter.Fill(mDataTable);

for (int i = 0; i<mDataTable.Rows.Count;i++)
{
	mDataTable.Rows[i][mDataTable.Columns.Count - 1] = "Dear " + mDataTable.Rows[i][0].ToString() + ",";
	System.Console.WriteLine("postalCode:" + mDataTable.Rows[i][3].ToString());
	System.Console.WriteLine("Heading:" + mDataTable.Rows[i][mDataTable.Columns.Count - 1].ToString());
}

mDbDataAdapter.Dispose();
mDbConnection.Close();
////End of Common part.

////case one:
////Input template pdf is a pdf file and output is a big merged stream.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////case two:
////Input template pdf is a pdf file and output is a lot of small files.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Note: mail.pdf is a template pdf which has seven text fields. NorthWind.mdb is the microsoft access db.
'Common part: Get the data from the database NorthWind.mdb fill it into the DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Construct the data table.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Create columns for the datatable. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Connect to the database source and query the data.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Query the data and insert into the datatable.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Construct the last column  of the Datatable.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'End of Common part.

'case one:
'Input template pdf is a pdf file and output is a big merged stream.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'case two:
'Input template pdf is a pdf file and output is a lot of small files.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### 参照

* インターフェース [ISaveableFacade](../isaveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)