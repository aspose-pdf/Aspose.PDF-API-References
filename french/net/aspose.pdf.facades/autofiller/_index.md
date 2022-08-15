---
title: AutoFiller
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour recevoir des données de la base de données ou dune autre source de données les remplit dans les champs conçus du modèle pdf et génère enfin un nouveau fichier pdf ou flux. Il a deux modes dentrée de fichier modèle  entrée sous forme de flux ou de fichier pdf . Il dispose de quatre types de modes de sortie  un flux fusionné un fichier fusionné de nombreux petits flux de nombreux petits fichiers. Il peut recevoir des données littérales contenues dans un System.Data.DataTable.
type: docs
weight: 2170
url: /fr/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Représente une classe pour recevoir des données de la base de données ou d'une autre source de données, les remplit dans les champs conçus du modèle pdf et génère enfin un nouveau fichier pdf ou flux. Il a deux modes d'entrée de fichier modèle : entrée sous forme de flux ou de fichier pdf . Il dispose de quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers. Il peut recevoir des données littérales contenues dans un System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [AutoFiller](autofiller)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Obtient ou définit le nom de fichier de base si de nombreux petits fichiers seront générés. Le fichier généré ressemblera à "BasicFileName0","BasicFileName1",... Cela fonctionne avec une autre propriété[`GeneratingPath`](./generatingpath) GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Obtient ou définit le chemin de génération des petits fichiers pdf si de nombreux petits fichiers pdf doivent être générés. Cela fonctionne avec une autre propriété[`BasicFileName`](./basicfilename)BasicFileName. L'un des quatre modes de sortie. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Obtient ou définit les nombreux flux de sortie. L'un des quatre modes de sortie. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Définit les champs qui ne seront pas aplatis. Si cette propriété n'est pas définie, tous les champs seront aplatis. |

## Méthodes

| Nom | La description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Lie un document Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Lie un fichier Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Lie un fichier Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Ferme l'objet et les flux de sortie. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Ferme l'objet et les flux de sortie. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | Importe des données de type DataTable. Le nom de chaque colonne du dataTable doit être le même que un nom de champ du modèle pdf en respectant la casse. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Enregistre tous les fichiers PDF. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Enregistre tous les fichiers PDF. |

### Exemples

```csharp
[C#]
//Remarque : mail.pdf est un modèle pdf qui comporte sept champs de texte. NorthWind.mdb est la base de données Microsoft Access.
////Partie commune : récupérez les données de la base de données NorthWind.mdb et remplissez-les dans le DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Construire la table de données.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Connectez-vous à la source de la base de données et interrogez les données.
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
////Le modèle d'entrée pdf est un fichier pdf et la sortie est un gros flux fusionné.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////cas 2 :
////Le modèle d'entrée pdf est un fichier pdf et la sortie est composée de nombreux petits fichiers.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Remarque : mail.pdf est un modèle pdf qui comporte sept champs de texte. NorthWind.mdb est la base de données Microsoft Access.
'Partie commune : récupérez les données de la base de données NorthWind.mdb et remplissez-les dans le DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Construire le tableau de données.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Créez des colonnes pour la table de données. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Connectez-vous à la source de la base de données et interrogez les données.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Interrogez les données et insérez-les dans la table de données.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Construire la dernière colonne du Datatable.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'Fin de partie commune.

'cas un :
'Le modèle d'entrée pdf est un fichier pdf et la sortie est un gros flux fusionné.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'cas deux :
'Le modèle d'entrée pdf est un fichier pdf et la sortie est composée de nombreux petits fichiers.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Voir également

* interface [ISaveableFacade](../isaveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
