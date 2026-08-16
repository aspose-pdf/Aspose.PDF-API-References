---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato Html"
type: docs
weight: 1990
url: /es/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Opciones de guardado para exportar al formato Html

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Inicializa una nueva instancia de la clase HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Inicializa una nueva instancia de la clase {@code HtmlSaveOptions}. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Inicializa una nueva instancia de la clase HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Inicializa una nueva instancia de la clase HtmlSaveOptions. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada no se dividirá en diferentes páginas HTML, sino que se colocará en un único archivo HTML resultante grande. Pero cada página PDF de origen se representará con su propia área rectangular en HTML (si es necesario, esas áreas pueden estar delimitadas para mostrar los bordes del papel de la página con el atributo especial 'PageBorderIfAny'). Este parámetro define el ancho del margen que se dejará obligatoriamente alrededor de esas áreas HTML de salida que representan las páginas del documento PDF de origen. En esencia define el intervalo garantizado entre las representaciones HTML de las páginas "paper" del PDF en este modo de conversión. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Este parámetro define las medidas de antialiasing requeridas durante la conversión de imágenes de fondo compuestas de PDF a HTML. |
| [getBatchSize](#getBatchSize--) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | Cuando el conversor PDFtoHTML genera los CSS resultantes, los nombres de clases CSS (algo como ".stl_01 {}" ... ".stl_NN {}") se generan y se utilizan en el CSS resultante. Esta propiedad permite establecer forzadamente un prefijo para los nombres de clase. Por ejemplo, si desea que todos los nombres de clase comiencen con 'my_prefix_' (es decir, algo como 'my_prefix_1' ... 'my_prefix_NNN'), simplemente asigne 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanece sin tocar (es decir, se deja null como valor), el conversor generará los nombres de clase por sí mismo (será algo como ".stl_01 {}" ... ".stl_NN {}"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión de PDF a HTML para el manejo del guardado de los CSS relacionados con el documento HTML creado en su totalidad o con sus páginas (si se generan varias páginas HTML). Si desea manejar el archivo CSS de una manera específica, simplemente cree el método correspondiente y asigne el delegado creado a partir de él a esta propiedad. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | El resultado de la conversión puede contener una o varias páginas HTML. Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implementa el procesamiento de una página HTML (para ser precisos, markup-HTML, sin archivos vinculados externos, si los hay) que se creó durante la conversión. En tal caso, el procesamiento (como guardar el HTML de la página en un flujo o en disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar la página HTML deben llevarse a cabo en el código del método suministrado, porque guardar el resultado en el código del convertidor no se utilizará. Si el procesamiento para este u otro caso, por alguna razón, debe ser realizado por el propio código del convertidor, no en código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': indicará al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor de la misma manera que si no hubiera ningún código personalizado externo para el procesamiento. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Este controlador puede usarse para manejar eventos de progreso de conversión, por ejemplo, puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas; un ejemplo del código del controlador que muestra el progreso en la consola es: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de recursos referenciados creados (como imágenes y fuentes) relacionados con los nodos del HTML guardado. Esa estrategia debe procesar los recursos y devolver una cadena que represente la URL deseada del recurso guardado en el HTML generado. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Este campo puede contener un método personalizado que devuelva la URL (o plantilla de URL si la generación multipágina está activada - ver detalles a continuación) del CSS objetivo tal como debe insertarse en el HTML resultante generado. Por ejemplo, si desea que el convertidor coloque una URL específica en lugar del nombre de archivo CSS estándar en el CSS generado, entonces simplemente debe crear y asignar a esta propiedad un método que genere la URL deseada. Si la bandera 'SplitCssIntoPages' está establecida, entonces esta estrategia personalizada (si existe) debe devolver no la URL exacta del CSS sino una cadena de plantilla que (después de sustituir el marcador de posición con el número de página mediante la función String.Format() dentro del convertidor) pueda resolverse en la URL del CSS de esa página. Ejemplos de la cadena de retorno esperada en tal caso son: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | Especifica el nombre de una fuente instalada que se utiliza para sustituir cualquier fuente del documento que no esté incrustada y no esté instalada en el sistema. Si es nulo, se utiliza la fuente de sustitución predeterminada. |
| [getDocumentType](#getDocumentType--) | Obtiene el {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Lista de nombres de fuentes incrustadas en PDF que no se incrustan en HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Con esta propiedad puedes definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Este atributo especifica texto de párrafo de ancho completo para el modo Flujo, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Define una regla especial de codificación para ajustar la decodificación de PDF para el documento actual |
| [getFontSavingMode](#getFontSavingMode--) | Define el modo de guardado de fuentes que se utilizará al guardar el PDF en el formato deseado |
| [getFontSources](#getFontSources--) | <p> Fuentes de fuentes preguardadas. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | A veces existen requisitos específicos para la generación de marcado HTML. Este parámetro define los modos de preparación de HTML que pueden usarse durante la conversión de PDF a HTML para cumplir con dichos requisitos específicos. |
| [getImageResolution](#getImageResolution--) | Obtiene o establece la resolución para la renderización de imágenes. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Establece el modo de posicionamiento de letras en palabras en el HTML resultante |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Este atributo establece el ancho mínimo de la línea de ruta gráfica. Si el grosor de la línea es inferior a 1px, Adobe Acrobat lo redondea a este valor. Por lo tanto, este atributo puede usarse para emular este comportamiento en los navegadores HTML. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Este atributo representa un conjunto de configuraciones usadas para dibujar el borde (si lo hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. En esencia, se refiere a la visualización de los bordes del papel de la página, no al borde de la página referenciado en la propia página PDF. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Este atributo representa un conjunto de márgenes de página adicionales (si los hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Define si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | El PDF convertido puede contener imágenes raster. Este parámetro define cómo deben manejarse durante la conversión de PDF a HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Obtiene o establece la ruta al directorio donde deben guardarse las imágenes si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos de imagen (si los hay) se guardarán junto con los demás archivos vinculados al HTML. No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Obtiene o establece la ruta al directorio donde deben guardarse solo las imágenes SVG si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos SVG (si los hay) se guardarán junto con los demás archivos de imagen (cerca del archivo de salida) o en una carpeta especial para imágenes (si se especifica en la opción SpecialImagesFolderIfAny). No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente. |
| [getTitle](#getTitle--) | Obtiene o establece el título de la página HTML. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Obtiene la bandera que indica si los gráficos SVG encontrados (si los hay) se comprimirán (en zip) al formato SVGZ durante el guardado. Valor: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Si el atributo ConvertMarkedContentToLayers está establecido en true, entonces todos los elementos dentro de un contenido marcado de PDF (capa) se colocarán en un div HTML con el atributo \"data-pdflayer\" que especifica el nombre de la capa. Este nombre de capa se extraerá de las propiedades opcionales del contenido marcado de PDF. Si este atributo es false (por defecto), no se crearán capas a partir del contenido marcado de PDF. |
| [isFixedLayout](#isFixedLayout--) | Obtiene un valor que indica si el HTML se crea como diseño fijo. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada se colocará en un único archivo HTML de resultado grande. Esta bandera define si el HTML de resultado se generará de manera que el flujo de áreas que representan páginas PDF en el HTML de resultado dependa de la resolución de pantalla del visor. Supongamos que el ancho de pantalla del visor es lo suficientemente grande como para colocar 2 o más páginas una al lado de la otra en dirección horizontal. Si esta bandera se establece en true, entonces se utilizará esta oportunidad (se mostrarán tantas páginas como sea posible en dirección horizontal una al lado de la otra, y luego el siguiente grupo horizontal de páginas se mostrará bajo el primero). De lo contrario, las páginas fluirán de la siguiente manera: la página siguiente siempre se coloca bajo la anterior. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Este atributo activa el modo en el que los glifos de texto no se agruparán en palabras y cadenas. Este modo permite mantener la máxima precisión al posicionar los glifos en la página y puede usarse para la conversión de documentos con notas musicales o glifos que deben colocarse por separado unos de otros. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Define si en el HTML creado se eliminará el área vacía superior e inferior sin contenido (si la hay). |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Si el atributo RenderTextAsImage se establece en true, el texto de la fuente se convierte en una imagen en HTML. Puede ser útil para hacer que el texto no sea seleccionable o cuando el texto HTML no se renderiza correctamente. |
| [isSaveFullFont](#isSaveFullFont--) | Indica que se guardará la fuente completa, solo admite fuentes True Type. Por defecto SaveFullFont = false y el conversor guarda el subconjunto de la fuente inicial necesario para mostrar el texto del documento. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | El PDF puede contener textos que están sombreados por otros elementos (p. ej., por imágenes) pero que pueden seleccionarse al portapapeles en Acrobat Reader (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado para imitar el comportamiento de Acrobat Reader (de lo contrario, esos textos suelen guardarse como ocultos, no disponibles para copiar al portapapeles). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | El PDF puede contener textos transparentes que pueden seleccionarse al portapapeles (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Este atributo especifica una agrupación secuencial de glifos y palabras en cadenas. Por ejemplo, las etiquetas y las palabras tienen un orden diferente en el HTML convertido y se desea que coincidan. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'true'), este atributo define si se debe crear un archivo CSS separado para cada página HTML de resultado. Por defecto este atributo es false, por lo que se crea un único CSS común grande para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un solo CSS grande, porque en el primer caso las clases CSS se duplican en varios archivos CSS para cada página. Por lo tanto, esta configuración es menos recomendable y solo debe usarse cuando le interese procesar cada página HTML de forma independiente en el futuro, y por consiguiente el tamaño del CSS de cada página individual sea el factor más crítico. |
| [isSplitIntoPages](#isSplitIntoPages--) | Obtiene la bandera que indica si cada página del documento fuente se convertirá en su propio documento HTML de destino, es decir, si el HTML de resultado se dividirá en varias páginas HTML. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | El propio PDF no contiene marcadores de subrayado para los textos. Se emula con una línea situada bajo el texto. Esta opción permite al conversor intentar adivinar que una u otra línea es el subrayado del texto y colocar esta información en CSS en lugar de dibujar el subrayado gráficamente. |
| [isUseZOrder](#isUseZOrder--) | Si el atributo UseZORder se establece en true, los gráficos y el texto se añaden al documento HTML resultante de acuerdo con el orden Z del documento PDF original. Si este atributo es false, todos los gráficos se colocan en una sola capa, lo que puede causar efectos innecesarios en los objetos superpuestos. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada no se dividirá en diferentes páginas HTML, sino que se colocará en un único archivo HTML resultante grande. Pero cada página PDF de origen se representará con su propia área rectangular en HTML (si es necesario, esas áreas pueden estar delimitadas para mostrar los bordes del papel de la página con el atributo especial 'PageBorderIfAny'). Este parámetro define el ancho del margen que se dejará obligatoriamente alrededor de esas áreas HTML de salida que representan las páginas del documento PDF de origen. En esencia define el intervalo garantizado entre las representaciones HTML de las páginas "paper" del PDF en este modo de conversión. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Este parámetro define las medidas de antialiasing requeridas durante la conversión de imágenes de fondo compuestas de PDF a HTML. |
| [setBatchSize](#setBatchSize-int-) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Establece la bandera que indica si los gráficos SVG encontrados (si los hay) se comprimirán (en zip) al formato SVGZ durante el guardado Valor: El {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Si el atributo ConvertMarkedContentToLayers está establecido en true, entonces todos los elementos dentro de un contenido marcado de PDF (capa) se colocarán en un div HTML con el atributo \"data-pdflayer\" que especifica el nombre de la capa. Este nombre de capa se extraerá de las propiedades opcionales del contenido marcado de PDF. Si este atributo es false (por defecto), no se crearán capas a partir del contenido marcado de PDF. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | Cuando el conversor PDFtoHTML genera los CSS resultantes, los nombres de clases CSS (algo como ".stl_01 {}" ... ".stl_NN {}") se generan y se utilizan en el CSS resultante. Esta propiedad permite establecer forzadamente un prefijo para los nombres de clase. Por ejemplo, si desea que todos los nombres de clase comiencen con 'my_prefix_' (es decir, algo como 'my_prefix_1' ... 'my_prefix_NNN'), simplemente asigne 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanece sin tocar (es decir, se deja null como valor), el conversor generará los nombres de clase por sí mismo (será algo como ".stl_01 {}" ... ".stl_NN {}"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión de PDF a HTML para el manejo del guardado de los CSS relacionados con el documento HTML creado en su totalidad o con sus páginas (si se generan varias páginas HTML). Si desea manejar el archivo CSS de una manera específica, simplemente cree el método correspondiente y asigne el delegado creado a partir de él a esta propiedad. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | El resultado de la conversión puede contener una o varias páginas HTML Puedes asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de una página HTML (para ser precisos - markup-HTML, sin archivos vinculados externos si los hay) que se creó durante la conversión. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Este manejador puede usarse para manejar eventos de progreso de conversión, p. ej. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de recursos referenciados creados (como imágenes y fuentes) relacionados con los nodos del HTML guardado. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Este campo puede contener un método personalizado que devuelva la URL (o plantilla de URL si la generación multipágina está activada - ver detalles a continuación) del CSS de referencia tal como debe insertarse en el HTML resultante generado. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Especifica el nombre de una fuente instalada que se utiliza para sustituir cualquier fuente del documento que no esté incrustada y no esté instalada en el sistema. Si es nulo, se utiliza la fuente de sustitución predeterminada. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Establece el {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Lista de nombres de fuentes incrustadas en PDF que no se incrustan en HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Con esta propiedad puedes definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción. |
| [setFixedLayout](#setFixedLayout-boolean-) | Establece un valor que indica si ese HTML se crea como diseño fijo. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Este atributo especifica texto de párrafo de ancho completo para el modo Flujo, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Define una regla especial de codificación para ajustar la decodificación de PDF para el documento actual |
| [setFontSavingMode](#setFontSavingMode-int-) | Define el modo de guardado de fuentes que se utilizará al guardar el PDF en el formato deseado |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | A veces existen requisitos específicos para la generación de marcado HTML. Este parámetro define los modos de preparación de HTML que pueden usarse durante la conversión de PDF a HTML para cumplir con dichos requisitos específicos. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto |
| [setImageResolution](#setImageResolution-int-) | Obtiene o establece la resolución para la renderización de imágenes. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Establece el modo de posicionamiento de letras en palabras en el HTML resultante |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Este atributo establece el ancho mínimo de la línea de ruta gráfica. Si el grosor de la línea es inferior a 1px, Adobe Acrobat lo redondea a este valor. Por lo tanto, este atributo puede usarse para emular este comportamiento en los navegadores HTML. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Este atributo representa el conjunto de configuraciones usadas para dibujar un borde (si lo hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Este atributo representa un conjunto de márgenes de página adicionales (si los hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada se colocará en un único archivo HTML de resultado grande. Esta bandera define si el HTML de resultado se generará de manera que el flujo de áreas que representan páginas PDF en el HTML de resultado dependa de la resolución de pantalla del visor. Supongamos que el ancho de pantalla del visor es lo suficientemente grande como para colocar 2 o más páginas una al lado de la otra en dirección horizontal. Si esta bandera se establece en true, entonces se utilizará esta oportunidad (se mostrarán tantas páginas como sea posible en dirección horizontal una al lado de la otra, y luego el siguiente grupo horizontal de páginas se mostrará bajo el primero). De lo contrario, las páginas fluirán de la siguiente manera: la página siguiente siempre se coloca bajo la anterior. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Define si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Este atributo activa el modo en el que los glifos de texto no se agruparán en palabras y cadenas. Este modo permite mantener la máxima precisión al posicionar los glifos en la página y puede usarse para la conversión de documentos con notas musicales o glifos que deben colocarse por separado unos de otros. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | El PDF convertido puede contener imágenes raster. Este parámetro define cómo deben manejarse durante la conversión de PDF a HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Define si en el HTML creado se eliminará el área vacía superior e inferior sin contenido (si la hay). |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Si el atributo RenderTextAsImage se establece en true, el texto de la fuente se convierte en una imagen en HTML. Puede ser útil para hacer que el texto no sea seleccionable o cuando el texto HTML no se renderiza correctamente. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Indica que se guardará la fuente completa, solo admite fuentes True Type. Por defecto SaveFullFont = false y el conversor guarda el subconjunto de la fuente inicial necesario para mostrar el texto del documento. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | El PDF puede contener textos que están sombreados por otros elementos (p. ej., por imágenes) pero que pueden seleccionarse al portapapeles en Acrobat Reader (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado para imitar el comportamiento de Acrobat Reader (de lo contrario, esos textos suelen guardarse como ocultos, no disponibles para copiar al portapapeles). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | El PDF puede contener textos transparentes que pueden seleccionarse al portapapeles (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Este atributo especifica una agrupación secuencial de glifos y palabras en cadenas. Por ejemplo, las etiquetas y las palabras tienen un orden diferente en el HTML convertido y se desea que coincidan. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Obtiene o establece la ruta al directorio donde deben guardarse las imágenes si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos de imagen (si los hay) se guardarán junto con los demás archivos vinculados al HTML. No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Obtiene o establece la ruta al directorio donde deben guardarse solo las imágenes SVG si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos SVG (si los hay) se guardarán junto con los demás archivos de imagen (cerca del archivo de salida) o en una carpeta especial para imágenes (si se especifica en la opción SpecialImagesFolderIfAny). No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'true'), este atributo define si se debe crear un archivo CSS separado para cada página HTML de resultado. Por defecto este atributo es false, por lo que se crea un único CSS común grande para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un solo CSS grande, porque en el primer caso las clases CSS se duplican en varios archivos CSS para cada página. Por lo tanto, esta configuración es menos recomendable y solo debe usarse cuando le interese procesar cada página HTML de forma independiente en el futuro, y por consiguiente el tamaño del CSS de cada página individual sea el factor más crítico. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Establece la bandera que indica si cada página del documento fuente se convertirá en su propio documento HTML de destino, es decir, si el HTML resultante se dividirá en varias páginas HTML. |
| [setTitle](#setTitle-java.lang.String-) | Obtiene o establece el título de la página HTML. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | El propio PDF no contiene marcadores de subrayado para los textos. Se emula con una línea situada bajo el texto. Esta opción permite al conversor intentar adivinar que una u otra línea es el subrayado del texto y colocar esta información en CSS en lugar de dibujar el subrayado gráficamente. |
| [setUseZOrder](#setUseZOrder-boolean-) | Si el atributo UseZORder se establece en true, los gráficos y el texto se añaden al documento HTML resultante de acuerdo con el orden Z del documento PDF original. Si este atributo es false, todos los gráficos se colocan en una sola capa, lo que puede causar efectos innecesarios en los objetos superpuestos. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Inicializa una nueva instancia de la clase HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Inicializa una nueva instancia de la clase {@code HtmlSaveOptions}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixedLayout |  | valor booleano |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Inicializa una nueva instancia de la clase HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Inicializa una nueva instancia de la clase HtmlSaveOptions.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada no se dividirá en diferentes páginas HTML, sino que se colocará en un único archivo HTML resultante grande. Pero cada página PDF de origen se representará con su propia área rectangular en HTML (si es necesario, esas áreas pueden estar delimitadas para mostrar los bordes del papel de la página con el atributo especial 'PageBorderIfAny'). Este parámetro define el ancho del margen que se dejará obligatoriamente alrededor de esas áreas HTML de salida que representan las páginas del documento PDF de origen. En esencia define el intervalo garantizado entre las representaciones HTML de las páginas "paper" del PDF en este modo de conversión.

**Returns:**
valor int @deprecated AdditionalMarginWidthInPoints está obsoleto, por favor use PageMarginIfAny en su lugar.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Este parámetro define las medidas de antialiasing requeridas durante la conversión de imágenes de fondo compuestas de PDF a HTML.

**Returns:**
Elemento AntialiasingProcessingType @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Returns:**
valor int

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

Cuando el conversor PDFtoHTML genera los CSS resultantes, los nombres de clases CSS (algo como ".stl_01 {}" ... ".stl_NN {}") se generan y se utilizan en el CSS resultante. Esta propiedad permite establecer forzadamente un prefijo para los nombres de clase. Por ejemplo, si desea que todos los nombres de clase comiencen con 'my_prefix_' (es decir, algo como 'my_prefix_1' ... 'my_prefix_NNN'), simplemente asigne 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanece sin tocar (es decir, se deja null como valor), el conversor generará los nombres de clase por sí mismo (será algo como ".stl_01 {}" ... ".stl_NN {}").

**Returns:**
valor String

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión de PDF a HTML para el manejo del guardado de los CSS relacionados con el documento HTML creado en su totalidad o con sus páginas (si se generan varias páginas HTML). Si desea manejar el archivo CSS de una manera específica, simplemente cree el método correspondiente y asigne el delegado creado a partir de él a esta propiedad.

**Returns:**
Instancia CssSavingStrategy

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

El resultado de la conversión puede contener una o varias páginas HTML. Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implementa el procesamiento de una página HTML (para ser precisos, markup-HTML, sin archivos vinculados externos, si los hay) que se creó durante la conversión. En tal caso, el procesamiento (como guardar el HTML de la página en un flujo o en disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar la página HTML deben llevarse a cabo en el código del método suministrado, porque guardar el resultado en el código del convertidor no se utilizará. Si el procesamiento para este u otro caso, por alguna razón, debe ser realizado por el propio código del convertidor, no en código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': indicará al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor de la misma manera que si no hubiera ningún código personalizado externo para el procesamiento.

**Returns:**
Instancia HtmlPageMarkupSavingStrategy

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Este controlador puede usarse para manejar eventos de progreso de conversión, por ejemplo, puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas; un ejemplo del código del controlador que muestra el progreso en la consola es: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
Instancia ConversionProgressEventHandler

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de recursos referenciados creados (como imágenes y fuentes) relacionados con los nodos del HTML guardado. Esa estrategia debe procesar los recursos y devolver una cadena que represente la URL deseada del recurso guardado en el HTML generado.

**Returns:**
Instancia ResourceSavingStrategy

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Este campo puede contener un método personalizado que devuelva la URL (o plantilla de URL si la generación multipágina está activada - ver detalles a continuación) del CSS objetivo tal como debe insertarse en el HTML resultante generado. Por ejemplo, si desea que el convertidor coloque una URL específica en lugar del nombre de archivo CSS estándar en el CSS generado, entonces simplemente debe crear y asignar a esta propiedad un método que genere la URL deseada. Si la bandera 'SplitCssIntoPages' está establecida, entonces esta estrategia personalizada (si existe) debe devolver no la URL exacta del CSS sino una cadena de plantilla que (después de sustituir el marcador de posición con el número de página mediante la función String.Format() dentro del convertidor) pueda resolverse en la URL del CSS de esa página. Ejemplos de la cadena de retorno esperada en tal caso son: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
Instancia CssUrlMakingStrategy

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Especifica el nombre de una fuente instalada que se utiliza para sustituir cualquier fuente del documento que no esté incrustada y no esté instalada en el sistema. Si es nulo, se utiliza la fuente de sustitución predeterminada.

**Returns:**
Valor de cadena: Nombre de fuente

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Obtiene el {@code HtmlDocumentTypeInternal}.

**Returns:**
El {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Lista de nombres de fuentes incrustadas en PDF que no se incrustan en HTML.

**Returns:**
matriz de elementos String

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Con esta propiedad puedes definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción.

**Returns:**
matriz de int

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Este atributo especifica texto de párrafo de ancho completo para el modo Flujo, FixedLayout = false

**Returns:**
valor booleano

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Define una regla especial de codificación para ajustar la decodificación de PDF para el documento actual

**Returns:**
Elemento FontEncodingRules @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Define el modo de guardado de fuentes que se utilizará al guardar el PDF en el formato deseado

**Returns:**
Elemento FontSavingModes @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Fuentes de fuentes preguardadas. </p>

**Returns:**
Objeto FontSourceCollection <hr> <p> Las fuentes pueden guardarse preliminarmente para fines de caché y luego pasarse al proceso de conversión Html. Por ejemplo, puede ser útil en escenarios de división de documentos y procesamiento de páginas de documentos en múltiples hilos con un único conjunto de fuentes. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

A veces existen requisitos específicos para la generación de marcado HTML. Este parámetro define los modos de preparación de HTML que pueden usarse durante la conversión de PDF a HTML para cumplir con dichos requisitos específicos.

**Returns:**
Elemento HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Obtiene o establece la resolución para la renderización de imágenes.

**Returns:**
Valor: Resolución

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Establece el modo de posicionamiento de letras en palabras en el HTML resultante

**Returns:**
Elemento LettersPositioningMethods @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Este atributo establece el ancho mínimo de la línea de ruta gráfica. Si el grosor de la línea es inferior a 1px, Adobe Acrobat lo redondea a este valor. Por lo tanto, este atributo puede usarse para emular este comportamiento en los navegadores HTML.

**Returns:**
valor flotante

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Este atributo representa un conjunto de configuraciones usadas para dibujar el borde (si lo hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen. En esencia, se refiere a la visualización de los bordes del papel de la página, no al borde de la página referenciado en la propia página PDF.

**Returns:**
Instancia BorderInfo

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Este atributo representa un conjunto de márgenes de página adicionales (si los hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen.

**Returns:**
Instancia MarginInfo

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Define si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas

**Returns:**
Elemento PartsEmbeddingModes @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

El PDF convertido puede contener imágenes raster. Este parámetro define cómo deben manejarse durante la conversión de PDF a HTML

**Returns:**
Elemento RasterImagesSavingModes @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Obtiene o establece la ruta al directorio donde deben guardarse las imágenes si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos de imagen (si los hay) se guardarán junto con los demás archivos vinculados al HTML. No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente.

**Returns:**
valor String

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Obtiene o establece la ruta al directorio donde deben guardarse solo las imágenes SVG si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos SVG (si los hay) se guardarán junto con los demás archivos de imagen (cerca del archivo de salida) o en una carpeta especial para imágenes (si se especifica en la opción SpecialImagesFolderIfAny). No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public final String getTitle()
```

Obtiene o establece el título de la página HTML.

**Returns:**
valor String

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Obtiene la bandera que indica si los gráficos SVG encontrados (si los hay) se comprimirán (en zip) al formato SVGZ durante el guardado. Valor: {@code HtmlDocumentType}.

**Returns:**
valor booleano

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Si el atributo ConvertMarkedContentToLayers está establecido en true, entonces todos los elementos dentro de un contenido marcado de PDF (capa) se colocarán en un div HTML con el atributo \"data-pdflayer\" que especifica el nombre de la capa. Este nombre de capa se extraerá de las propiedades opcionales del contenido marcado de PDF. Si este atributo es false (por defecto), no se crearán capas a partir del contenido marcado de PDF.

**Returns:**
valor booleano

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Obtiene un valor que indica si el HTML se crea como diseño fijo.

**Returns:**
valor: {@code true} si [fixed layout]; de lo contrario, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto

**Returns:**
valor booleano

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada se colocará en un único archivo HTML de resultado grande. Esta bandera define si el HTML de resultado se generará de manera que el flujo de áreas que representan páginas PDF en el HTML de resultado dependa de la resolución de pantalla del visor. Supongamos que el ancho de pantalla del visor es lo suficientemente grande como para colocar 2 o más páginas una al lado de la otra en dirección horizontal. Si esta bandera se establece en true, entonces se utilizará esta oportunidad (se mostrarán tantas páginas como sea posible en dirección horizontal una al lado de la otra, y luego el siguiente grupo horizontal de páginas se mostrará bajo el primero). De lo contrario, las páginas fluirán de la siguiente manera: la página siguiente siempre se coloca bajo la anterior.

**Returns:**
valor booleano

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Este atributo activa el modo en el que los glifos de texto no se agruparán en palabras y cadenas. Este modo permite mantener la máxima precisión al posicionar los glifos en la página y puede usarse para la conversión de documentos con notas musicales o glifos que deben colocarse por separado unos de otros. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true.

**Returns:**
valor booleano

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Define si en el HTML creado se eliminará el área vacía superior e inferior sin contenido (si la hay).

**Returns:**
valor booleano

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Si el atributo RenderTextAsImage se establece en true, el texto de la fuente se convierte en una imagen en HTML. Puede ser útil para hacer que el texto no sea seleccionable o cuando el texto HTML no se renderiza correctamente.

**Returns:**
valor booleano

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Indica que se guardará la fuente completa, solo admite fuentes True Type. Por defecto SaveFullFont = false y el conversor guarda el subconjunto de la fuente inicial necesario para mostrar el texto del documento.

**Returns:**
valor booleano

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

El PDF puede contener textos que están sombreados por otros elementos (p. ej., por imágenes) pero que pueden seleccionarse al portapapeles en Acrobat Reader (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado para imitar el comportamiento de Acrobat Reader (de lo contrario, esos textos suelen guardarse como ocultos, no disponibles para copiar al portapapeles).

**Returns:**
valor booleano

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

El PDF puede contener textos transparentes que pueden seleccionarse al portapapeles (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado.

**Returns:**
valor booleano

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Este atributo especifica una agrupación secuencial de glifos y palabras en cadenas. Por ejemplo, las etiquetas y las palabras tienen un orden diferente en el HTML convertido y se desea que coincidan. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true.

**Returns:**
valor booleano

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'true'), este atributo define si se debe crear un archivo CSS separado para cada página HTML de resultado. Por defecto este atributo es false, por lo que se crea un único CSS común grande para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un solo CSS grande, porque en el primer caso las clases CSS se duplican en varios archivos CSS para cada página. Por lo tanto, esta configuración es menos recomendable y solo debe usarse cuando le interese procesar cada página HTML de forma independiente en el futuro, y por consiguiente el tamaño del CSS de cada página individual sea el factor más crítico.

**Returns:**
valor booleano

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Obtiene la bandera que indica si cada página del documento fuente se convertirá en su propio documento HTML de destino, es decir, si el HTML de resultado se dividirá en varias páginas HTML.

**Returns:**
valor booleano

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

El propio PDF no contiene marcadores de subrayado para los textos. Se emula con una línea situada bajo el texto. Esta opción permite al conversor intentar adivinar que una u otra línea es el subrayado del texto y colocar esta información en CSS en lugar de dibujar el subrayado gráficamente.

**Returns:**
valor booleano

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Si el atributo UseZORder se establece en true, los gráficos y el texto se añaden al documento HTML resultante de acuerdo con el orden Z del documento PDF original. Si este atributo es false, todos los gráficos se colocan en una sola capa, lo que puede causar efectos innecesarios en los objetos superpuestos.

**Returns:**
valor booleano

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada no se dividirá en diferentes páginas HTML, sino que se colocará en un único archivo HTML resultante grande. Pero cada página PDF de origen se representará con su propia área rectangular en HTML (si es necesario, esas áreas pueden estar delimitadas para mostrar los bordes del papel de la página con el atributo especial 'PageBorderIfAny'). Este parámetro define el ancho del margen que se dejará obligatoriamente alrededor de esas áreas HTML de salida que representan las páginas del documento PDF de origen. En esencia define el intervalo garantizado entre las representaciones HTML de las páginas "paper" del PDF en este modo de conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int @deprecated AdditionalMarginWidthInPoints está obsoleto, por favor use PageMarginIfAny en su lugar. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Este parámetro define las medidas de antialiasing requeridas durante la conversión de imágenes de fondo compuestas de PDF a HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| antialiasingProcessing |  | Elemento AntialiasingProcessingType @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Establece la bandera que indica si los gráficos SVG encontrados (si los hay) se comprimirán (en zip) al formato SVGZ durante el guardado Valor: El {@code HtmlDocumentType}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Si el atributo ConvertMarkedContentToLayers está establecido en true, entonces todos los elementos dentro de un contenido marcado de PDF (capa) se colocarán en un div HTML con el atributo \"data-pdflayer\" que especifica el nombre de la capa. Este nombre de capa se extraerá de las propiedades opcionales del contenido marcado de PDF. Si este atributo es false (por defecto), no se crearán capas a partir del contenido marcado de PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
Cuando el conversor PDFtoHTML genera los CSS resultantes, los nombres de clases CSS (algo como ".stl_01 {}" ... ".stl_NN {}") se generan y se utilizan en el CSS resultante. Esta propiedad permite establecer forzadamente un prefijo para los nombres de clase. Por ejemplo, si desea que todos los nombres de clase comiencen con 'my_prefix_' (es decir, algo como 'my_prefix_1' ... 'my_prefix_NNN'), simplemente asigne 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanece sin tocar (es decir, se deja null como valor), el conversor generará los nombres de clase por sí mismo (será algo como ".stl_01 {}" ... ".stl_NN {}").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión de PDF a HTML para el manejo del guardado de los CSS relacionados con el documento HTML creado en su totalidad o con sus páginas (si se generan varias páginas HTML). Si desea manejar el archivo CSS de una manera específica, simplemente cree el método correspondiente y asigne el delegado creado a partir de él a esta propiedad.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
El resultado de la conversión puede contener una o varias páginas HTML Puedes asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de una página HTML (para ser precisos - markup-HTML, sin archivos vinculados externos si los hay) que se creó durante la conversión.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Este manejador puede usarse para manejar eventos de progreso de conversión, p. ej.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de recursos referenciados creados (como imágenes y fuentes) relacionados con los nodos del HTML guardado.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Este campo puede contener un método personalizado que devuelva la URL (o plantilla de URL si la generación multipágina está activada - ver detalles a continuación) del CSS de referencia tal como debe insertarse en el HTML resultante generado.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Especifica el nombre de una fuente instalada que se utiliza para sustituir cualquier fuente del documento que no esté incrustada y no esté instalada en el sistema. Si es nulo, se utiliza la fuente de sustitución predeterminada.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Establece el {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Lista de nombres de fuentes incrustadas en PDF que no se incrustan en HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Con esta propiedad puedes definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Establece un valor que indica si ese HTML se crea como diseño fijo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | : {@code true} si [fixed layout]; de lo contrario, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Este atributo especifica texto de párrafo de ancho completo para el modo Flujo, FixedLayout = false

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Define una regla especial de codificación para ajustar la decodificación de PDF para el documento actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontEncodingStrategy |  | Elemento FontEncodingRules @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Define el modo de guardado de fuentes que se utilizará al guardar el PDF en el formato deseado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSavingMode |  | Elemento FontSavingModes @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

A veces existen requisitos específicos para la generación de marcado HTML. Este parámetro define los modos de preparación de HTML que pueden usarse durante la conversión de PDF a HTML para cumplir con dichos requisitos específicos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | Elemento HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Obtiene o establece la resolución para la renderización de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor: Resolución |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Establece el modo de posicionamiento de letras en palabras en el HTML resultante

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Este atributo establece el ancho mínimo de la línea de ruta gráfica. Si el grosor de la línea es inferior a 1px, Adobe Acrobat lo redondea a este valor. Por lo tanto, este atributo puede usarse para emular este comportamiento en los navegadores HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Este atributo representa el conjunto de configuraciones usadas para dibujar un borde (si lo hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Este atributo representa un conjunto de márgenes de página adicionales (si los hay) en el documento HTML resultante alrededor del área que representa la página PDF de origen.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Si el atributo 'SplitOnPages=false', entonces todo el HTML que representa todas las páginas PDF de entrada se colocará en un único archivo HTML de resultado grande. Esta bandera define si el HTML de resultado se generará de manera que el flujo de áreas que representan páginas PDF en el HTML de resultado dependa de la resolución de pantalla del visor. Supongamos que el ancho de pantalla del visor es lo suficientemente grande como para colocar 2 o más páginas una al lado de la otra en dirección horizontal. Si esta bandera se establece en true, entonces se utilizará esta oportunidad (se mostrarán tantas páginas como sea posible en dirección horizontal una al lado de la otra, y luego el siguiente grupo horizontal de páginas se mostrará bajo el primero). De lo contrario, las páginas fluirán de la siguiente manera: la página siguiente siempre se coloca bajo la anterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | valor booleano |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Define si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| partsEmbeddingMode |  | Elemento PartsEmbeddingModes @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Este atributo activa el modo en el que los glifos de texto no se agruparán en palabras y cadenas. Este modo permite mantener la máxima precisión al posicionar los glifos en la página y puede usarse para la conversión de documentos con notas musicales o glifos que deben colocarse por separado unos de otros. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

El PDF convertido puede contener imágenes raster. Este parámetro define cómo deben manejarse durante la conversión de PDF a HTML

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImagesSavingMode |  | Elemento RasterImagesSavingModes @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Define si en el HTML creado se eliminará el área vacía superior e inferior sin contenido (si la hay).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | valor booleano |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Si el atributo RenderTextAsImage se establece en true, el texto de la fuente se convierte en una imagen en HTML. Puede ser útil para hacer que el texto no sea seleccionable o cuando el texto HTML no se renderiza correctamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Indica que se guardará la fuente completa, solo admite fuentes True Type. Por defecto SaveFullFont = false y el conversor guarda el subconjunto de la fuente inicial necesario para mostrar el texto del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

El PDF puede contener textos que están sombreados por otros elementos (p. ej., por imágenes) pero que pueden seleccionarse al portapapeles en Acrobat Reader (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado para imitar el comportamiento de Acrobat Reader (de lo contrario, esos textos suelen guardarse como ocultos, no disponibles para copiar al portapapeles).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | valor booleano |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

El PDF puede contener textos transparentes que pueden seleccionarse al portapapeles (normalmente ocurre cuando el documento contiene imágenes y textos OCR extraídos de ellas). Esta configuración indica al conversor si debemos guardar dichos textos como textos transparentes seleccionables en el HTML de resultado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| saveTransparentTexts |  | valor booleano |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Este atributo especifica una agrupación secuencial de glifos y palabras en cadenas. Por ejemplo, las etiquetas y las palabras tienen un orden diferente en el HTML convertido y se desea que coincidan. Este parámetro se aplicará al documento solo cuando el valor del atributo FixedLayout sea true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Obtiene o establece la ruta al directorio donde deben guardarse las imágenes si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos de imagen (si los hay) se guardarán junto con los demás archivos vinculados al HTML. No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Obtiene o establece la ruta al directorio donde deben guardarse solo las imágenes SVG si se encuentran durante el guardado del documento como HTML. Si el parámetro está vacío o es nulo, los archivos SVG (si los hay) se guardarán junto con los demás archivos de imagen (cerca del archivo de salida) o en una carpeta especial para imágenes (si se especifica en la opción SpecialImagesFolderIfAny). No afecta nada si la propiedad CustomImageSavingStrategy se utilizó con éxito para procesar el archivo de imagen correspondiente.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'true'), este atributo define si se debe crear un archivo CSS separado para cada página HTML de resultado. Por defecto este atributo es false, por lo que se crea un único CSS común grande para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un solo CSS grande, porque en el primer caso las clases CSS se duplican en varios archivos CSS para cada página. Por lo tanto, esta configuración es menos recomendable y solo debe usarse cuando le interese procesar cada página HTML de forma independiente en el futuro, y por consiguiente el tamaño del CSS de cada página individual sea el factor más crítico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Establece la bandera que indica si cada página del documento fuente se convertirá en su propio documento HTML de destino, es decir, si el HTML resultante se dividirá en varias páginas HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTitle {#setTitle-java.lang.String-}
Obtiene o establece el título de la página HTML.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

El propio PDF no contiene marcadores de subrayado para los textos. Se emula con una línea situada bajo el texto. Esta opción permite al conversor intentar adivinar que una u otra línea es el subrayado del texto y colocar esta información en CSS en lugar de dibujar el subrayado gráficamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | valor booleano |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Si el atributo UseZORder se establece en true, los gráficos y el texto se añaden al documento HTML resultante de acuerdo con el orden Z del documento PDF original. Si este atributo es false, todos los gráficos se colocan en una sola capa, lo que puede causar efectos innecesarios en los objetos superpuestos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
