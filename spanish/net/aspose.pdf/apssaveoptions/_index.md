---
title: Class ApsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.ApsSaveOptions. Opciones de guardado para exportar al formato XML APS
type: docs
weight: 2760
url: /es/net/aspose.pdf/apssaveoptions/
---
## Clase ApsSaveOptions

Opciones de guardado para exportar al formato XML APS.

```csharp
public class ApsSaveOptions : UnifiedSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ApsSaveOptions](apssaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de PDF a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si se cerrará el objeto Response después de que el documento se guarde en la respuesta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de datos guardados. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento del enum ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de guardado continúa; sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una cerca de la otra. En tal caso, los renderizadores de los formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a un archivo APS

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-APS.pdf");

	// The path to output APS File.
	var apsFile = Path.Combine(dataDir, "PDF-to-APS.aps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ApsSaveOptions  	
		ApsSaveOptions saveOptions = new ApsSaveOptions();
		
		// Save APS file
		pdfDocument.Save(apsFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-APS.pdf")

    ' The path to output APS File.
    Dim apsFile = Path.Combine(dataDir, "PDF-to-APS.aps")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize ApsSaveOptions    
        Dim saveOptions As ApsSaveOptions = New ApsSaveOptions()
 
        ' Save APS file
        pdfDocument.Save(apsFile, saveOptions)
    End Using
```

### Ver También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)