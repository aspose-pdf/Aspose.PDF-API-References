---
title: "Classe AutoFiller"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.AutoFiller. Représente une classe permettant de recevoir des données depuis une base de données ou une autre source de données et de les remplir dans les champs conçus du PDF modèle, puis génère finalement un nouveau fichier PDF ou un flux. Elle possède deux modes d'entrée de fichier modèle : en tant que flux ou en tant que fichier PDF. Elle propose quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers. Elle peut recevoir des données littérales contenues dans un System.Data.DataTable."
type: docs
weight: 4270
url: /fr/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Représente une classe permettant de recevoir des données d'une base de données ou d'une autre source de données, de les placer dans les champs conçus du modèle PDF et, enfin, de générer un nouveau fichier ou flux PDF. Elle possède deux modes d'entrée de fichier modèle : entrée sous forme de flux ou fichier PDF. Elle propose quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers. Elle peut recevoir des données littérales contenues dans un System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AutoFiller](autofiller/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Obtient ou définit le nom de fichier de base si de nombreux petits fichiers doivent être générés. Le fichier généré sera comme "BasicFileName0","BasicFileName1",... Il fonctionne avec une autre propriété [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Obtient ou définit le chemin de génération des petits fichiers PDF si de nombreux petits fichiers PDF doivent être générés. Il fonctionne avec une autre propriété [`BasicFileName`](./basicfilename/)BasicFileName. L'un des quatre modes de sortie. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Obtient ou définit les nombreux flux de sortie. L'un des quatre modes de sortie. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Définit les champs qui ne seront pas aplatis. Si cette propriété n'est pas définie, tous les champs seront aplatis. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Lie un Pdf document. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Lie un fichier Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Lie un fichier Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Ferme l'objet et les flux de sortie. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Ferme l'objet et les flux de sortie. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Importe des données de type DataTable. Le nom de chaque colonne du dataTable doit être identique à celui d'un champ du PDF modèle, en respectant la casse. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Enregistre tous les pdf. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Enregistre tous les pdf. |

## Exemples

```csharp
[C#]
//Note : mail.pdf est un PDF modèle qui possède sept champs de texte. NorthWind.mdb est la base de données Microsoft Access.
////Partie commune : Récupérez les données de la base de données NorthWind.mdb et remplissez‑les dans le DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Construisez le tableau de données.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Connectez‑vous à la source de la base de données et interrogez les données.
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
////Fin de la partie commune.

////cas un :
////Le PDF modèle d'entrée est un fichier PDF et la sortie est un grand flux fusionné.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////cas deux :
////Le PDF modèle d'entrée est un fichier PDF et la sortie est un grand nombre de petits fichiers.
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

### Voir aussi

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


