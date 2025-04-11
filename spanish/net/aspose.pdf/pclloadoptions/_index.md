---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PclLoadOptions. Representa opciones para cargar importar un archivo PCL en un documento PDF
type: docs
weight: 8300
url: /es/net/aspose.pdf/pclloadoptions/
---
## Clase PclLoadOptions

Representa opciones para cargar (importar) un archivo PCL en un documento PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Define el tamaño del lote si la conversión por lotes es aplicable a la pareja de formatos de origen y destino. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece un indicador para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Define el motor de conversión que se utilizará para la conversión |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Lista de errores de conversión. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Obtiene o establece un valor booleano que indica si los errores de conversión de PCL deben ser suprimidos. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PCL a un archivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Véase también

* clase [LoadOptions](../loadoptions/)
* interfaz [IPipelineOptions](../ipipelineoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)