---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.HtmlSaveOptions. Opciones de guardado para exportar a formato Html
type: docs
weight: 5560
url: /es/net/aspose.pdf/htmlsaveoptions/
---
## Clase HtmlSaveOptions

Opciones de guardado para exportar a formato Html

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Inicializa una nueva instancia de la clase `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Inicializa una nueva instancia de la clase `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Inicializa una nueva instancia de la clase `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Inicializa una nueva instancia de la clase `HtmlSaveOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Define el tamaño del lote si la conversión por lotes es aplicable a la pareja de formatos de origen y destino. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de pdf a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si se cerrará el objeto Response después de que el documento se guarde en la respuesta. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Obtiene o establece la bandera que indica si los gráficos SVG encontrados (si los hay) se comprimirán (zip) en formato SVGZ durante el guardado. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Si el atributo ConvertMarkedContentToLayers se establece en verdadero, entonces todos los elementos dentro de un contenido marcado de PDF (capa) se colocarán en un div HTML con el atributo "data-pdflayer" que especifica un nombre de capa. Este nombre de capa se extraerá de las propiedades opcionales del contenido marcado de PDF. Si este atributo es falso (por defecto), no se crearán capas a partir del contenido marcado de PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Especifica el nombre de una fuente instalada que se utiliza para sustituir cualquier fuente de documento que no esté incrustada y no esté instalada en el sistema. Si es nulo, se utiliza la fuente de sustitución predeterminada. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Obtiene o establece el [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Con esta propiedad puedes definir explícitamente qué páginas del documento deben ser convertidas. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de las páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s): en las páginas resultantes siempre irán en el orden en que están presentes en el PDF de origen. Si esta lista es nula (como es por defecto), todas las páginas serán convertidas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]), se lanzará una excepción. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Obtiene o establece un valor que indica si el HTML se crea como un diseño fijo. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Este atributo especifica texto de párrafo de ancho completo para el modo de flujo, FixedLayout = falso. |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Fuentes de fuentes preguardadas. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | El texto con el tamaño especificado o menor será ignorado durante la conversión. No eliminamos este texto, lo ignoramos y no lo transferimos al archivo de salida. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Obtiene o establece la indicación de que se ignorarán los errores relacionados con la ausencia de fuentes. verdadero - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que se refieren a recursos incorrectos se omitirán durante el procesamiento. falso por defecto. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Obtiene o establece la resolución para el renderizado de imágenes. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Este atributo establece el ancho mínimo de la línea del camino gráfico. Si el grosor de la línea es menor de 1px, Adobe Acrobat lo redondea a este valor. Por lo tanto, este atributo se puede utilizar para emular este comportamiento en los navegadores HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Este atributo activa el modo en el que los glifos de texto no se agruparán en palabras y cadenas. Este modo permite mantener la máxima precisión durante la posición de los glifos en la página y se puede utilizar para convertir documentos con notas musicales o glifos que deben colocarse separados entre sí. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea verdadero. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Si el atributo RenderTextAsImage se establece en verdadero, el texto de la fuente se convierte en una imagen en HTML. Puede ser útil para hacer que el texto no sea seleccionable o si el texto HTML no se renderiza correctamente. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de guardado de datos. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indica que se guardará la fuente completa, solo admite fuentes True Type. Por defecto, SaveFullFont = falso y el convertidor guarda el subconjunto de la fuente inicial necesario para mostrar el texto del documento. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Este atributo especifica un agrupamiento secuencial de glifos y palabras en cadenas. Por ejemplo, las etiquetas y las palabras tienen un orden diferente en el HTML convertido y deseas que coincidan. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea verdadero. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'verdadero'), este atributo define si se debe crear un archivo CSS separado para cada página HTML resultante. Por defecto, este atributo es falso, por lo que se creará un gran CSS común para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un gran archivo CSS, porque en el primer caso las clases CSS son duplicados en varios archivos CSS para cada página. Por lo tanto, esta configuración es mejor utilizarla solo cuando estés interesado en el procesamiento futuro de cada página HTML de forma independiente, y por lo tanto, el tamaño del CSS de cada página por separado es el problema más crítico. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Obtiene o establece la bandera que indica si cada página del documento de origen se convertirá en su propio documento HTML de destino, es decir, si el HTML resultante se dividirá en varias páginas HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Obtiene o establece el título de la página HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | La bandera para combinar fragmentos de imagen en una sola imagen. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Si el atributo UseZOrder se establece en verdadero, los gráficos y el texto se añaden al documento HTML resultante de acuerdo con el orden Z en el documento PDF original. Si este atributo es falso, todos los gráficos se colocan como una sola capa, lo que puede causar algunos efectos innecesarios para objetos superpuestos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Este parámetro define las medidas de antialiasing requeridas durante la conversión de imágenes de fondo compuestas de PDF a HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Cuando el convertidor PDFtoHTML genera los CSS resultantes, se generan y utilizan nombres de clase CSS (algo como ".stl_01 {}" ... ".stl_NN {}") en el CSS resultante. Esta propiedad permite establecer forzosamente un prefijo de nombre de clase. Por ejemplo, si deseas que todos los nombres de clase comiencen con 'my_prefix_' (es decir, sean algo como 'my_prefix_1' ... 'my_prefix_NNN'), simplemente asigna 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanece sin cambios (es decir, se deja nula como valor), el convertidor generará los nombres de clase por sí mismo (será algo como ".stl_01 {}" ... ".stl_NN {}"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Este campo puede contener la estrategia de guardado que debe utilizarse (si está presente) durante la conversión de PDF a HTML para manejar el guardado de los CSS relacionados con el documento HTML creado en su conjunto o con sus páginas (si se generan varias páginas HTML). Si deseas manejar el archivo CSS de alguna manera específica, simplemente crea el método relevante y asigna el delegado creado a esta propiedad. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | El resultado de la conversión puede contener una o varias páginas HTML. Puedes asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de una página HTML (para ser precisos, HTML de marcado, sin archivos vinculados externos, si los hay) que se creó durante la conversión. En tal caso, el procesamiento (como el guardado del HTML de la página en un flujo o disco) puede hacerse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar la página HTML deben llevarse a cabo en el código del método proporcionado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este o aquel caso, por alguna razón, debe hacerse por el código del convertidor mismo, no en el código personalizado, establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': esto le señalará al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben hacerse en el convertidor mismo de la misma manera que si no hubiera ningún código externo personalizado para el procesamiento. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Este controlador se puede utilizar para manejar eventos de progreso de conversión, por ejemplo, se puede utilizar para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, un ejemplo del código del controlador que muestra el progreso en la consola es: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Este campo puede contener la estrategia de guardado que debe utilizarse (si está presente) durante la conversión para el manejo personalizado de los archivos de recursos referenciados creados (como imágenes y fuentes) relacionados con los nodos del HTML guardado. Esa estrategia debe procesar los recursos y devolver una cadena que represente la URL deseada del recurso guardado en el HTML generado. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Este campo puede contener un método personalizado que devuelve la URL (o plantilla de URL si la generación multipágina está activada - ver detalles a continuación) del CSS sujeto tal como debería ser colocado en el HTML resultante generado. Por ejemplo, si deseas que el convertidor coloque alguna URL específica en lugar del nombre de archivo CSS estándar en el CSS generado, simplemente debes crear y colocar en esta propiedad un método que genere la URL deseada. Si la bandera 'SplitCssIntoPages' está establecida, entonces esta estrategia personalizada (si la hay) debe devolver no la URL exacta del CSS, sino más bien una cadena de plantilla que (después de la sustitución del marcador de posición con el número de página usando la función string.Format() dentro del convertidor) puede resolverse en la URL del CSS de esta o aquella página. Ejemplos de cadenas de retorno esperadas en tal caso son: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Lista de nombres de fuentes incrustadas en PDF que no se incrustarán en HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Define una regla de codificación especial para ajustar la decodificación de PDF para el documento actual. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Define el modo de guardado de fuentes que se utilizará durante el guardado de PDF al formato deseado. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | A veces hay requisitos específicos para la generación de HTML. Este parámetro define los modos de preparación de HTML que se pueden utilizar durante la conversión de PDF a HTML para cumplir con tales requisitos específicos. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Establece el modo de posicionamiento de letras en palabras en el HTML resultante. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Este atributo representa un conjunto de configuraciones utilizadas para dibujar un borde (si lo hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. En esencia, se refiere a mostrar los bordes del papel de la página, no al borde de la página mencionado en la propia página PDF. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Este atributo representa un conjunto de márgenes adicionales de página (si los hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada se colocará en un gran archivo HTML resultante. Esta bandera define si el HTML resultante se generará de tal manera que el flujo de áreas que representan las páginas PDF en el HTML resultante dependerá de la resolución de pantalla del espectador. Supongamos que el ancho de la pantalla del lado del espectador es lo suficientemente grande como para colocar 2 o más páginas una al lado de la otra en dirección horizontal. Si esta bandera se establece en verdadero, entonces se utilizará esta oportunidad (tantas páginas se mostrarán en dirección horizontal una al lado de la otra como sea posible, luego el siguiente grupo horizontal de páginas se mostrará debajo del primero). De lo contrario, las páginas fluirán de tal manera: la siguiente página siempre va debajo de la anterior. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Define si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | El PDF convertido puede contener imágenes rasterizadas. Este parámetro define cómo deben ser manejadas durante la conversión de PDF a HTML. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Define si en el HTML creado se eliminarán las áreas vacías en la parte superior e inferior sin contenido (si las hay). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | El PDF puede contener textos que están sombreados por otros elementos (por ejemplo, por imágenes) pero que se pueden seleccionar en el portapapeles en Acrobat Reader (generalmente sucede cuando el documento contiene imágenes y textos OCR extraídos de él). Esta configuración le indica al convertidor si necesitamos guardar tales textos como textos seleccionables transparentes en el HTML resultante para imitar el comportamiento de Acrobat Reader (de lo contrario, tales textos generalmente se guardan como ocultos, no disponibles para copiar al portapapeles). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | El PDF puede contener textos transparentes que se pueden seleccionar en el portapapeles (generalmente sucede cuando el documento contiene imágenes y textos OCR extraídos de él). Esta configuración le indica al convertidor si necesitamos guardar tales textos como textos seleccionables transparentes en el HTML resultante. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Obtiene o establece la ruta al directorio al que deben guardarse todas las imágenes si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o nulo, entonces los archivos de imagen (si los hay) se guardarán junto con otros archivos vinculados al HTML. No afecta nada si se utilizó con éxito la propiedad CustomImageSavingStrategy para procesar el archivo de imagen relevante. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Obtiene o establece la ruta al directorio al que deben guardarse solo las imágenes SVG si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o nulo, entonces los archivos SVG (si los hay) se guardarán junto con otros archivos de imagen (cerca del archivo de salida) o en una carpeta especial para imágenes (si se especifica en la opción SpecialImagesFolderIfAny). No afecta nada si se utilizó con éxito la propiedad CustomImageSavingStrategy para procesar el archivo de imagen relevante. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una al lado de la otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (antialiasing) son diferentes de las de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intenta usar esta configuración para deshacerte de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, utiliza esta opción solo cuando sea realmente necesario. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | El PDF en sí no contiene marcadores de subrayado para textos. Se emula con una línea situada debajo del texto. Esta opción permite al convertidor intentar adivinar que esta o aquella línea es un subrayado de texto y poner esta información en CSS en lugar de dibujar el subrayado gráficamente. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a un archivo HTML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Ver También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* interfaz [IPageSetOptions](../ipagesetoptions/)
* interfaz [IPipelineOptions](../ipipelineoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)