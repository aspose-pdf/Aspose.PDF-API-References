---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.XmlLoadOptions. Representa opciones para cargar/importar un archivo XML en un documento PDF
type: docs
weight: 11390
url: /es/net/aspose.pdf/xmlloadoptions/
---
## Clase XmlLoadOptions

Representa opciones para cargar/importar un archivo XML en un documento PDF.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Crea un objeto `XmlLoadOptions` sin datos xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Crea un objeto `XmlLoadOptions` con datos xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Crea un objeto `XmlLoadOptions` con datos xsl. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece un indicador para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtiene datos xsl para convertir xml en un documento PDF. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo XML a un archivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Véase También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)