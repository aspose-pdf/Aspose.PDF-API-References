---
title: "类 AutoFiller"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.AutoFiller 类。表示一个从数据库或其他数据源接收数据并将其填充到模板 PDF 的设计字段中的类，最终生成新的 PDF 文件或流。它有两种模板文件输入模式：作为流或作为 PDF 文件。它有四种输出模式：一个合并流、一个合并文件、多个小流、多个小文件。它可以接收包含在 System.Data.DataTable 中的文字数据。"
type: docs
weight: 4270
url: /zh/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

表示一个类，用于从数据库或其他数据源接收数据，将其填充到模板 PDF 的设计字段中，最终生成新的 PDF 文件或流。它有两种模板文件输入模式：作为流或 PDF 文件。它有四种输出模式：一个合并流、一个合并文件、多个小流、多个小文件。它可以接收包含在 System.Data.DataTable 中的文字数据。

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AutoFiller](autofiller/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | 获取或设置基本文件名（如果将生成多个小文件）。生成的文件将类似于 \"BasicFileName0\",\"BasicFileName1\",...，它与另一个属性 [`GeneratingPath`](./generatingpath/)GeneratingPath 配合使用。 |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | 获取或设置小 pdf 文件的生成路径（如果将生成多个小 pdf 文件）。它与另一个属性 [`BasicFileName`](./basicfilename/)BasicFileName 配合使用。四种输出模式之一。 |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | 获取或设置多个输出流。四种输出模式之一。 |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | 设置不需要扁平化的字段。如果未设置此属性，所有字段将被扁平化。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | 绑定一个 Pdf 文档。 |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | 绑定一个 Pdf 文件。 |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | 绑定一个 Pdf 文件。 |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | 关闭对象和输出流。 |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | 关闭对象和输出流。 |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | 导入 DataTable 类型的数据。dataTable 的每列名称必须与模板 pdf 中的字段名称完全匹配（区分大小写）。 |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | 保存所有 pdf。 |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | 保存所有 pdf。 |

## 示例

```csharp
[C#]
//注意：mail.pdf 是一个包含七个文本字段的模板 pdf。NorthWind.mdb 是 Microsoft Access 数据库。
////Common part: 从数据库 NorthWind.mdb 获取数据并填充到 DataTable。
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//构建数据表。
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//连接到数据库源并查询数据。
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
////Common part结束。

////案例一：
////输入模板 pdf 是一个 pdf 文件，输出是一个大的合并流。\t\t
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////案例二：
////输入模板 pdf 是一个 pdf 文件，输出是大量小文件。
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

### 另请参见

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


