---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.SvgSaveOptions. Opciones de guardado para exportar a formato SVG
type: docs
weight: 10230
url: /es/net/aspose.pdf/svgsaveoptions/
---
## Clase SvgSaveOptions

Opciones de guardado para exportar a formato SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de PDF a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si se cerrará el objeto Response después de que el documento se guarde en la respuesta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de guardado de datos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento del enum ReturnAction que especifica Continuar o Abortar. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abortar, en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Especifica si la salida se creará como un solo archivo zip. Consulte el comentario sobre las opciones 'TreatTargetFileNameAsDirectory' para ver las reglas de nombrado de los archivos svg de las páginas para documentos fuente multipágina, que también se aplican al conjunto comprimido de archivos de salida. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Este campo puede contener la estrategia de guardado que debe utilizarse (si está presente) durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas (como BMP o JPEG incrustados) en el SVG guardado. Esa estrategia debe procesar los recursos y devolver una cadena que represente la URI deseada del recurso guardado en el SVG generado. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo, y no en el código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el convertidor mismo como si no hubiera ningún código personalizado externo. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Especifica si se debe escalar el documento de salida de puntos tipográficos a píxeles. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Esta opción define si se creará un directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del archivo de salida solicitado en sí. Si es así, ese directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación). Si no, los archivos de salida de las páginas, excepto el primero, se crearán exactamente en el directorio solicitado como el archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que está definido por el número de página, por ejemplo, si define el archivo de salida "C:\AsposeTests\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C:\AsposeTests\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una al lado de la otra. En tal caso, los renderizadores de los formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de las de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a un archivo SVG

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Ver También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)