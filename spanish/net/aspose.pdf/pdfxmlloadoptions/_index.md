---
title: Class PdfXmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PdfXmlLoadOptions. Opciones de carga para el formato PdfXml
type: docs
weight: 8460
url: /es/net/aspose.pdf/pdfxmlloadoptions/
---
## Clase PdfXmlLoadOptions

Opciones de carga para el formato PdfXml.

```csharp
public class PdfXmlLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfXmlLoadOptions](pdfxmlloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDFXML a un archivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PDFXML File.
	string pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf");

	// Initialize PdfXmlLoadOptions	
	PdfXmlLoadOptions pdfXmlLoadOptions = new PdfXmlLoadOptions();
		
	using (Document pdfDocument = new Document(pdfXmlFile, pdfXmlLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDFXML File.
    Dim pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf")
 
    ' Initialize PdfXmlLoadOptions  
    Dim pdfXmlLoadOptions As PdfXmlLoadOptions = New PdfXmlLoadOptions()
 
    Using pdfDocument As Document = New Document(pdfXmlFile, pdfXmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)