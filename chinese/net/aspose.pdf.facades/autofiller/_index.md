---
title: AutoFiller
second_title: Aspose.PDF for .NET API 参考
description: 代表一个类从数据库或其他数据源接收数据填充到模板pdf的设计字段中最后生成新的pdf文件或流 它有两种模板文件输入方式作为流输入或pdf文件输入. 它有四种输出模式一种合并流一种合并文件许多小流许多小文件 它可以接收包含在System.Data.DataTable中的文字数据
type: docs
weight: 2170
url: /zh/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

代表一个类，从数据库或其他数据源接收数据，填充到模板pdf的设计字段中，最后生成新的pdf文件或流。 它有两种模板文件输入方式：作为流输入或pdf文件输入. 它有四种输出模式：一种合并流，一种合并文件，许多小流，许多小文件。 它可以接收包含在System.Data.DataTable中的文字数据。

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [AutoFiller](autofiller)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | 如果要生成很多小文件，获取或设置基本文件名。生成的文件将类似于 "BasicFileName0","BasicFileName1",... 它与另一个属性一起使用[`GeneratingPath`](./generatingpath)生成路径. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | 如果要生成许多小pdf文件，获取或设置小pdf文件的生成路径。它适用于另一个属性[`BasicFileName`](./basicfilename)BasicFileName. 四种输出模式之一。 |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | 获取或设置多个输出流。四种输出模式之一。 |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | 设置不被展平的字段。 如果没有设置这个属性，所有的字段都将被展平。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | 绑定一个 Pdf 文档。 |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | 绑定一个 Pdf 文件。 |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | 绑定一个 Pdf 文件。 |
| [Close](../../aspose.pdf.facades/autofiller/close)() | 关闭对象和输出流。 |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | 关闭对象和输出流。 |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | 导入DataTable 类型的数据。数据表每一列的名称必须与 模板pdf的一个字段名称相同，区分大小写。 |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | 保存所有 pdf。 |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | 保存所有 pdf。 |

### 例子

```csharp
[C#]
//注意：mail.pdf 是一个模板 pdf，它有七个文本字段。 NorthWind.mdb 是微软访问数据库。
////通用部分：从数据库NorthWind.mdb中获取数据填充到DataTable中。
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//构造数据表。
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//连接数据库源，查询数据。
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
////公共部分结束。

////案例一：
////输入模板pdf是一个pdf文件，输出是一个大的合并流。		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////情况二：
////输入模板pdf是一个pdf文件，输出是很多小文件。
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'注意：mail.pdf 是一个模板 pdf，它有七个文本字段。 NorthWind.mdb 是微软访问数据库。
'公共部分：从数据库NorthWind.mdb中获取数据，填充到DataTable中。 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'构建数据表。
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'为数据表创建列。 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'连接数据库源并查询数据。
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'查询数据并插入数据表。
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'构造数据表的最后一列。
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'公共部分结束。

'案例一：
'输入模板 pdf 是一个 pdf 文件，输出是一个大的合并流。
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'案例二：
'输入模板pdf是一个pdf文件，输出是很多小文件。
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### 也可以看看

* interface [ISaveableFacade](../isaveablefacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
