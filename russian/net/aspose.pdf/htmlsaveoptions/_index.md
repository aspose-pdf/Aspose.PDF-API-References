---
title: "Класс HtmlSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.HtmlSaveOptions. Параметры сохранения для экспорта в формат Html."
type: docs
weight: 5690
url: /ru/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Параметры сохранения для экспорта в формат HTML.

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Инициализирует новый экземпляр класса `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Инициализирует новый экземпляр класса `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Инициализирует новый экземпляр класса `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Инициализирует новый экземпляр класса `HtmlSaveOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения document в ответ. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Получает или задает флаг, указывающий, будет ли найденная графика SVG (если есть) сжата (упакована) в формат SVGZ при сохранении. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Если атрибут ConvertMarkedContentToLayers установлен в true, то все элементы внутри помеченного содержимого PDF (слой) будут помещены в HTML‑div с атрибутом "data-pdflayer", указывающим имя слоя. Это имя слоя будет извлечено из дополнительных свойств помеченного содержимого PDF. Если этот атрибут установлен в false (по умолчанию), то из помеченного содержимого PDF не будет создано никаких слоёв. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Указывает имя установленного шрифта, который используется для замены любого шрифта документа, не встроенного и не установленного в системе. Если значение null, используется шрифт замены по умолчанию. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Получает или задает [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | С помощью этого свойства вы можете явно определить, какие страницы документа следует конвертировать. Страницы в этом списке должны иметь нумерацию, начинающуюся с 1. То есть допустимые номера страниц должны быть взяты из диапазона (1...[NumberOfPagesInConvertedDocument]). Порядок появления страниц в этом списке не влияет на их порядок в результирующих HTML‑страницах — в результирующих страницах они всегда будут идти в том порядке, в котором они присутствуют в исходном PDF. Если список равен null (как по умолчанию), будут конвертированы все страницы. Если любой номер страницы из этого списка выходит за пределы существующих страниц (1-[amountOfPagesInDocument]), будет выброшено исключение. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включил функциональность извлечения изображений или текста из PDF‑документов с подслойкой OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Получает или задает значение, указывающее, создаётся ли HTML в виде фиксированного макета. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Этот атрибут указывает текст абзаца полной ширины для режима Flow, FixedLayout = false. |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Источники шрифтов предварительно сохранённых шрифтов. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Текст указанного размера или меньше будет игнорироваться при конвертации. Мы не удаляем этот текст, а просто игнорируем его и не переносим в выходной файл. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Получает или задает индикатор, указывающий, что ошибки, связанные с отсутствием шрифта, будут игнорироваться. true — означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты текста, ссылающиеся на некорректные ресурсы, будут пропущены во время обработки. false по умолчанию. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Получает или задает разрешение для рендеринга изображения. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Этот атрибут задает минимальную ширину линии графического пути. Если толщина линии меньше 1 px, Adobe Acrobat округляет её до этого значения. Таким образом, этот атрибут можно использовать для эмуляции данного поведения в браузерах HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Этот атрибут переключает режим, при котором глифы текста не группируются в слова и строки. Этот режим позволяет сохранять максимальную точность при позиционировании глифов на странице и может использоваться при конвертации документов с нотными знаками или глифами, которые должны располагаться отдельно друг от друга. Этот параметр будет применён к документу только когда значение атрибута FixedLayout равно true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Если атрибут RenderTextAsImage установлен в true, текст из источника становится изображением в HTML. Это может быть полезно, чтобы сделать текст нечитаемым для выделения или если HTML‑текст отображается некорректно. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Указывает, что будет сохраняться полный шрифт, поддерживает только True Type Fonts. По умолчанию SaveFullFont = false, и конвертер сохраняет подмножество исходного шрифта, необходимое для отображения текста документа. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Этот атрибут задает последовательную группировку глифов и слов в строки. Например, теги и слова имеют разный порядок в конвертированном HTML, и вы хотите, чтобы они совпадали. Этот параметр будет применён к документу только когда значение атрибута FixedLayout равно true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Когда выбран режим мультистраничности (т.е. 'SplitIntoPages' = 'true'), этот атрибут определяет, следует ли создавать отдельный CSS‑файл для каждой результирующей HTML‑страницы. По умолчанию атрибут имеет значение false, поэтому создаётся один большой общий CSS для всех страниц. Суммарный размер всех CSS‑файлов, генерируемых в этом режиме (по одному CSS на страницу), обычно значительно превышает размер одного большого CSS‑файла, потому что в первом случае классы CSS дублируются в нескольких файлах для каждой страницы. Поэтому данную настройку следует использовать только тогда, когда вам необходимо последующее независимое обработка каждой HTML‑страницы, и размер CSS отдельной страницы является критическим фактором. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Получает или задает флаг, указывающий, будет ли каждая страница исходного документа конвертироваться в отдельный целевой HTML‑документ, т.е. будет ли результирующий HTML разбит на несколько HTML‑страниц. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Получает или задает заголовок HTML‑страницы. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Флаг для объединения фрагментов изображения в одну картинку. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Если атрибут UseZORder установлен в true, графика и текст добавляются в результирующий HTML‑документ в соответствии с Z‑порядком в оригинальном PDF‑документе. Если этот атрибут имеет значение false, вся графика помещается в один слой, что может вызвать нежелательные эффекты для перекрывающихся объектов. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Этот параметр определяет необходимые меры сглаживания при конвертации составных фоновых изображений из PDF в HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Когда конвертер PDFtoHTML генерирует результирующие CSS‑файлы, имена классов CSS (например, \".stl_01 {}\" … \".stl_NN {}\") создаются и используются в итоговом CSS. Это свойство позволяет принудительно задать префикс имени класса. Например, если вы хотите, чтобы все имена классов начинались с 'my_prefix_' (т.е. выглядели как 'my_prefix_1' … 'my_prefix_NNN'), просто присвойте 'my_prefix_' этому свойству перед конвертацией. Если это свойство оставлено без изменения (т.е. значение null), конвертер сгенерирует имена классов самостоятельно (это будет что‑то вроде \".stl_01 {}\" … \".stl_NN {}\"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Это поле может содержать стратегию сохранения, которую необходимо использовать (если указана) во время конвертации PDF в HTML для обработки сохранения CSS‑файлов, связанных с созданным HTML‑документом в целом или с его страницами (если генерируется несколько HTML‑страниц). Если вы хотите обрабатывать CSS‑файл каким‑то специфическим образом, просто создайте соответствующий метод и назначьте делегат, созданный из него, этому свойству. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Результат конвертации может содержать одну или несколько HTML‑страниц. Вы можете назначить этому свойству делегат, созданный из пользовательского метода, который реализует обработку одной HTML‑страницы (точнее — разметки HTML без внешних связанных файлов, если такие имеются), созданной во время конвертации. В таком случае обработка (например, сохранение HTML‑страницы в поток или на диск) может быть выполнена в этом пользовательском коде. При этом все необходимые действия по сохранению HTML‑страницы должны быть выполнены в коде предоставленного метода, поскольку сохранение результата в коде конвертера использоваться не будет. Если обработка в том или ином случае по какой‑то причине должна быть выполнена кодом конвертера, а не пользовательским кодом, пожалуйста, установите в пользовательском коде флаг 'CustomProcessingCancelled' переменной параметра 'htmlSavingInfo': это сигнализирует конвертеру, что все необходимые шаги по обработке данного ресурса должны быть выполнены самим конвертером так же, как если бы внешнего пользовательского кода для обработки не было. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Этот обработчик можно использовать для обработки событий прогресса конвертации, например, для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц; пример кода обработчика, выводящего прогресс в консоль: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Это поле может содержать стратегию сохранения, которая должна использоваться (если указана) во время конвертации для пользовательской обработки созданных связанных файлов ресурсов (например, изображений и шрифтов), относящихся к узлам сохранённого HTML. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URL сохранённого ресурса в сгенерированном HTML. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Это поле может содержать пользовательский метод, который возвращает URL (или шаблон URL, если включена генерация нескольких страниц — см. детали ниже) CSS‑файла, который должен быть вставлен в сгенерированный результат HTML. Например, если вы хотите, чтобы конвертер вставил какой‑то конкретный URL вместо стандартного имени CSS‑файла в сгенерированный CSS, то достаточно создать и задать в этом свойстве метод, генерирующий нужный URL. Если установлен флаг 'SplitCssIntoPages', то эта пользовательская стратегия (если она есть) должна возвращать не точный URL CSS, а шаблон строки, который (после подстановки номера страницы с помощью функции string.Format() внутри конвертера) может быть преобразован в URL CSS‑файла конкретной страницы. Примеры ожидаемых строк возврата в таком случае: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Список встроенных в PDF имён шрифтов, которые не должны быть внедрены в HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Определяет специальное правило кодировки для настройки декодирования PDF текущего документа |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Определяет режим сохранения шрифтов, который будет использоваться при сохранении PDF в нужный формат |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Иногда существуют специфические требования к генерации разметки HTML. Этот параметр определяет режимы подготовки HTML, которые могут использоваться при конвертации PDF в HTML для удовлетворения таких специфических требований. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывать страницы в нескольких потоках. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Устанавливает режим позиционирования букв в словах в результирующем HTML |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Этот атрибут представляет набор настроек, используемых для отрисовки рамки (если она есть) в результирующем HTML‑документе вокруг области, представляющей исходную страницу PDF. По сути он относится к отображению краёв листа, а не к границе страницы, указанной в самом PDF. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Этот атрибут представляет набор дополнительных полей страницы (если они есть) в результирующем HTML‑документе вокруг области, представляющей исходную страницу PDF. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Если атрибут 'SplitOnPages=false', то весь HTML, представляющий все входные страницы PDF, будет помещён в один большой результирующий HTML‑файл. Этот флаг определяет, будет ли результирующий HTML генерироваться таким образом, что расположение областей, представляющих страницы PDF, будет зависеть от разрешения экрана просмотрщика. Предположим, ширина экрана у просмотрщика достаточно велика, чтобы разместить 2 и более страниц рядом друг с другом по горизонтали. Если этот флаг установлен в true, то будет использована возможность отображать несколько страниц в горизонтальном ряду (по столько страниц, сколько помещается, затем следующая горизонтальная группа страниц будет размещена под первой). В противном случае страницы будут располагаться последовательно: следующая страница всегда будет под предыдущей. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Определяет, будут ли связанные файлы (HTML, шрифты, изображения, CSS) встроены в основной HTML‑файл или будут созданы как отдельные бинарные сущности |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Преобразованный PDF может содержать растровые изображения. Этот параметр определяет, как их следует обрабатывать при конвертации PDF в HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Определяет, будет ли в созданном HTML удалена верхняя и нижняя пустая область без содержимого (если таковая имеется). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | Pdf может содержать тексты, скрытые другими элементами (например, изображениями), но доступные для копирования в буфер обмена в Acrobat Reader (обычно это происходит, когда документ содержит изображения и извлечённый с помощью OCR текст). Эта настройка указывает конвертеру, нужно ли сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML, чтобы имитировать поведение Acrobat Reader (в противном случае такие тексты обычно сохраняются скрытыми и недоступными для копирования). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | Pdf может содержать прозрачные тексты, которые можно скопировать в буфер обмена (обычно это происходит, когда документ содержит изображения и извлечённый с помощью OCR текст). Эта настройка указывает конвертеру, нужно ли сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Получает или задает путь к каталогу, в который должны сохраняться все изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пустой или null, то файлы изображений (если есть) будут сохранены вместе с другими файлами, связанными с HTML. Это не влияет на работу, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Получает или задает путь к каталогу, в который должны сохраняться только SVG‑изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пустой или null, то SVG‑файлы (если есть) будут сохранены вместе с другими файлами изображений (рядом с выходным файлом) или в специальной папке для изображений (если она указана в параметре SpecialImagesFolderIfAny). Это не влияет на работу, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDFs содержат фоновые изображения (страниц или ячеек таблиц), построенные из нескольких одинаковых плиточных фоновых изображений, размещённых рядом друг с другом. В таком случае рендереры целевых форматов (например MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краёв изображений (anti-aliasing) отличаются от Acrobat Reader. Если кажется, что экспортированный document содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от нежелательного эффекта. ATTENTION! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только когда это действительно необходимо. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | Сам PDF не содержит маркеров подчеркивания для текста. Оно имитируется линией, расположенной под текстом. Эта опция позволяет конвертеру попытаться определить, является ли та или иная линия подчеркиванием текста, и поместить эту информацию в CSS вместо графического рисования подчеркивания. |

## Примеры

Следующий пример показывает, как преобразовать файл PDF в файл HTML.

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// Путь к выходному файлу HTML.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Инициализировать HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Сохранить файл HTML
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

### См. также

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


