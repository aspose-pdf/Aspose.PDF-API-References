---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.HtmlLoadOptions. Representa opciones para cargar/importar un archivo html en un documento pdf
type: docs
weight: 5530
url: /es/net/aspose.pdf/htmlloadoptions/
---
## Clase HtmlLoadOptions

Representa opciones para cargar/importar un archivo html en un documento pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Crea opciones de carga para convertir html en un documento pdf con una ruta base vacía. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Crea opciones de carga para convertir html en un documento pdf con una ruta base definida. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | La ruta/base url para el archivo html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Obtiene o establece los tipos de medios posibles utilizados durante el renderizado. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Obtiene o establece el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Obtiene o establece la incrustación de fuentes en el documento resultante |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Obtiene o establece la bandera que especifica que las reglas @page definidas en css anularán los valores definidos en PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Obtiene o establece el renderizado de todo el documento en una sola página |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Obtiene o establece la información de la página del documento |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Obtiene o establece la opción de diseño. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abortar. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abortar en cuyo caso la operación de carga debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.PDF en la nube, el acceso directo a los archivos referenciados es imposible: en tal caso, se debe utilizar algún código personalizado puesto en un método especial, y el delegado que hace referencia a ese método debe asignarse a este atributo. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Si la carga de datos externos referenciados en HTML requiere credenciales, puede colocarlas en este parámetro: se utilizarán durante la carga de recursos externos |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo HTML a un archivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)