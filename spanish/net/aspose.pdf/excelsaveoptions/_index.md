---
title: Class ExcelSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.ExcelSaveOptions. Opciones de guardado para exportar a formato Excel
type: docs
weight: 4080
url: /es/net/aspose.pdf/excelsaveoptions/
---
## Clase ExcelSaveOptions

Opciones de guardado para exportar a formato Excel

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de PDF a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si se cerrará el objeto Response después de que el documento se guarde en la respuesta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | Formato de salida |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | Establezca verdadero si necesita insertar una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es falso; significa que no se insertará una columna en blanco. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | Establezca verdadero si necesita minimizar el número de hojas de cálculo en el libro de trabajo resultante. El valor predeterminado es falso; significa que se guardará cada página PDF como una hoja de cálculo separada. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de datos guardados. |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | Establezca verdadero para usar una división uniforme de columnas a través del documento. El valor predeterminado es falso; significa que la división de columnas será independiente para cada página. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abortar. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abortar, en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una cerca de la otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a un archivo XLS o XLSX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// The path to output xls or xlsx File.
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ExcelSaveOptions	
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// Save xls or xlsx file
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### Ver También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)