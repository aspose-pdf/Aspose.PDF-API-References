---
title: HtmlSaveOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Guardar opciones para exportar a formato HTML
type: docs
weight: 3430
url: /es/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Guardar opciones para exportar a formato HTML

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions#constructor)() | Inicializa una nueva instancia del[`HtmlSaveOptions`](../htmlsaveoptions) clase. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_3)(bool) | Inicializa una nueva instancia del[`HtmlSaveOptions`](../htmlsaveoptions) clase. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_1)(HtmlDocumentType) | Inicializa una nueva instancia del[`HtmlSaveOptions`](../htmlsaveoptions) clase. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_2)(HtmlDocumentType, bool) | Inicializa una nueva instancia del[`HtmlSaveOptions`](../htmlsaveoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize) { get; set; } | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtiene o establece un valor booleano que indica que el objeto de respuesta se cerrará después de que el documento se guarde en la respuesta. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany) { get; set; } | Obtiene o establece el indicador que indica si los gráficos SVG encontrados (si los hay) se comprimirán (comprimirán) en formato SVGZ durante el guardado |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers) { get; set; } | Si el atributo ConvertMarkedContentToLayers se establece en verdadero, todos los elementos dentro de un PDF marcado contenido (capa) se colocarán en un div HTML con el atributo "data-pdflayer" que especifica un nombre de capa. Este nombre de capa se extraerá de las propiedades opcionales de PDF contenido marcado. Si este atributo es falso (por defecto), no se creará ninguna capa a partir de contenido marcado en PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname) { get; set; } | Especifica el nombre de una fuente instalada que se utiliza para sustituir cualquier fuente de documento que no esté incrustada ni instalada en el sistema. Si es nulo, se utiliza la fuente de sustitución predeterminada. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype) { get; set; } | Obtiene o establece el[`HtmlDocumentType`](../htmldocumenttype) . |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages) { get; set; } | Con esta propiedad, puede definir explícitamente qué páginas del documento deben convertirse. Las páginas de esta lista deben tener números basados en 1. Es decir, números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]) El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s) - en las páginas de resultados siempre irán en orden en el que están presentes en el PDF de origen. Si esta lista es nula (como lo es de forma predeterminada), todas las páginas se convertirán. Si algún número de página de esta lista sale del rango de páginas actuales (1-[ cantidadDePáginasEnDocumento]) se lanzará una excepción. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Este atributo activó la funcionalidad para extraer imágenes o texto para documentos PDF con subcapa OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout) { get; set; } | Obtiene o establece un valor que indica si ese HTML se crea como diseño fijo. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth) { get; set; } | Este atributo especifica texto de párrafo de ancho completo para el modo de flujo, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources) { get; } | Fuentes de fuentes de fuentes guardadas previamente. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution) { get; set; } | Obtiene o establece la resolución para la representación de imágenes. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth) { get; set; } | Este atributo establece el ancho mínimo de la línea de la ruta del gráfico. Si el grosor de la línea es inferior a 1 px, Adobe Acrobat lo redondea a este valor. Entonces, este atributo puede usarse para emular este comportamiento para navegadores HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping) { get; set; } | Este atributo activa el modo cuando los glifos de texto no se agruparán en palabras y cadenas Este modo permite mantener la máxima precisión durante el posicionamiento de los glifos en la página y puede usarse para convertir documentos con notas musicales o glifos que deben colocarse por separado entre sí. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea verdadero. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage) { get; set; } | Si el atributo RenderTextAsImage se establece en verdadero, el texto del origen se convierte en una imagen en HTML. Puede ser útil para hacer que el texto no se pueda seleccionar o el texto HTML no se representa correctamente. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Formato de guardado de datos. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping) { get; set; } | Este atributo especifica una agrupación secuencial de glifos y palabras en cadenas Por ejemplo, las etiquetas y las palabras tienen un orden diferente en HTML convertido y desea que coincidan. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea verdadero. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages) { get; set; } | Cuando se selecciona el modo multipágina (es decir, 'Dividir en páginas' es 'verdadero'), este atributo define si se debe crear un archivo CSS separado para cada página HTML de resultado. De forma predeterminada, este atributo es falso, por lo que se creará uno gran CSS común para todas las páginas creadas. Tamaño resumido de todos los CSS generados en este modo (un CSS por página) generalmente mucho más que el tamaño de un archivo CSS grande, porque en el caso anterior, las clases CSS están duplicadas en tal caso en varios archivos CSS para cada página. Entonces, esto la configuración es peor si se usa solo cuando está interesado en el procesamiento futuro de cada página HTML de forma independiente y, por lo tanto, el tamaño de CSS de cada página separada es el problema más crítico. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages) { get; set; } | Obtiene o establece el indicador que indica si cada página del documento de origen se convertirá en su propio documento HTML de destino, , es decir, si el HTML resultante se dividirá en varias páginas HTML. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder) { get; set; } | Si el atributo UseZORder se establece en verdadero, los gráficos y el texto se agregan al documento HTML resultante según el orden Z en el documento PDF original. Si este atributo es falso, todos los gráficos se ponen como una sola capa, lo que puede causar algunos efectos innecesarios para los objetos superpuestos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Devolución de llamada para manejar cualquier advertencia generada. WarningHandler devuelve el elemento de enumeración ReturnAction especificando Continuar o Anular. Continuar es la acción predeterminada y la operación Guardar continúa; sin embargo, el usuario también puede devolver Anular, en cuyo caso la operación Guardar debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing) | Este parámetro define las medidas de suavizado requeridas durante la conversión de imágenes de fondo compuestas de PDF a HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix) | Cuando el convertidor de PDF a HTML genera CSS de resultado, los nombres de clase de CSS (algo así como ".stl_01 {}" ... ".stl_NN {}) se generan y se utilizan en el CSS de resultado. Esta propiedad permite establecer por la fuerza el prefijo de nombre de clase Por ejemplo, si desea que todos los nombres de clase comiencen con 'my_prefix_' (es decir, algo así como 'my_prefix_1' ... 'my_prefix_NNN'), luego simplemente asigne 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanecerá intacta (es decir, nulo se dejará como valor), el convertidor luego generará nombres de clase en sí mismo (será algo así como ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy) | Este campo puede contener una estrategia de guardado que debe usarse (si está presente) durante la conversión de Pdf a Html para manejar el guardado de CSSes relacionados al documento HTML creado en su totalidad o a sus páginas (si se generan varias páginas HTML) Si lo desea maneje el archivo CSS de alguna manera específica, solo cree el método relevante y asigne el delegado creado a partir de él a esta propiedad. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy) | El resultado de la conversión puede contener una o varias páginas HTML Puede asignar a este delegado de propiedad creado a partir de un método personalizado que implementa el procesamiento de una página HTML (para ser precisos, marcado HTML, sin archivos vinculados externos, si los hay) que se creó durante la conversión. En tal caso, el procesamiento (como guardar el HTML de la página en flujo o disco) se puede realizar en ese código personalizado. En tal caso, se deben realizar todas las acciones necesarias para guardar la página HTML en el código del método proporcionado, porque no se usará el guardado del resultado en el código del convertidor. Si el procesamiento de este o aquel caso por alguna razón debe ser realizado por el propio código del convertidor, no en el código personalizado, establezca en el indicador de código personalizado 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': indicará al convertidor que todos los los pasos necesarios para el procesamiento de ese recurso se deben realizar en el convertidor mismo de la misma manera como si no hubiera ningún código personalizado externo para procesar . |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler) | Este controlador se puede usar para manejar eventos de progreso de conversión fe, se puede usar para mostrar la barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, el ejemplo del código del controlador que muestra el progreso en la consola es: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy) | Este campo puede contener una estrategia de guardado que se debe usar (si está presente) durante la conversión para el manejo personalizado de archivos de recursos referenciados creados (como imágenes y fuentes) relacionados con nodos de HTML guardado. Esa estrategia debe procesar recursos y devolver una cadena que representa la URL deseada del recurso guardado en HTML generado. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation) | Este campo puede contener un método personalizado que devuelve URL (o plantilla de URL si la generación de varias páginas está activada; consulte los detalles a continuación) de subject CSS, ya que debe colocarse en el resultado generado HTML. Si desea que el convertidor coloque una URL específica en lugar de standard El nombre del archivo CSS en el CSS generado, luego debe crear y colocar en esta propiedad el método que genera la URL deseada. Si se establece el indicador 'SplitCssIntoPages', entonces esta estrategia personalizada (si corresponde) no debe devolver la URL exacta de CSS sino una plantilla la cadena that (después de la sustitución del marcador de posición con el número de página con la función string.Format() dentro del convertidor) se puede resolver en URL para esta o la URL de CSS de esa página. Ejemplos de cadena de retorno esperada en tal caso son: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist) | Lista de nombres de fuentes incrustadas en PDF que no pueden incrustarse en HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy) | Define la regla especial de codificación para ajustar la decodificación de PDF para el documento actual |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode) | Define el modo de guardado de fuente que se usará durante el guardado de PDF en el formato deseado |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode) | A veces existen requisitos específicos para la generación de marcado HTML. Este parámetro define los modos de preparación de HTML que se pueden usar durante la conversión de PDF a HTML para cumplir con dichos requisitos específicos. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod) | Establece el modo de posicionamiento de las letras en las palabras en el resultado HTML |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany) | Este atributo representa un conjunto de configuraciones utilizadas para dibujar el borde (si lo hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. En esencia, se trata de mostrar los bordes del papel de la página, no el borde de la página al que se hace referencia en la página PDF en sí. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany) | Este atributo representa un conjunto de margen de página adicional (si lo hay) en el documento HTML de resultado alrededor del área que representa la página PDF de origen. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize) | Si el atributo 'SplitOnPages=false', el HTML completo que representa todas las páginas PDF de entrada se colocará en un gran archivo HTML de resultado. Este indicador define si el resultado HTML se generará de tal manera que el flujo de áreas que representan páginas PDF en el resultado HTML dependerá de la resolución de pantalla del visor. Supongamos que el ancho de la pantalla en el lado del espectador es lo suficientemente grande como para colocar 2 o más páginas, una cerca de la otra en dirección horizontal. Si este indicador se establece en verdadero, entonces se usará esta oportunidad (se mostrarán tantas páginas en dirección horizontal una cerca de otra como sea posible, luego el siguiente grupo horizontal de páginas se mostrará debajo de la primera). De lo contrario, las páginas fluirán de esta manera: la página siguiente va siempre debajo de la anterior. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode) | Define si los archivos de referencia (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode) | El PDF convertido puede contener imágenes rasterizadas Este parámetro define cómo deben manejarse durante la conversión de PDF a HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom) | Define si en el HTML creado se eliminará el área vacía superior e inferior sin ningún contenido (si lo hay). |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont) | Indica que se guardará la fuente completa, solo admite fuentes True Type. De manera predeterminada, SaveFullFont = false y el convertidor guarda el subconjunto de la fuente inicial necesaria para mostrar el texto del documento. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts) | Pdf puede contener textos sombreados por otros elementos (por ejemplo, por imágenes), pero se puede seleccionar en el portapapeles en Acrobat Reader (generalmente sucede cuando el documento contiene imágenes y textos OCR extraídos de él). Esta configuración le dice al convertidor si necesita guardar dichos textos como transparent textos seleccionables en el resultado HTML para imitar el comportamiento de Acrobat Reader (de lo contrario, dichos textos generalmente se guardan como ocultos, no disponibles para copiar al portapapeles) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts) | Pdf puede contener textos transparentes que se pueden seleccionar en el portapapeles (generalmente sucede cuando el documento contiene imágenes y textos OCRed extraídos de él). Esta configuración le dice al convertidor si necesitamos guardar dichos textos como transparent textos seleccionables en el resultado HTML |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages) | Obtiene o establece la ruta al directorio en el que se deben guardar las imágenes si se encuentran al guardar el documento como HTML. Si el parámetro está vacío o es nulo , los archivos de imagen (si los hay) se guardarán junto con otros archivos vinculados a HTML No afecta nada si la propiedad CustomImageSavingStrategy se usó correctamente para procesar el archivo de imagen relevante. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages) | Obtiene o establece la ruta al directorio en el que se deben guardar solo las imágenes SVG si se encuentran al guardar el documento como HTML. Si el parámetro está vacío o es nulo , los archivos SVG (si los hay) se guardarán junto con otros archivos de imagen (cerca del archivo de salida) o en una carpeta especial para imágenes (si se especificó en la opción SpecialImagesFolderIfAny). No afecta nada si la propiedad CustomImageSavingStrategy se usó correctamente para procesar el archivo de imagen relevante. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | A veces, los archivos PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico juntas colocadas una cerca de otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo , causa que sus técnicas de suavizado de bordes de imagen (anti-aliasing) sean diferentes de Acrobat Reader. Si parece que el documento exportado contiene límites tan visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de de eso efecto no deseado ¡ATENCIÓN! Esta optimización de la calidad suele ralentizar esencialmente la conversión, así que, utilice esta opción solo cuando sea realmente necesario. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss) | PDF en sí mismo no contiene marcadores de subrayado para textos. Emuló con una línea situada debajo del texto. Esta opción permite que el convertidor intente adivinar que esta o aquella línea es un texto subrayado y coloque esta información en CSS en lugar de dibujar o subrayar gráficamente |

### Ver también

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPageSetOptions](../ipagesetoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->