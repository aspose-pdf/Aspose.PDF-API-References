---
title: AutoFiller
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una clase para recibir datos de la base de datos u otra fuente de datos los llena en los campos diseñados de la plantilla pdf y por último genera un nuevo archivo pdf o secuencia. Tiene dos modos de entrada de archivo de plantilla entrada como secuencia o archivo pdf . Tiene cuatro tipos de modos de salida un flujo fusionado un archivo fusionado muchos flujos pequeños muchos archivos pequeños. Puede recibir datos literales contenidos en un System.Data.DataTable.
type: docs
weight: 2170
url: /es/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Representa una clase para recibir datos de la base de datos u otra fuente de datos, los llena en los campos diseñados de la plantilla pdf y, por último, genera un nuevo archivo pdf o secuencia. Tiene dos modos de entrada de archivo de plantilla: entrada como secuencia o archivo pdf . Tiene cuatro tipos de modos de salida: un flujo fusionado, un archivo fusionado, muchos flujos pequeños, muchos archivos pequeños. Puede recibir datos literales contenidos en un System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AutoFiller](autofiller)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Obtiene o establece el nombre de archivo básico si se generarán muchos archivos pequeños. El archivo generado será como "BasicFileName0","BasicFileName1",... Funciona con otra propiedad[`GeneratingPath`](./generatingpath) GenerandoRuta. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Obtiene o establece la ruta de generación de los archivos PDF pequeños si se van a generar muchos archivos PDF pequeños. Funciona con otra propiedad.[`BasicFileName`](./basicfilename)BasicFileName. Uno de los cuatro modos de salida. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Obtiene o establece los muchos flujos de salida. Uno de los cuatro modos de salida. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Establece los campos que no se aplanarán. Si no se establece esta propiedad, todos los campos se aplanarán. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Enlaza un documento PDF. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Enlaza un archivo PDF. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Enlaza un archivo PDF. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Cierra el objeto y los flujos de salida. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Cierra el objeto y los flujos de salida. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | Importa datos de tipo DataTable. El nombre de cada columna de la tabla de datos debe ser el mismo que un nombre de campo de la plantilla pdf en mayúsculas y minúsculas. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Guarda todos los pdf. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Guarda todos los pdf. |

### Ejemplos

```csharp
[C#]
//Nota: mail.pdf es una plantilla pdf que tiene siete campos de texto. NorthWind.mdb es la base de datos de Microsoft Access.
////Parte común: Obtenga los datos de la base de datos NorthWind.mdb, llénelos en DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Construir la tabla de datos.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Conéctese al origen de la base de datos y consulte los datos.
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
////Fin de la parte común.

////caso uno:
////La plantilla de entrada pdf es un archivo pdf y la salida es una gran secuencia combinada.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////caso dos:
////La plantilla de entrada pdf es un archivo pdf y la salida es una gran cantidad de archivos pequeños.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Nota: mail.pdf es una plantilla pdf que tiene siete campos de texto. NorthWind.mdb es la base de datos de Microsoft Access.
'Parte común: obtenga los datos de la base de datos NorthWind.mdb y complételos en DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Construya la tabla de datos.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Crea columnas para la tabla de datos. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Conéctese al origen de la base de datos y consulte los datos.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Consultar los datos e insertarlos en la tabla de datos.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Construya la última columna de la tabla de datos.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'Fin de la parte común.

'caso uno:
'La plantilla de entrada pdf es un archivo pdf y la salida es una gran secuencia combinada.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'caso dos:
'La plantilla de entrada pdf es un archivo pdf y la salida es una gran cantidad de archivos pequeños.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Ver también

* interface [ISaveableFacade](../isaveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
