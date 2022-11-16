---
title: HtmlSaveOptions
second_title: Aspose.PDF для справки по Java API
description: Сохранить параметры для экспорта в формат Html
type: docs
weight: 161
url: /ru/java/com.aspose.pdf/htmlsaveoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**Все реализованные интерфейсы:**
[com.aspose.pdf.IPageSetOptions](../../com.aspose.pdf/ipagesetoptions), [com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions, IPipelineOptions
```

Сохранить параметры для экспорта в формат Html
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | Инициализирует новый экземпляр класса HtmlSaveOptions. |
| [HtmlSaveOptions(int documentType)](#HtmlSaveOptions-int-) | Инициализирует новый экземпляр класса HtmlSaveOptions. |
| [HtmlSaveOptions(boolean fixedLayout)](#HtmlSaveOptions-boolean-) | Инициализирует новый экземпляр класса HtmlSaveOptions. |
| [HtmlSaveOptions(int documentType, boolean fixedLayout)](#HtmlSaveOptions-int-boolean-) | Инициализирует новый экземпляр класса HtmlSaveOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionalMarginWidthInPoints()](#getAdditionalMarginWidthInPoints--) | Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, не будет разделен на разные HTML-страницы, а будет помещен в один большой результирующий HTML-файл. |
| [getAntialiasingProcessing()](#getAntialiasingProcessing--) | Этот параметр определяет необходимые меры сглаживания при преобразовании составных фоновых изображений из PDF в HTML. |
| [getBatchSize()](#getBatchSize--) | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [getClass()](#getClass--) |  |
| [getCompressSvgGraphicsIfAny()](#getCompressSvgGraphicsIfAny--) | Получает флаг, указывающий, будет ли найденная графика SVG (если есть) сжата (заархивирована) в формат SVGZ во время сохранения. |
| [getConvertMarkedContentToLayers()](#getConvertMarkedContentToLayers--) | Если для атрибута ConvertMarkedContentToLayers задано значение true, то все элементы внутри помеченного PDF-содержимого (слоя) будут помещены в элемент div HTML с атрибутом «data-pdflayer», указывающим имя слоя. |
| [getCssClassNamesPrefix()](#getCssClassNamesPrefix--) | Когда конвертер PDFtoHTML генерирует результирующие CSS, имена классов CSS (что-то вроде «.stl\ _01\{\}" ... ".stl\ _NN\{\}) генерируются и используются в результирующем CSS. |
| [getCustomCssSavingStrategy()](#getCustomCssSavingStrategy--) | Это поле может содержать стратегию сохранения, которая должна использоваться (если присутствует) во время преобразования Pdf в Html для управления сохранением CSS, связанных с созданным HTML-документом в целом или с его страницами (если создается несколько HTML-страниц). Если вы хотите обрабатывать файл CSS каким-то особым образом, просто создайте соответствующий метод и назначьте делегата, созданного из него, этому свойству. |
| [getCustomHtmlSavingStrategy()](#getCustomHtmlSavingStrategy--) | Результат конвертации может содержать одну или несколько HTML-страниц. Этому свойству можно присвоить делегат, созданный из пользовательского метода, реализующего обработку одной HTML-страницы (точнее - разметки-HTML, без внешних связанных файлов, если таковые имеются), которая была создана во время преобразование. |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли: |
| [getCustomResourceSavingStrategy()](#getCustomResourceSavingStrategy--) | Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов ресурсов (например, изображений и шрифтов), связанных с узлами сохраненного HTML. |
| [getCustomStrategyOfCssUrlCreation()](#getCustomStrategyOfCssUrlCreation--) | Это поле может содержать пользовательский метод, который возвращает URL-адрес (или шаблон URL-адреса, если включена многостраничная генерация — см. подробности ниже) предметного CSS, поскольку он должен быть помещен в сгенерированный результирующий HTML-код. |
| [getDefaultFontName()](#getDefaultFontName--) | Указывает имя установленного шрифта, который используется для замены любого шрифта документа, который не встроен и не установлен в системе. |
| [getDocumentType()](#getDocumentType--) | Получает HtmlDocumentTypeInternal . |
| [getExcludeFontNameList()](#getExcludeFontNameList--) | Список имен встроенных шрифтов PDF, которые не могут быть встроены в HTML. |
| [getExplicitListOfSavedPages()](#getExplicitListOfSavedPages--) | С помощью этого свойства вы можете явно указать, какие страницы документа должны быть преобразованы. |
| [getFixedLayout()](#getFixedLayout--) | Получает значение, указывающее, создан ли этот HTML как фиксированный макет. |
| [getFontEncodingStrategy()](#getFontEncodingStrategy--) | Определяет специальное правило кодирования для настройки декодирования PDF для текущего документа. |
| [getFontSavingMode()](#getFontSavingMode--) | Определяет режим сохранения шрифта, который будет использоваться при сохранении PDF в желаемом формате. |
| [getFontSources()](#getFontSources--) | Источники предварительно сохраненных шрифтов. |
| [getHtmlMarkupGenerationMode()](#getHtmlMarkupGenerationMode--) | Иногда предъявляются особые требования к генерации HTML-разметки. |
| [getImageResolution()](#getImageResolution--) | Получает или задает разрешение для рендеринга изображения. |
| [getLettersPositioningMethod()](#getLettersPositioningMethod--) | Задает способ расположения букв в словах в результирующем HTML |
| [getMinimalLineWidth()](#getMinimalLineWidth--) | Этот атрибут задает минимальную ширину линии графического контура. |
| [getPageBorderIfAny()](#getPageBorderIfAny--) | Этот атрибут представляет собой набор настроек, используемых для рисования границы (если есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. |
| [getPageMarginIfAny()](#getPageMarginIfAny--) | Этот атрибут представляет набор дополнительных полей страницы (если они есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. |
| [getPartsEmbeddingMode()](#getPartsEmbeddingMode--) | Он определяет, будут ли ссылочные файлы (HTML, шрифты, изображения, CSS) встроены в основной файл HTML или будут сгенерированы как отдельные двоичные объекты. |
| [getPreventGlyphsGrouping()](#getPreventGlyphsGrouping--) | Этот атрибут включает режим, при котором текстовые глифы не будут группироваться в слова и строки. Этот режим позволяет сохранить максимальную точность при позиционировании глифов на странице и может быть использован для конвертации документов с нотами или глифами, которые необходимо размещать отдельно друг от друга. Другой. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [getRasterImagesSavingMode()](#getRasterImagesSavingMode--) | Преобразованный PDF может содержать растровые изображения. Этот параметр определяет, как они должны обрабатываться при преобразовании PDF в HTML. |
| [getSaveFormat()](#getSaveFormat--) | Формат сохранения данных. |
| [getSimpleTextboxModeGrouping()](#getSimpleTextboxModeGrouping--) | Этот атрибут указывает последовательную группировку глифов и слов в строки. Например, теги и слова имеют разный порядок в преобразованном HTML, и вы хотите, чтобы они совпадали. |
| [getSpecialFolderForAllImages()](#getSpecialFolderForAllImages--) | Получает или задает путь к каталогу, в который должны быть сохранены любые изображения, если они встречаются при сохранении документа в формате HTML. |
| [getSpecialFolderForSvgImages()](#getSpecialFolderForSvgImages--) | Получает или задает путь к каталогу, в который должны быть сохранены только SVG-изображения, если они встречаются при сохранении документа в формате HTML. |
| [getSplitCssIntoPages()](#getSplitCssIntoPages--) | Когда выбран многостраничный режим (т.е. 'SplitIntoPages' имеет значение 'true'), то этот атрибут определяет, должен ли быть создан отдельный CSS-файл для каждой результирующей HTML-страницы. |
| [getSplitIntoPages()](#getSplitIntoPages--) | Получает флаг, указывающий, будет ли каждая страница исходного документа преобразована в свой собственный целевой HTML-документ, т.е. будет ли результирующий HTML разбит на несколько HTML-страниц. |
| [getUseZOrder()](#getUseZOrder--) | Если для атрибута UseZORder установлено значение true, графика и текст добавляются в результирующий HTML-документ в соответствии с Z-порядком в исходном PDF-документе. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [isPagesFlowTypeDependsOnViewersScreenSize()](#isPagesFlowTypeDependsOnViewersScreenSize--) | Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, будет помещен в один большой результирующий HTML-файл. |
| [isRemoveEmptyAreasOnTopAndBottom()](#isRemoveEmptyAreasOnTopAndBottom--) | Определяет, будут ли в созданном HTML удаляться верхняя и нижняя пустые области без содержимого (если оно есть). |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Если для атрибута RenderTextAsImage задано значение true, текст из источника становится изображением в формате HTML. |
| [isSaveFullFont()](#isSaveFullFont--) | Указывает, что будет сохранен полный шрифт, поддерживаются только шрифты True Type. |
| [isSaveShadowedTextsAsTransparentTexts()](#isSaveShadowedTextsAsTransparentTexts--) | Pdf может содержать тексты, которые затенены другими элементами (например, изображениями), но могут быть выделены в буфер обмена в Acrobat Reader (обычно это происходит, когда документ содержит изображения и извлеченные из них тексты, подвергнутые распознаванию). |
| [isSaveTransparentTexts()](#isSaveTransparentTexts--) | Pdf может содержать прозрачные тексты, которые можно выделить в буфер обмена (обычно это происходит, когда документ содержит изображения и извлеченные из него OCR-тексты). |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss()](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | Сам PDF не содержит маркеров подчеркивания для текстов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdditionalMarginWidthInPoints(int value)](#setAdditionalMarginWidthInPoints-int-) | Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, не будет разделен на разные HTML-страницы, а будет помещен в один большой результирующий HTML-файл. |
| [setAntialiasingProcessing(int antialiasingProcessing)](#setAntialiasingProcessing-int-) | Этот параметр определяет необходимые меры сглаживания при преобразовании составных фоновых изображений из PDF в HTML. |
| [setBatchSize(int value)](#setBatchSize-int-) | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [setCompressSvgGraphicsIfAny(boolean value)](#setCompressSvgGraphicsIfAny-boolean-) | Устанавливает флаг, указывающий, будет ли найденная графика SVG (если есть) сжата (заархивирована) в формат SVGZ во время сохранения |
| [setConvertMarkedContentToLayers(boolean value)](#setConvertMarkedContentToLayers-boolean-) | Если для атрибута ConvertMarkedContentToLayers задано значение true, то все элементы внутри помеченного PDF-содержимого (слоя) будут помещены в элемент div HTML с атрибутом «data-pdflayer», указывающим имя слоя. |
| [setCssClassNamesPrefix(String cssClassNamesPrefix)](#setCssClassNamesPrefix-java.lang.String-) | Когда конвертер PDFtoHTML генерирует результирующие CSS, имена классов CSS (что-то вроде «.stl\ _01\{\}" ... ".stl\ _NN\{\}) генерируются и используются в результирующем CSS. |
| [setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy)](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Это поле может содержать стратегию сохранения, которая должна использоваться (если присутствует) во время преобразования Pdf в Html для управления сохранением CSS, связанных с созданным HTML-документом в целом или с его страницами (если создается несколько HTML-страниц). Если вы хотите обрабатывать файл CSS каким-то особым образом, просто создайте соответствующий метод и назначьте делегата, созданного из него, этому свойству. |
| [setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy)](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Результат конвертации может содержать одну или несколько HTML-страниц. Этому свойству можно присвоить делегат, созданный из пользовательского метода, реализующего обработку одной HTML-страницы (точнее - разметки-HTML, без внешних связанных файлов, если таковые имеются), которая была создана во время преобразование. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли: |
| [setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy)](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов ресурсов (например, изображений и шрифтов), связанных с узлами сохраненного HTML. |
| [setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation)](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Это поле может содержать пользовательский метод, который возвращает URL-адрес (или шаблон URL-адреса, если включена многостраничная генерация — см. подробности ниже) предметного CSS, поскольку он должен быть помещен в сгенерированный результирующий HTML-код. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Указывает имя установленного шрифта, который используется для замены любого шрифта документа, который не встроен и не установлен в системе. |
| [setDocumentType(int value)](#setDocumentType-int-) | Задает HtmlDocumentType . |
| [setExcludeFontNameList(String[] excludeFontNameList)](#setExcludeFontNameList-java.lang.String---) | Список имен встроенных шрифтов PDF, которые не могут быть встроены в HTML. |
| [setExplicitListOfSavedPages(int[] value)](#setExplicitListOfSavedPages-int---) | С помощью этого свойства вы можете явно указать, какие страницы документа должны быть преобразованы. |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [setFixedLayout(boolean value)](#setFixedLayout-boolean-) | Задает значение, указывающее, создан ли этот HTML как фиксированный макет. |
| [setFontEncodingStrategy(byte fontEncodingStrategy)](#setFontEncodingStrategy-byte-) | Определяет специальное правило кодирования для настройки декодирования PDF для текущего документа. |
| [setFontSavingMode(int fontSavingMode)](#setFontSavingMode-int-) | Определяет режим сохранения шрифта, который будет использоваться при сохранении PDF в желаемом формате. |
| [setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)](#setHtmlMarkupGenerationMode-int-) | Иногда предъявляются особые требования к генерации HTML-разметки. |
| [setImageResolution(int value)](#setImageResolution-int-) | Получает или задает разрешение для рендеринга изображения. |
| [setLettersPositioningMethod(int lettersPositioningMethod)](#setLettersPositioningMethod-int-) | Задает способ расположения букв в словах в результирующем HTML |
| [setMinimalLineWidth(float value)](#setMinimalLineWidth-float-) | Этот атрибут задает минимальную ширину линии графического контура. |
| [setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny)](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Этот атрибут представляет собой набор настроек, используемых для рисования границы (если есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. |
| [setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny)](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Этот атрибут представляет набор дополнительных полей страницы (если они есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. |
| [setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, будет помещен в один большой результирующий HTML-файл. |
| [setPartsEmbeddingMode(int partsEmbeddingMode)](#setPartsEmbeddingMode-int-) | Он определяет, будут ли ссылочные файлы (HTML, шрифты, изображения, CSS) встроены в основной файл HTML или будут сгенерированы как отдельные двоичные объекты. |
| [setPreventGlyphsGrouping(boolean value)](#setPreventGlyphsGrouping-boolean-) | Этот атрибут включает режим, при котором текстовые глифы не будут группироваться в слова и строки. Этот режим позволяет сохранить максимальную точность при позиционировании глифов на странице и может быть использован для конвертации документов с нотами или глифами, которые необходимо размещать отдельно друг от друга. Другой. |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) |  Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе |
| [setRasterImagesSavingMode(int rasterImagesSavingMode)](#setRasterImagesSavingMode-int-) | Преобразованный PDF может содержать растровые изображения. Этот параметр определяет, как они должны обрабатываться при преобразовании PDF в HTML. |
| [setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Определяет, будут ли в созданном HTML удаляться верхняя и нижняя пустые области без содержимого (если оно есть). |
| [setRenderTextAsImage(boolean value)](#setRenderTextAsImage-boolean-) | Если для атрибута RenderTextAsImage задано значение true, текст из источника становится изображением в формате HTML. |
| [setSaveFullFont(boolean saveFullFont)](#setSaveFullFont-boolean-) | Указывает, что будет сохранен полный шрифт, поддерживаются только шрифты True Type. |
| [setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf может содержать тексты, которые затенены другими элементами (например, изображениями), но могут быть выделены в буфер обмена в Acrobat Reader (обычно это происходит, когда документ содержит изображения и извлеченные из них тексты, подвергнутые распознаванию). |
| [setSaveTransparentTexts(boolean saveTransparentTexts)](#setSaveTransparentTexts-boolean-) | Pdf может содержать прозрачные тексты, которые можно выделить в буфер обмена (обычно это происходит, когда документ содержит изображения и извлеченные из него OCR-тексты). |
| [setSimpleTextboxModeGrouping(boolean value)](#setSimpleTextboxModeGrouping-boolean-) | Этот атрибут указывает последовательную группировку глифов и слов в строки. Например, теги и слова имеют разный порядок в преобразованном HTML, и вы хотите, чтобы они совпадали. |
| [setSpecialFolderForAllImages(String specialFolderForAllImages)](#setSpecialFolderForAllImages-java.lang.String-) | Получает или задает путь к каталогу, в который должны быть сохранены любые изображения, если они встречаются при сохранении документа в формате HTML. |
| [setSpecialFolderForSvgImages(String specialFolderForSvgImages)](#setSpecialFolderForSvgImages-java.lang.String-) | Получает или задает путь к каталогу, в который должны быть сохранены только SVG-изображения, если они встречаются при сохранении документа в формате HTML. |
| [setSplitCssIntoPages(boolean value)](#setSplitCssIntoPages-boolean-) | Когда выбран многостраничный режим (т.е. 'SplitIntoPages' имеет значение 'true'), то этот атрибут определяет, должен ли быть создан отдельный CSS-файл для каждой результирующей HTML-страницы. |
| [setSplitIntoPages(boolean value)](#setSplitIntoPages-boolean-) | Устанавливает флаг, указывающий, будет ли каждая страница исходного документа преобразована в свой собственный целевой HTML-документ, т.е. будет ли результирующий HTML разбит на несколько HTML-страниц. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | Сам PDF не содержит маркеров подчеркивания для текстов. |
| [setUseZOrder(boolean value)](#setUseZOrder-boolean-) | Если для атрибута UseZORder установлено значение true, графика и текст добавляются в результирующий HTML-документ в соответствии с Z-порядком в исходном PDF-документе. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


Инициализирует новый экземпляр класса HtmlSaveOptions.

### HtmlSaveOptions(int documentType) {#HtmlSaveOptions-int-}
```
public HtmlSaveOptions(int documentType)
```


Инициализирует новый экземпляр класса HtmlSaveOptions.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentType | int | HtmlDocumentTypeInternal . |

### HtmlSaveOptions(boolean fixedLayout) {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```


Инициализирует новый экземпляр класса HtmlSaveOptions.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fixedLayout | boolean | логическое значение |

### HtmlSaveOptions(int documentType, boolean fixedLayout) {#HtmlSaveOptions-int-boolean-}
```
public HtmlSaveOptions(int documentType, boolean fixedLayout)
```


Инициализирует новый экземпляр класса HtmlSaveOptions.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentType | int | HtmlDocumentTypeInternal . |
| fixedLayout | boolean | если установлено значение true, HTML создается как фиксированный макет. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getAdditionalMarginWidthInPoints() {#getAdditionalMarginWidthInPoints--}
```
public int getAdditionalMarginWidthInPoints()
```


Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, не будет разделен на разные HTML-страницы, а будет помещен в один большой результирующий HTML-файл. Но каждая исходная PDF-страница будет представлена своей собственной прямоугольной областью в HTML (при необходимости эти области могут быть ограничены для отображения краев бумаги страницы с помощью специального атрибута «PageBorderIfAny». Этот параметр определяет ширину поля, которое будет принудительно оставлено вокруг этого выходного HTML-кода. -области, которые представляют собой страницы исходного PDF-документа. По сути, он определяет гарантированный интервал между HTML-представлениями "бумажных" страниц PDF, такой режим преобразования.

**Возвращает:**
интервал - целочисленное значение
### getAntialiasingProcessing() {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```


Этот параметр определяет необходимые меры сглаживания при преобразовании составных фоновых изображений из PDF в HTML.

**Возвращает:**
int — элемент AntialiasingProcessingType
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов.

**Возвращает:**
инт
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCompressSvgGraphicsIfAny() {#getCompressSvgGraphicsIfAny--}
```
public boolean getCompressSvgGraphicsIfAny()
```


Получает флаг, указывающий, будет ли найденная графика SVG (если есть) сжата (заархивирована) в формат SVGZ во время сохранения.

Значение: HtmlDocumentType.

**Возвращает:**
boolean - логическое значение
### getConvertMarkedContentToLayers() {#getConvertMarkedContentToLayers--}
```
public boolean getConvertMarkedContentToLayers()
```


Если для атрибута ConvertMarkedContentToLayers задано значение true, то все элементы внутри помеченного PDF-содержимого (слоя) будут помещены в элемент div HTML с атрибутом «data-pdflayer», указывающим имя слоя. Это имя слоя будет извлечено из необязательных свойств помеченного содержимого PDF. Если этот атрибут имеет значение false (по умолчанию), то никакие слои не будут созданы из содержимого, помеченного PDF.

**Возвращает:**
boolean - логическое значение
### getCssClassNamesPrefix() {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```


Когда конвертер PDFtoHTML генерирует результирующие CSS, имена классов CSS (что-то вроде «.stl\ _01\{\}" ... ".stl\ _NN\{\}) генерируются и используются в результирующем CSS. Это свойство позволяет принудительно установить префикс имени класса. Например, если Вы хотите, чтобы все имена классов начинались с 'my\_префикс\_' (т.е. были чем-то вроде 'мой\_префикс\_1'...'мой\_префикс\_NNN' ), затем просто назначьте 'мой\_префикс\_' к этому свойству перед преобразованием. Если это свойство останется нетронутым (т.е. в качестве значения будет оставлено значение null ), то конвертер сам сгенерирует имена классов (это будет что-то вроде ".stl\ _01\{\}" ... ".stl\ _NN\{\}")

**Возвращает:**
java.lang.String — строковое значение
### getCustomCssSavingStrategy() {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```


Это поле может содержать стратегию сохранения, которая должна использоваться (если присутствует) во время преобразования Pdf в Html для управления сохранением CSS, связанных с созданным HTML-документом в целом или с его страницами (если создается несколько HTML-страниц). Если вы хотите обрабатывать файл CSS каким-то особым образом, просто создайте соответствующий метод и назначьте делегата, созданного из него, этому свойству.

**Возвращает:**
[CssSavingStrategy](../../com.aspose.pdf/csssavingstrategy) - Экземпляр CssSavingStrategy
### getCustomHtmlSavingStrategy() {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```


Результат конвертации может содержать одну или несколько HTML-страниц. Этому свойству можно присвоить делегат, созданный из пользовательского метода, реализующего обработку одной HTML-страницы (точнее - разметки-HTML, без внешних связанных файлов, если таковые имеются), которая была создана во время преобразование. В этом случае обработка (например, сохранение HTML-кода страницы в потоке или на диске) может выполняться в этом пользовательском коде. В таком случае все необходимые действия по сохранению HTML-страницы должны быть выполнены в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка в том или ином случае по каким-либо причинам должна производиться самим кодом конвертера, а не в пользовательском коде, пожалуйста, установите в пользовательском коде флаг CustomProcessingCancelled переменной параметра htmlSavingInfo: это будет сигнализировать конвертеру, что все необходимые шаги для обработка этого ресурса должна производиться в самом конвертере так же, как если бы не было никакого внешнего пользовательского кода для обработки.

**Возвращает:**
[HtmlPageMarkupSavingStrategy](../../com.aspose.pdf/htmlpagemarkupsavingstrategy) Экземпляр HtmlPageMarkupSavingStrategy
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли:

--------------------

```
public static void ConvertWithShowingProgress()
     {
         (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
         Document doc = new Document("Booklet.pdf");
         HtmlSaveOptions saveOptions = new HtmlSaveOptions();
         saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
        public void invoke(
    	    UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
    	showProgressOnConsole(eventInfo);
        }
    };
         doc.save("Booklet.doc", saveOptions);
     }
     public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
     {
         switch (eventInfo.EventType)
         {
             case HtmlSaveOptions.ProgressEventType.TotalProgress:
                 System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
                 break;
             case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
        	 System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
        	 System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
        	 System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             default:
                 break;
         }
      }
```

**Возвращает:**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) - Экземпляр ConversionProgressEventHandler
### getCustomResourceSavingStrategy() {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```


Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов ресурсов (например, изображений и шрифтов), связанных с узлами сохраненного HTML. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URL-адрес сохраненного ресурса в сгенерированном HTML.

**Возвращает:**
[ResourceSavingStrategy](../../com.aspose.pdf/resourcesavingstrategy) - Экземпляр ResourceSavingStrategy
### getCustomStrategyOfCssUrlCreation() {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```


Это поле может содержать пользовательский метод, который возвращает URL-адрес (или шаблон URL-адреса, если включена многостраничная генерация — см. подробности ниже) предметного CSS, поскольку он должен быть помещен в сгенерированный результирующий HTML-код. Например, если вы хотите, чтобы конвертер поместил какой-то конкретный URL-адрес вместо стандартного имени файла CSS в сгенерированный CSS-файл, вам нужно просто создать и поместить в это свойство метод, который генерирует желаемый URL-адрес. Если установлен флаг «SplitCssIntoPages», то эта пользовательская стратегия (если есть) должна возвращать не точный URL-адрес CSS, а строку шаблона, которая (после замены заполнителя номером страницы с помощью функции String.Format() внутри конвертера) может быть преобразована в URL-адрес для URL той или иной страницы CSS. Примеры ожидаемой возвращаемой строки в таком случае: 'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\ {0\} ' )

**Возвращает:**
[CssUrlMakingStrategy](../../com.aspose.pdf/cssurlmakingstrategy) - Экземпляр CssUrlMakingStrategy
### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


Указывает имя установленного шрифта, который используется для замены любого шрифта документа, который не встроен и не установлен в системе. Если null, то используется шрифт замены по умолчанию.

**Возвращает:**
java.lang.String — строковое значение: имя шрифта
### getDocumentType() {#getDocumentType--}
```
public int getDocumentType()
```


Получает HtmlDocumentTypeInternal .

**Возвращает:**
int — HtmlDocumentTypeInternal.
### getExcludeFontNameList() {#getExcludeFontNameList--}
```
public String[] getExcludeFontNameList()
```


Список имен встроенных шрифтов PDF, которые не могут быть встроены в HTML.

**Возвращает:**
java.lang.String[] - массив строковых элементов
### getExplicitListOfSavedPages() {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```


С помощью этого свойства вы можете явно указать, какие страницы документа должны быть преобразованы. Страницы в этом списке должны иметь номера, начинающиеся с 1. Т.е. действительные номера страниц должны быть взяты из диапазона (1...[NumberOfPagesInConvertedDocument]) Порядок появления страниц в этом списке не влияет на их порядок в результирующей HTML-странице (-ах) - в результирующих страницах всегда будет следовать порядок, в котором они присутствуют в исходном PDF-файле. Если этот список пуст (по умолчанию), все страницы будут преобразованы. Если какой-либо номер страницы этого списка выйдет за пределы диапазона существующих страниц (1-[количество страниц в документе]) будет выдано исключение.

**Возвращает:**
инт[]
### getFixedLayout() {#getFixedLayout--}
```
public boolean getFixedLayout()
```


Получает значение, указывающее, создан ли этот HTML как фиксированный макет.

**Возвращает:**
 логическое значение: истинно, если[фиксированная раскладка]; в противном случае ложь.
### getFontEncodingStrategy() {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```


Определяет специальное правило кодирования для настройки декодирования PDF для текущего документа.

**Возвращает:**
byte — элемент FontEncodingRules
### getFontSavingMode() {#getFontSavingMode--}
```
public int getFontSavingMode()
```


Определяет режим сохранения шрифта, который будет использоваться при сохранении PDF в желаемом формате.

**Возвращает:**
int - элемент FontSavingModes
### getFontSources() {#getFontSources--}
```
public FontSourceCollection getFontSources()
```


Источники предварительно сохраненных шрифтов.

**Возвращает:**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) - Объект FontSourceCollection

--------------------

Шрифты могут быть предварительно сохранены для целей кеша, а затем переданы в процесс преобразования Html. Например, это может быть полезно в сценарии разделения документа и обработки страниц документа в нескольких потоках с одним набором шрифтов.
### getHtmlMarkupGenerationMode() {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```


Иногда предъявляются особые требования к генерации HTML-разметки. Этот параметр определяет режимы подготовки HTML, которые можно использовать во время преобразования PDF в HTML для соответствия таким конкретным требованиям.

**Возвращает:**
int — элемент HtmlMarkupGenerationModes
### getImageResolution() {#getImageResolution--}
```
public int getImageResolution()
```


Получает или задает разрешение для рендеринга изображения.

**Возвращает:**
int — значение: разрешение
### getLettersPositioningMethod() {#getLettersPositioningMethod--}
```
public int getLettersPositioningMethod()
```


Задает способ расположения букв в словах в результирующем HTML

**Возвращает:**
int — элемент LettersPositioningMethods
### getMinimalLineWidth() {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```


Этот атрибут задает минимальную ширину линии графического контура. Если толщина линии меньше 1 пикселя, Adobe Acrobat округляет ее до этого значения. Таким образом, этот атрибут можно использовать для имитации такого поведения HTML-браузеров.

**Возвращает:**
float - плавающее значение
### getPageBorderIfAny() {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```


Этот атрибут представляет собой набор настроек, используемых для рисования границы (если есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. По сути, это касается отображения краев бумаги страницы, а не границы страницы, на которую ссылается сама страница PDF.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - экземпляр BorderInfo
### getPageMarginIfAny() {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```


Этот атрибут представляет набор дополнительных полей страницы (если они есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Экземпляр MarginInfo
### getPartsEmbeddingMode() {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```


Он определяет, будут ли ссылочные файлы (HTML, шрифты, изображения, CSS) встроены в основной файл HTML или будут сгенерированы как отдельные двоичные объекты.

**Возвращает:**
int — элемент PartsEmbeddingModes
### getPreventGlyphsGrouping() {#getPreventGlyphsGrouping--}
```
public boolean getPreventGlyphsGrouping()
```


Этот атрибут включает режим, при котором текстовые глифы не будут группироваться в слова и строки. Этот режим позволяет сохранить максимальную точность при позиционировании глифов на странице и может быть использован для конвертации документов с нотами или глифами, которые необходимо размещать отдельно друг от друга. Другой. Этот параметр будет применяться к документу только в том случае, если значение атрибута FixedLayout равно true.

**Возвращает:**
boolean - логическое значение
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Возвращает:**
com.aspose.pdf.ConversionProgressEventsTranslator — экземпляр ConversionProgressEventsTranslator
### getRasterImagesSavingMode() {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```


Преобразованный PDF может содержать растровые изображения. Этот параметр определяет, как они должны обрабатываться при преобразовании PDF в HTML.

**Возвращает:**
int - элемент RasterImagesSavingModes
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Формат сохранения данных.

**Возвращает:**
[SaveFormat](../../com.aspose.pdf/saveformat) - Значение формата сохранения
### getSimpleTextboxModeGrouping() {#getSimpleTextboxModeGrouping--}
```
public final boolean getSimpleTextboxModeGrouping()
```


Этот атрибут указывает последовательную группировку глифов и слов в строки. Например, теги и слова имеют разный порядок в преобразованном HTML, и вы хотите, чтобы они совпадали. Этот параметр будет применяться к документу только в том случае, если значение атрибута FixedLayout равно true.

**Возвращает:**
boolean - логическое значение
### getSpecialFolderForAllImages() {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```


Получает или задает путь к каталогу, в который должны быть сохранены любые изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пуст или нулевой, то файлы изображений (если они есть) будут сохранены вместе с другими файлами, связанными с HTML. Это ни на что не влияет, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения.

**Возвращает:**
java.lang.String — строковое значение
### getSpecialFolderForSvgImages() {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```


Получает или задает путь к каталогу, в который должны быть сохранены только SVG-изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пустой или нулевой, то файлы SVG (если они есть) будут сохранены вместе с другими файлами-изображениями (рядом с выходным файлом) или в специальную папку для изображений (если это указано в опции SpecialImagesFolderIfAny). Это ни на что не влияет, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения.

**Возвращает:**
java.lang.String — строковое значение
### getSplitCssIntoPages() {#getSplitCssIntoPages--}
```
public boolean getSplitCssIntoPages()
```


Когда выбран многостраничный режим (т.е. 'SplitIntoPages' имеет значение 'true'), то этот атрибут определяет, должен ли быть создан отдельный CSS-файл для каждой результирующей HTML-страницы. По умолчанию этот атрибут имеет значение false, поэтому для всех создаваемых страниц будет создан один большой общий CSS. Суммарный размер всех CSS, сгенерированных в этом режиме (один CSS на страницу), обычно намного больше, чем размер одного большого файла CSS, потому что в первом случае классы CSS дублируются в таком случае в нескольких файлах CSS для каждой страницы. Таким образом, этот параметр хуже использовать только тогда, когда Вы заинтересованы в дальнейшей обработке каждой HTML-страницы независимо, и поэтому размер CSS каждой отдельной страницы, разобранной на части, является наиболее критичным вопросом.

**Возвращает:**
boolean - логическое значение
### getSplitIntoPages() {#getSplitIntoPages--}
```
public boolean getSplitIntoPages()
```


Получает флаг, указывающий, будет ли каждая страница исходного документа преобразована в свой собственный целевой HTML-документ, т.е. будет ли результирующий HTML разбит на несколько HTML-страниц.

**Возвращает:**
boolean - логическое значение
### getUseZOrder() {#getUseZOrder--}
```
public boolean getUseZOrder()
```


Если для атрибута UseZORder установлено значение true, графика и текст добавляются в результирующий HTML-документ в соответствии с Z-порядком в исходном PDF-документе. Если этот атрибут имеет значение false, вся графика помещается в один слой, что может вызвать некоторые ненужные эффекты для перекрывающихся объектов.

**Возвращает:**
boolean - логическое значение
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. «Продолжить» — это действие по умолчанию, и операция «Сохранить» продолжается, однако пользователь может также вернуть команду «Прервать», и в этом случае операция «Сохранить» должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

**Возвращает:**
boolean - логическое значение
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR.

Значение: в результирующий документ будет извлечен истинный текст; в противном случае ложь.

**Возвращает:**
boolean - логическое значение
### isPagesFlowTypeDependsOnViewersScreenSize() {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```


Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, будет помещен в один большой результирующий HTML-файл. Этот флаг определяет, будет ли результирующий HTML генерироваться таким образом, что поток областей, представляющих страницы PDF в результирующем HTML, будет зависеть от разрешения экрана средства просмотра. Предположим, что ширина экрана со стороны зрителя достаточно велика, чтобы разместить 2 или более страниц одну рядом с другой в горизонтальном направлении. Если этот флаг установлен в true, то эта возможность будет использована (будет показано столько страниц в горизонтальном направлении одна рядом с другой, сколько возможно, тогда следующая горизонтальная группа страниц будет показана под первой). В противном случае страницы будут перетекать таким образом: следующая страница всегда идет под предыдущей.

**Возвращает:**
boolean - логическое значение
### isRemoveEmptyAreasOnTopAndBottom() {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```


Определяет, будут ли в созданном HTML удаляться верхняя и нижняя пустые области без содержимого (если оно есть).

**Возвращает:**
boolean - логическое значение
### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Если для атрибута RenderTextAsImage задано значение true, текст из источника становится изображением в формате HTML. Может быть полезно, чтобы сделать текст недоступным для выбора или HTML-текст не отображается должным образом.

**Возвращает:**
boolean - логическое значение
### isSaveFullFont() {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```


Указывает, что будет сохранен полный шрифт, поддерживаются только шрифты True Type. По умолчанию SaveFullFont = false и конвертер сохраняет подмножество исходного шрифта, необходимое для отображения текста документа.

**Возвращает:**
boolean - логическое значение
### isSaveShadowedTextsAsTransparentTexts() {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```


Pdf может содержать тексты, которые затенены другими элементами (например, изображениями), но могут быть выделены в буфер обмена в Acrobat Reader (обычно это происходит, когда документ содержит изображения и извлеченные из них тексты, подвергнутые распознаванию). Эти настройки сообщают конвертеру, нужно ли нам сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML, чтобы имитировать поведение Acrobat Reader (иначе такие тексты обычно сохраняются как скрытые, недоступные для копирования в буфер обмена)

**Возвращает:**
boolean - логическое значение
### isSaveTransparentTexts() {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```


Pdf может содержать прозрачные тексты, которые можно выделить в буфер обмена (обычно это происходит, когда документ содержит изображения и извлеченные из него OCR-тексты). Эти настройки сообщают конвертеру, нужно ли нам сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML.

**Возвращает:**
boolean - логическое значение
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

**Возвращает:**
boolean - логическое значение
### isTrySaveTextUnderliningAndStrikeoutingInCss() {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```


Сам PDF не содержит маркеров подчеркивания для текстов. Он эмулируется строкой, расположенной под текстом. Эта опция позволяет конвертеру попытаться угадать, что та или иная строка является подчеркиванием текста, и занести эту информацию в CSS вместо того, чтобы рисовать или подчеркивать графически.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdditionalMarginWidthInPoints(int value) {#setAdditionalMarginWidthInPoints-int-}
```
public void setAdditionalMarginWidthInPoints(int value)
```


Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, не будет разделен на разные HTML-страницы, а будет помещен в один большой результирующий HTML-файл. Но каждая исходная PDF-страница будет представлена своей собственной прямоугольной областью в HTML (при необходимости эти области могут быть ограничены для отображения краев бумаги страницы с помощью специального атрибута «PageBorderIfAny». Этот параметр определяет ширину поля, которое будет принудительно оставлено вокруг этого выходного HTML-кода. -области, которые представляют собой страницы исходного PDF-документа. По сути, он определяет гарантированный интервал между HTML-представлениями "бумажных" страниц PDF, такой режим преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setAntialiasingProcessing(int antialiasingProcessing) {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```


Этот параметр определяет необходимые меры сглаживания при преобразовании составных фоновых изображений из PDF в HTML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| antialiasingProcessing | int | Элемент AntialiasingProcessingType |

### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCompressSvgGraphicsIfAny(boolean value) {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```


Устанавливает флаг, указывающий, будет ли найденная графика SVG (если есть) сжата (заархивирована) в формат SVGZ во время сохранения

Значение: HtmlDocumentType.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setConvertMarkedContentToLayers(boolean value) {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```


Если для атрибута ConvertMarkedContentToLayers задано значение true, то все элементы внутри помеченного PDF-содержимого (слоя) будут помещены в элемент div HTML с атрибутом «data-pdflayer», указывающим имя слоя. Это имя слоя будет извлечено из необязательных свойств помеченного содержимого PDF. Если этот атрибут имеет значение false (по умолчанию), то никакие слои не будут созданы из содержимого, помеченного PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCssClassNamesPrefix(String cssClassNamesPrefix) {#setCssClassNamesPrefix-java.lang.String-}
```
public void setCssClassNamesPrefix(String cssClassNamesPrefix)
```


Когда конвертер PDFtoHTML генерирует результирующие CSS, имена классов CSS (что-то вроде «.stl\ _01\{\}" ... ".stl\ _NN\{\}) генерируются и используются в результирующем CSS. Это свойство позволяет принудительно установить префикс имени класса. Например, если Вы хотите, чтобы все имена классов начинались с 'my\_префикс\_' (т.е. были чем-то вроде 'мой\_префикс\_1'...'мой\_префикс\_NNN' ), затем просто назначьте 'мой\_префикс\_' к этому свойству перед преобразованием. Если это свойство останется нетронутым (т.е. в качестве значения будет оставлено значение null ), то конвертер сам сгенерирует имена классов (это будет что-то вроде ".stl\ _01\{\}" ... ".stl\ _NN\{\}")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| cssClassNamesPrefix | java.lang.String | Строковое значение |

### setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy) {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
```
public void setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy)
```


Это поле может содержать стратегию сохранения, которая должна использоваться (если присутствует) во время преобразования Pdf в Html для управления сохранением CSS, связанных с созданным HTML-документом в целом или с его страницами (если создается несколько HTML-страниц). Если вы хотите обрабатывать файл CSS каким-то особым образом, просто создайте соответствующий метод и назначьте делегата, созданного из него, этому свойству.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customCssSavingStrategy | [CssSavingStrategy](../../com.aspose.pdf/csssavingstrategy) | Экземпляр CssSavingStrategy |

### setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy) {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
```
public void setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy)
```


Результат конвертации может содержать одну или несколько HTML-страниц. Этому свойству можно присвоить делегат, созданный из пользовательского метода, реализующего обработку одной HTML-страницы (точнее - разметки-HTML, без внешних связанных файлов, если таковые имеются), которая была создана во время преобразование. В этом случае обработка (например, сохранение HTML-кода страницы в потоке или на диске) может выполняться в этом пользовательском коде. В таком случае все необходимые действия по сохранению HTML-страницы должны быть выполнены в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка в том или ином случае по каким-либо причинам должна производиться самим кодом конвертера, а не в пользовательском коде, пожалуйста, установите в пользовательском коде флаг CustomProcessingCancelled переменной параметра htmlSavingInfo: это будет сигнализировать конвертеру, что все необходимые шаги для обработка этого ресурса должна производиться в самом конвертере так же, как если бы не было никакого внешнего пользовательского кода для обработки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customHtmlSavingStrategy | [HtmlPageMarkupSavingStrategy](../../com.aspose.pdf/htmlpagemarkupsavingstrategy) | Экземпляр HtmlPageMarkupSavingStrategy |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)
```


Этот обработчик можно использовать для обработки событий о ходе преобразования, например, для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц. Пример кода обработчика, показывающего ход выполнения на консоли:

--------------------

```
public static void ConvertWithShowingProgress()
     {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
     public void invoke(
     UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
     showProgressOnConsole(eventInfo);
     }
     };
     doc.save("Booklet.doc", saveOptions);
     }
     public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
     {
     switch (eventInfo.EventType)
     {
     case HtmlSaveOptions.ProgressEventType.TotalProgress:
     System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
     break;
     case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
     System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
     System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
     System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     default:
     break;
     }
     }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customProgressHandler | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | Экземпляр ConversionProgressEventHandler |

### setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy) {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
```
public void setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy)
```


Это поле может содержать стратегию сохранения, которую необходимо использовать (если она присутствует) во время преобразования для индивидуальной обработки созданных файлов ресурсов (например, изображений и шрифтов), связанных с узлами сохраненного HTML. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URL-адрес сохраненного ресурса в сгенерированном HTML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customResourceSavingStrategy | [ResourceSavingStrategy](../../com.aspose.pdf/resourcesavingstrategy) | Экземпляр ResourceSavingStrategy |

### setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation) {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
```
public void setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation)
```


Это поле может содержать пользовательский метод, который возвращает URL-адрес (или шаблон URL-адреса, если включена многостраничная генерация — см. подробности ниже) предметного CSS, поскольку он должен быть помещен в сгенерированный результирующий HTML-код. Например, если вы хотите, чтобы конвертер поместил какой-то конкретный URL-адрес вместо стандартного имени файла CSS в сгенерированный CSS-файл, вам нужно просто создать и поместить в это свойство метод, который генерирует желаемый URL-адрес. Если установлен флаг «SplitCssIntoPages», то эта пользовательская стратегия (если есть) должна возвращать не точный URL-адрес CSS, а строку шаблона, которая (после замены заполнителя номером страницы с помощью функции String.Format() внутри конвертера) может быть преобразована в URL-адрес для URL той или иной страницы CSS. Примеры ожидаемой возвращаемой строки в таком случае: 'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\ {0\} ' )

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customStrategyOfCssUrlCreation | [CssUrlMakingStrategy](../../com.aspose.pdf/cssurlmakingstrategy) | Экземпляр CssUrlMakingStrategy |

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


Указывает имя установленного шрифта, который используется для замены любого шрифта документа, который не встроен и не установлен в системе. Если null, то используется шрифт замены по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Название шрифта |

### setDocumentType(int value) {#setDocumentType-int-}
```
public void setDocumentType(int value)
```


Задает HtmlDocumentType .

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | HtmlDocumentType . |

### setExcludeFontNameList(String[] excludeFontNameList) {#setExcludeFontNameList-java.lang.String---}
```
public void setExcludeFontNameList(String[] excludeFontNameList)
```


Список имен встроенных шрифтов PDF, которые не могут быть встроены в HTML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| excludeFontNameList | java.lang.String[] | массив строковых элементов |

### setExplicitListOfSavedPages(int[] value) {#setExplicitListOfSavedPages-int---}
```
public final void setExplicitListOfSavedPages(int[] value)
```


С помощью этого свойства вы можете явно указать, какие страницы документа должны быть преобразованы. Страницы в этом списке должны иметь номера, начинающиеся с 1. Т.е. действительные номера страниц должны быть взяты из диапазона (1...[NumberOfPagesInConvertedDocument]) Порядок появления страниц в этом списке не влияет на их порядок в результирующей HTML-странице (-ах) - в результирующих страницах всегда будет следовать порядок, в котором они присутствуют в исходном PDF-файле. Если этот список пуст (по умолчанию), все страницы будут преобразованы. Если какой-либо номер страницы этого списка выйдет за пределы диапазона существующих страниц (1-[количество страниц в документе]) будет выдано исключение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR.

Значение: в результирующий документ будет извлечен истинный текст; в противном случае ложь.

--------------------

Значение по умолчанию == ложь

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFixedLayout(boolean value) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```


Задает значение, указывающее, создан ли этот HTML как фиксированный макет.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  : верно, если[фиксированная раскладка]; в противном случае ложь. |

### setFontEncodingStrategy(byte fontEncodingStrategy) {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```


Определяет специальное правило кодирования для настройки декодирования PDF для текущего документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontEncodingStrategy | byte | Элемент FontEncodingRules |

### setFontSavingMode(int fontSavingMode) {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```


Определяет режим сохранения шрифта, который будет использоваться при сохранении PDF в желаемом формате.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSavingMode | int | Элемент FontSavingModes |

### setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode) {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```


Иногда предъявляются особые требования к генерации HTML-разметки. Этот параметр определяет режимы подготовки HTML, которые можно использовать во время преобразования PDF в HTML для соответствия таким конкретным требованиям.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlMarkupGenerationMode | int | Элемент HtmlMarkupGenerationModes |

### setImageResolution(int value) {#setImageResolution-int-}
```
public void setImageResolution(int value)
```


Получает или задает разрешение для рендеринга изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение: Разрешение |

### setLettersPositioningMethod(int lettersPositioningMethod) {#setLettersPositioningMethod-int-}
```
public void setLettersPositioningMethod(int lettersPositioningMethod)
```


Задает способ расположения букв в словах в результирующем HTML

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| lettersPositioningMethod | int | Элемент LettersPositioningMethods |

### setMinimalLineWidth(float value) {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```


Этот атрибут задает минимальную ширину линии графического контура. Если толщина линии меньше 1 пикселя, Adobe Acrobat округляет ее до этого значения. Таким образом, этот атрибут можно использовать для имитации такого поведения HTML-браузеров.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny) {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
```
public void setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny)
```


Этот атрибут представляет собой набор настроек, используемых для рисования границы (если есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. По сути, это касается отображения краев бумаги страницы, а не границы страницы, на которую ссылается сама страница PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageBorderIfAny | [BorderInfo](../../com.aspose.pdf/borderinfo) | Экземпляр BorderInfo |

### setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny) {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
```
public void setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny)
```


Этот атрибут представляет набор дополнительных полей страницы (если они есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageMarginIfAny | [MarginInfo](../../com.aspose.pdf/margininfo) | Экземпляр MarginInfo |

### setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize) {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```


Если атрибут 'SplitOnPages=false', то весь HTML-код, представляющий все входные PDF-страницы, будет помещен в один большой результирующий HTML-файл. Этот флаг определяет, будет ли результирующий HTML генерироваться таким образом, что поток областей, представляющих страницы PDF в результирующем HTML, будет зависеть от разрешения экрана средства просмотра. Предположим, что ширина экрана со стороны зрителя достаточно велика, чтобы разместить 2 или более страниц одну рядом с другой в горизонтальном направлении. Если этот флаг установлен в true, то эта возможность будет использована (будет показано столько страниц в горизонтальном направлении одна рядом с другой, сколько возможно, тогда следующая горизонтальная группа страниц будет показана под первой). В противном случае страницы будут перетекать таким образом: следующая страница всегда идет под предыдущей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize | boolean | логическое значение |

### setPartsEmbeddingMode(int partsEmbeddingMode) {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```


Он определяет, будут ли ссылочные файлы (HTML, шрифты, изображения, CSS) встроены в основной файл HTML или будут сгенерированы как отдельные двоичные объекты.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| partsEmbeddingMode | int | Элемент PartsEmbeddingModes |

### setPreventGlyphsGrouping(boolean value) {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```


Этот атрибут включает режим, при котором текстовые глифы не будут группироваться в слова и строки. Этот режим позволяет сохранить максимальную точность при позиционировании глифов на странице и может быть использован для конвертации документов с нотами или глифами, которые необходимо размещать отдельно друг от друга. Другой. Этот параметр будет применяться к документу только в том случае, если значение атрибута FixedLayout равно true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


 Представляет внутренний обработчик событий выполнения, который работает во время преобразования и переводит события преобразования внутренних этапов преобразования во внешние общие события выполнения. Также класс транслирует события, которые позволяют высвободить ресурсы, которые больше не нужны.[Другой формат] progress для расчета общего прогресса и информирования кода клиента об этих событиях общего прогресса. Этот класс использует два типа событий: преобразование модели ApsToExternal и события преобразования Pdf в APS для создания событий общего прогресса Экспорт состоит из трех этапов: 1) Pdf в Aps 2) Распознавание приложений 3\_ Экспорт приложений в целевой формат Конструктор позволяет настроить, сколько страниц конвертируется и какова приблизительная часть того или иного этапа в общем прогрессе

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | Экземпляр ConversionProgressEventsTranslator |

### setRasterImagesSavingMode(int rasterImagesSavingMode) {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```


Преобразованный PDF может содержать растровые изображения. Этот параметр определяет, как они должны обрабатываться при преобразовании PDF в HTML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImagesSavingMode | int | Элемент RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom) {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```


Определяет, будут ли в созданном HTML удаляться верхняя и нижняя пустые области без содержимого (если оно есть).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom | boolean | логическое значение |

### setRenderTextAsImage(boolean value) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```


Если для атрибута RenderTextAsImage задано значение true, текст из источника становится изображением в формате HTML. Может быть полезно, чтобы сделать текст недоступным для выбора или HTML-текст не отображается должным образом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSaveFullFont(boolean saveFullFont) {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean saveFullFont)
```


Указывает, что будет сохранен полный шрифт, поддерживаются только шрифты True Type. По умолчанию SaveFullFont = false и конвертер сохраняет подмножество исходного шрифта, необходимое для отображения текста документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| saveFullFont | boolean | логическое значение |

### setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts) {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```


Pdf может содержать тексты, которые затенены другими элементами (например, изображениями), но могут быть выделены в буфер обмена в Acrobat Reader (обычно это происходит, когда документ содержит изображения и извлеченные из них тексты, подвергнутые распознаванию). Эти настройки сообщают конвертеру, нужно ли нам сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML, чтобы имитировать поведение Acrobat Reader (иначе такие тексты обычно сохраняются как скрытые, недоступные для копирования в буфер обмена)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts | boolean | логическое значение |

### setSaveTransparentTexts(boolean saveTransparentTexts) {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```


Pdf может содержать прозрачные тексты, которые можно выделить в буфер обмена (обычно это происходит, когда документ содержит изображения и извлеченные из него OCR-тексты). Эти настройки сообщают конвертеру, нужно ли нам сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| saveTransparentTexts | boolean | логическое значение |

### setSimpleTextboxModeGrouping(boolean value) {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```


Этот атрибут указывает последовательную группировку глифов и слов в строки. Например, теги и слова имеют разный порядок в преобразованном HTML, и вы хотите, чтобы они совпадали. Этот параметр будет применяться к документу только в том случае, если значение атрибута FixedLayout равно true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSpecialFolderForAllImages(String specialFolderForAllImages) {#setSpecialFolderForAllImages-java.lang.String-}
```
public void setSpecialFolderForAllImages(String specialFolderForAllImages)
```


Получает или задает путь к каталогу, в который должны быть сохранены любые изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пуст или нулевой, то файлы изображений (если они есть) будут сохранены вместе с другими файлами, связанными с HTML. Это ни на что не влияет, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| specialFolderForAllImages | java.lang.String | Строковое значение |

### setSpecialFolderForSvgImages(String specialFolderForSvgImages) {#setSpecialFolderForSvgImages-java.lang.String-}
```
public void setSpecialFolderForSvgImages(String specialFolderForSvgImages)
```


Получает или задает путь к каталогу, в который должны быть сохранены только SVG-изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пустой или нулевой, то файлы SVG (если они есть) будут сохранены вместе с другими файлами-изображениями (рядом с выходным файлом) или в специальную папку для изображений (если это указано в опции SpecialImagesFolderIfAny). Это ни на что не влияет, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| specialFolderForSvgImages | java.lang.String | Строковое значение |

### setSplitCssIntoPages(boolean value) {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```


Когда выбран многостраничный режим (т.е. 'SplitIntoPages' имеет значение 'true'), то этот атрибут определяет, должен ли быть создан отдельный CSS-файл для каждой результирующей HTML-страницы. По умолчанию этот атрибут имеет значение false, поэтому для всех создаваемых страниц будет создан один большой общий CSS. Суммарный размер всех CSS, сгенерированных в этом режиме (один CSS на страницу), обычно намного больше, чем размер одного большого файла CSS, потому что в первом случае классы CSS дублируются в таком случае в нескольких файлах CSS для каждой страницы. Таким образом, этот параметр хуже использовать только тогда, когда Вы заинтересованы в дальнейшей обработке каждой HTML-страницы независимо, и поэтому размер CSS каждой отдельной страницы, разобранной на части, является наиболее критичным вопросом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSplitIntoPages(boolean value) {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```


Устанавливает флаг, указывающий, будет ли каждая страница исходного документа преобразована в свой собственный целевой HTML-документ, т.е. будет ли результирующий HTML разбит на несколько HTML-страниц.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | логическое значение |

### setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss) {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```


Сам PDF не содержит маркеров подчеркивания для текстов. Он эмулируется строкой, расположенной под текстом. Эта опция позволяет конвертеру попытаться угадать, что та или иная строка является подчеркиванием текста, и занести эту информацию в CSS вместо того, чтобы рисовать или подчеркивать графически.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss | boolean | логическое значение |

### setUseZOrder(boolean value) {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```


Если для атрибута UseZORder установлено значение true, графика и текст добавляются в результирующий HTML-документ в соответствии с Z-порядком в исходном PDF-документе. Если этот атрибут имеет значение false, вся графика помещается в один слой, что может вызвать некоторые ненужные эффекты для перекрывающихся объектов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. «Продолжить» — это действие по умолчанию, и операция «Сохранить» продолжается, однако пользователь может также вернуть команду «Прервать», и в этом случае операция «Сохранить» должна быть прекращена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | Значение IWarningCallback |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
