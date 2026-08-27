---
title: "Класс AutoFiller"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.AutoFiller. Представляет класс, получающий данные из базы данных или другого источника данных и заполняющий их в разработанные поля шаблона pdf, после чего генерирует новый pdf‑файл или поток. Имеет два режима ввода шаблонного файла — в виде потока или pdf‑файла. Поддерживает четыре типа режимов вывода: один объединённый поток, один объединённый файл, множество небольших потоков, множество небольших файлов. Может принимать буквальные данные, содержащиеся в System.Data.DataTable."
type: docs
weight: 4270
url: /ru/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Представляет класс для получения данных из базы данных или другого источника данных, заполняет их в предназначенные поля шаблона pdf и в конце генерирует новый pdf‑файл или поток. Он поддерживает два режима ввода шаблонного файла: ввод в виде потока или pdf‑файла. Он имеет четыре типа режимов вывода: один объединённый поток, один объединённый файл, множество небольших потоков, множество небольших файлов. Он может принимать буквальные данные, содержащиеся в System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AutoFiller](autofiller/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Получает или задает базовое имя файла, если будет генерировано много небольших файлов. Сгенерированный файл будет иметь вид "BasicFileName0","BasicFileName1",... Работает с другим свойством [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Получает или задает путь генерации небольших pdf‑файлов, если будет генерировано много небольших pdf‑файлов. Работает с другим свойством [`BasicFileName`](./basicfilename/)BasicFileName. Один из четырёх режимов вывода. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Получает или задает множество Output Streams. Один из четырёх режимов вывода. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Устанавливает поля, которые не будут уплощены. Если это свойство не задано, все поля будут уплощены. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Привязывает Pdf Document. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Привязывает Pdf файл. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Привязывает Pdf файл. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Закрывает объект и потоки вывода. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Закрывает объект и потоки вывода. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Импортирует данные типа DataTable. Имя каждого столбца dataTable должно точно совпадать с именем одного поля шаблона pdf (с учётом регистра). |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Сохраняет все pdf‑файлы. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Сохраняет все pdf‑файлы. |

## Примеры

```csharp
[C#]
//Примечание: mail.pdf — это шаблонный pdf, содержащий семь текстовых полей. NorthWind.mdb — это база данных Microsoft Access.
////Общая часть: Получить данные из базы данных NorthWind.mdb и заполнить их в DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Создать таблицу данных.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Подключиться к источнику базы данных и выполнить запрос данных.
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
////Конец общей части.

////случай один:
////Входной шаблонный pdf — это pdf‑файл, а вывод — большой объединённый поток.
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////случай два:
////Входной шаблонный pdf — это pdf‑файл, а вывод — множество небольших файлов.
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

### См. также

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


