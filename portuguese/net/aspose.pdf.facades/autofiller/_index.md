---
title: Class AutoFiller
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.AutoFiller. Representa uma classe para receber dados de banco de dados ou outra fonte de dados, preenchê-los nos campos projetados do pdf modelo e, por fim, gerar um novo arquivo ou fluxo pdf. Possui dois modos de entrada de arquivo modelo entrada como um fluxo ou um arquivo pdf. Possui quatro tipos de modos de saída um fluxo mesclado, um arquivo mesclado, muitos pequenos fluxos, muitos pequenos arquivos. Pode receber dados literais contidos em um System.Data.DataTable
type: docs
weight: 4150
url: /pt/net/aspose.pdf.facades/autofiller/
---
## Classe AutoFiller

Representa uma classe para receber dados de banco de dados ou outra fonte de dados, preenchê-los nos campos projetados do pdf modelo e, por fim, gerar um novo arquivo ou fluxo pdf. Possui dois modos de entrada de arquivo modelo: entrada como um fluxo ou um arquivo pdf. Possui quatro tipos de modos de saída: um fluxo mesclado, um arquivo mesclado, muitos pequenos fluxos, muitos pequenos arquivos. Pode receber dados literais contidos em um System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [AutoFiller](autofiller/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Obtém ou define o nome básico do arquivo se muitos pequenos arquivos forem gerados. O arquivo gerado será como "BasicFileName0","BasicFileName1",... Funciona com outra propriedade [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Obtém ou define o Caminho de Geração dos pequenos arquivos pdf se muitos pequenos arquivos pdf forem gerados. Funciona com outra propriedade [`BasicFileName`](./basicfilename/)BasicFileName. Um dos quatro modos de saída. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Obtém ou define os muitos Fluxos de Saída. Um dos quatro modos de saída. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Define os campos que não serão achatados. Se esta propriedade não for definida, todos os campos serão achatados. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Vincula um documento Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Vincula um arquivo Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Vincula um arquivo Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Fecha o objeto e os fluxos de saída. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Fecha o objeto e os fluxos de saída. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Importa dados do tipo DataTable. O nome de cada coluna do dataTable deve ser o mesmo que o nome de um campo do pdf modelo, respeitando maiúsculas e minúsculas. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Salva todos os pdfs. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Salva todos os pdfs. |

## Exemplos

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

### Veja Também

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)