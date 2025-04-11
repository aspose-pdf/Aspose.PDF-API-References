---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.DocSaveOptions. Opciones de guardado para exportar al formato Doc
type: docs
weight: 3750
url: /es/net/aspose.pdf/docsaveoptions/
---
## Clase DocSaveOptions

Opciones de guardado para exportar al formato Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Usar párrafos o saltos de línea |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Define el tamaño del lote si la conversión por lotes es aplicable a la pareja de formatos de origen y destino. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de pdf a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si se cerrará el objeto Response después de que el documento se guarde en la respuesta. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Obtiene o establece la conversión para fuentes Type3. En las fuentes Type 3, los glifos deben definirse mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en verdadero para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Formato de salida |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Resolución X de las imágenes convertidas. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Resolución Y de las imágenes convertidas. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Este parámetro se utiliza para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Especificado en cientos de por ciento de la altura de las líneas de texto. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Define la ruta (nombre de archivo o nombre de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Modo de reconocimiento. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Activar el reconocimiento de viñetas |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | En PDF, las palabras pueden estar representadas internamente con operadores que imprimen palabras imprimiendo independientemente sus letras o sílabas. Por lo tanto, para detectar palabras a veces necesitamos detectar grupos de caracteres independientes que son de hecho palabras. Esta configuración define el ancho del espacio entre elementos de texto (letras, sílabas) que deben tratarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (la presencia de un espacio vacío de al menos este ancho entre letras significa que los elementos textuales pertenecen a diferentes palabras). Está normalizado al tamaño de la fuente - 1.0 significa 100% del tamaño de fuente supuesto de la palabra. ¡ATENCIÓN! Se utiliza solo en casos cuando el PDF de origen contiene fuentes específicas poco utilizadas para las cuales no se puede calcular un valor óptimo a partir de la fuente. Por lo tanto, en la gran mayoría de los casos, este parámetro no cambia nada en el documento resultante. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Obtiene o establece el procedimiento para volver a guardar fuentes. Si se establece en verdadero, recargamos las fuentes en cada página para evitar la influencia de las propiedades de fuente anteriores y cargar la fuente recién creada desde cero. Establezca esta opción en falso si desea mejorar el rendimiento. El valor predeterminado es verdadero; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de guardado de datos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Este controlador se puede utilizar para manejar eventos de progreso de conversión, por ejemplo, se puede utilizar para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, un ejemplo del código del controlador que muestra el progreso en la consola es: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una al lado de la otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo, debido a que sus técnicas de suavizado de bordes de imagen (antialiasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario. |

### Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a un archivo DOC o DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Ver También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* interfaz [IPipelineOptions](../ipipelineoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)