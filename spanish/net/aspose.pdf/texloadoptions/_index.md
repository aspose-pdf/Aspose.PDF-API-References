---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.TeXLoadOptions. Representa opciones para cargar/importar un archivo TeX en un documento PDF
type: docs
weight: 10370
url: /es/net/aspose.pdf/texloadoptions/
---
## Clase TeXLoadOptions

Representa opciones para cargar/importar un archivo TeX en un documento PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Obtiene/establece un cierto valor para primitivas de fecha/hora como año, mes, día y hora. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Obtiene/establece el directorio de entrada TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Obtiene/establece el nombre del trabajo. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Obtiene/establece una bandera que cancela las ligaduras en todas las fuentes. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Obtiene/establece el directorio de salida TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo TeX dos veces en caso de que, por ejemplo, haya referencias en el/los archivo(s) TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos a lo largo del proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor utiliza de alguna manera esos datos. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que están de alguna manera incluidos en el archivo .tex principal, por ejemplo, paquetes para los cuales no hay soporte incorporado. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Obtiene/establece la bandera que indica si se debe mostrar la salida del terminal en la consola. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Obtiene/establece la bandera que indica si se deben subconfigurar las fuentes en el archivo de salida o no. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Obtiene el resultado de la carga y compilación de TeX: si todo salió bien o si hubo comentarios/errores. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo TeX a un archivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)