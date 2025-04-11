---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.EpubLoadOptions. Contiene opciones para cargar/importar un archivo EPUB en un documento pdf
type: docs
weight: 4050
url: /es/net/aspose.pdf/epubloadoptions/
---
## Clase EpubLoadOptions

Contiene opciones para cargar/importar un archivo EPUB en un documento pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Crea opciones de carga predeterminadas para convertir un archivo EPUB en un documento pdf. Tamaño de página pdf predeterminado - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Crea opciones de carga con un tamaño de página especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Obtiene o establece el Css personalizado que se aplicará al abrir el documento Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece un indicador para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Obtiene una referencia al objeto que representa la información de márgenes. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Obtiene o establece el tamaño de página de salida para la importación. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento del enum ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Representa el modo de uso del área de márgenes - define el tratamiento de las instrucciones (si las hay) del CSS del documento importado relacionadas con el uso de márgenes. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ¡ATENCIÓN! La función está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED revelado para el documento de muestra. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.), generalmente tienen un diseño flotante, por lo que permite ajustar el tamaño de página requerido. Pero a veces el contenido tiene posiciones o tamaños horizontales especificados que no permiten colocar el contenido en el tamaño de página requerido. En tal caso, podemos definir qué se debe hacer en este caso (es decir, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante). |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo EPUB a un archivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)