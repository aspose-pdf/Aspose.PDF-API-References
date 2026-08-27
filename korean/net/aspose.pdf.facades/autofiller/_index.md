---
title: "클래스 AutoFiller"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.AutoFiller 클래스. 데이터베이스 또는 기타 데이터 소스에서 데이터를 받아 템플릿 PDF의 설계된 필드에 채워 넣고 마지막에 새로운 PDF 파일이나 스트림을 생성하는 클래스를 나타냅니다. 두 가지 템플릿 파일 입력 모드(스트림 또는 PDF 파일)와 네 가지 출력 모드(하나의 병합 스트림, 하나의 병합 파일, 다수의 작은 스트림, 다수의 작은 파일)를 지원합니다. System.Data.DataTable에 포함된 리터럴 데이터를 수신할 수 있습니다."
type: docs
weight: 4270
url: /ko/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

데이터베이스 또는 기타 데이터 소스에서 데이터를 받아 템플릿 pdf의 설계된 필드에 채우고 최종적으로 새 pdf 파일이나 스트림을 생성하는 클래스를 나타냅니다. 이 클래스는 두 가지 템플릿 파일 입력 모드를 지원합니다: 스트림으로 입력하거나 pdf 파일로 입력합니다. 네 가지 출력 모드가 있습니다: 하나의 병합된 스트림, 하나의 병합된 파일, 다수의 작은 스트림, 다수의 작은 파일. 또한 System.Data.DataTable에 포함된 리터럴 데이터를 받을 수 있습니다.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AutoFiller](autofiller/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | 다수의 작은 파일이 생성될 경우 기본 파일 이름을 가져오거나 설정합니다. 생성된 파일은 "BasicFileName0", "BasicFileName1", ... 와 같은 형태가 됩니다. 다른 속성 [`GeneratingPath`](./generatingpath/)GeneratingPath와 함께 작동합니다. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | 다수의 작은 PDF 파일이 생성될 경우 작은 PDF 파일들의 Generating Path를 가져오거나 설정합니다. 다른 속성 [`BasicFileName`](./basicfilename/)BasicFileName와 함께 작동합니다. 네 가지 출력 모드 중 하나입니다. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | 다수의 Output Streams를 가져오거나 설정합니다. 네 가지 출력 모드 중 하나입니다. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | 평탄화되지 않을 필드를 설정합니다. 이 속성이 설정되지 않으면 모든 필드가 평탄화됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Pdf 문서를 바인딩합니다. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Pdf 파일을 바인딩합니다. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Pdf 파일을 바인딩합니다. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | 객체와 출력 스트림을 닫습니다. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | 객체와 출력 스트림을 닫습니다. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | DataTable 유형의 데이터를 가져옵니다. dataTable의 각 열 이름은 대소문자를 구분하여 템플릿 PDF의 필드 이름과 동일해야 합니다. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | 모든 PDF를 저장합니다. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | 모든 PDF를 저장합니다. |

## 예제

```csharp
[C#]
//참고: mail.pdf는 7개의 텍스트 필드가 있는 템플릿 PDF입니다. NorthWind.mdb는 Microsoft Access 데이터베이스입니다.
////Common part: 데이터베이스 NorthWind.mdb에서 데이터를 가져와 DataTable에 채웁니다.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//DataTable을 구성합니다.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//데이터베이스 소스에 연결하고 데이터를 쿼리합니다.
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
////공통 부분 끝.

////case one:
////Input template pdf는 PDF 파일이며 출력은 큰 병합 스트림입니다.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////case two:
////Input template pdf는 PDF 파일이며 출력은 많은 작은 파일들입니다.
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

### 또 보기

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


