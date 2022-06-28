---
title: AutoFiller
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для получения данных из базы данных или другого источника данных заполняет их в разработанные поля шаблона pdf и наконец создает новый файл pdf или поток. Он имеет два режима ввода файла шаблонаввод в виде потока или файла pdf. Он имеет четыре типа режимов выводаодин объединенный поток один объединенный файл много небольших потоков много маленьких файлов. Он может получать литеральные данные содержащиеся в System.Data.DataTable.
type: docs
weight: 2170
url: /ru/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Представляет класс для получения данных из базы данных или другого источника данных, заполняет их в разработанные поля шаблона pdf и, наконец, создает новый файл pdf или поток. Он имеет два режима ввода файла шаблона:ввод в виде потока или файла pdf. Он имеет четыре типа режимов вывода:один объединенный поток, один объединенный файл, много небольших потоков, много маленьких файлов. Он может получать литеральные данные, содержащиеся в System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AutoFiller](autofiller)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Получает или задает основное имя файла, если будет создано много маленьких файлов. Сгенерированный файл будет иметь вид "BasicFileName0", "BasicFileName1",... Он работает с другим свойством[`GeneratingPath`](./generatingpath)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Получает или задает путь создания небольших PDF-файлов, если необходимо создать много небольших PDF-файлов. Он работает с другим свойством[`BasicFileName`](./basicfilename)BasicFileName. Один из четырех режимов вывода. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Получает или задает множество выходных потоков. Один из четырех режимов вывода. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Устанавливает поля, которые не будут сведены. Если это свойство не установлено, все поля будут сведены. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Связывает документ PDF. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Связывает файл Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Связывает файл Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Закрывает объект и потоки вывода. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Закрывает объект и потоки вывода. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | Импортирует данные типа DataTable. Имя каждого столбца dataTable должно совпадать с одним именем поля шаблона pdf с учетом регистра. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Сохраняет все файлы PDF. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Сохраняет все файлы PDF. |

### Примеры

```csharp
[C#]
 //Примечание: mail.pdf — это шаблон pdf с семью текстовыми полями. NorthWind.mdb — это база данных Microsoft Access.
 ////Общая часть: Получить данные из базы данных NorthWind.mdb и заполнить их в DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

 //Создаем таблицу данных.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


 //Подключаемся к источнику базы данных и запрашиваем данные.
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
 ////Входной шаблон pdf — это файл pdf, а вывод — большой объединенный поток. 
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

 ////второй случай:
 ////Входной шаблон pdf представляет собой файл pdf, а вывод представляет собой множество небольших файлов.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Примечание: mail.pdf — это шаблон pdf с семью текстовыми полями. NorthWind.mdb — это база данных Microsoft Access.
   'Общая часть: Получить данные из базы данных NorthWind.mdb и заполнить их в DataTable.
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Построить таблицу данных.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Создайте столбцы для таблицы данных.
   'Имя каждого столбца должно совпадать с именем одного поля в файле templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Подключитесь к источнику базы данных и запросите данные.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Запросить данные и вставить в таблицу данных.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Создайте последний столбец таблицы данных.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'End of Common part.

'случай первый:
   'Входной шаблон pdf — это файл pdf, а вывод — большой объединенный поток.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'случай второй:
   'Входной шаблон pdf представляет собой файл pdf, а вывод — множество небольших файлов.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Смотрите также

* interface [ISaveableFacade](../isaveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
