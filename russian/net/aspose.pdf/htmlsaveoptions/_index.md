---
title: HtmlSaveOptions
second_title: Aspose.PDF для справочника API .NET
description: Сохранить параметры для экспорта в формат HTML
type: docs
weight: 3430
url: /ru/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Сохранить параметры для экспорта в формат HTML

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions#constructor)() | Инициализирует новый экземпляр[`HtmlSaveOptions`](../htmlsaveoptions) класс. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_3)(bool) | Инициализирует новый экземпляр[`HtmlSaveOptions`](../htmlsaveoptions) класс. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_1)(HtmlDocumentType) | Инициализирует новый экземпляр[`HtmlSaveOptions`](../htmlsaveoptions) класс. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_2)(HtmlDocumentType, bool) | Инициализирует новый экземпляр[`HtmlSaveOptions`](../htmlsaveoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize) { get; set; } | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в response. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany) { get; set; } | Получает или устанавливает флаг, указывающий, будет ли найденная графика SVG (если есть) сжата (заархивирована) в формат SVGZ во время сохранения |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers) { get; set; } | Если для атрибута ConvertMarkedContentToLayers задано значение true, то все элементы внутри содержимого (слоя) PDF с пометкой будут помещены в HTML-раздел с атрибутом «data-pdflayer», указывающим имя слоя. Имя этого слоя будет извлечено из дополнительных свойств PDF отмеченное содержимое. Если этот атрибут имеет значение false (по умолчанию), то никакие слои не будут созданы из содержимого PDF с пометкой. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname) { get; set; } | Указывает имя установленного шрифта, который используется для замены любого шрифта документа, который не встроен и не установлен в системе. Если null, то используется шрифт замены по умолчанию. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype) { get; set; } | Получает или задает[`HtmlDocumentType`](../htmldocumenttype) . |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages) { get; set; } | С помощью этого свойства вы можете явно определить какие страницы документа должны быть преобразованы. Страницы в этом списке должны иметь номера, начинающиеся с 1. Т.е. корректные номера страниц должны быть взяты из диапазона (1...[NumberOfPagesInConvertedDocument]) Порядок появления страниц в этом списке не влияет на их порядок в результирующей HTML-странице(ах) - в результирующих страницах всегда будет идти по порядку в котором они присутствуют в исходном PDF. Если этот список пуст (по умолчанию), все страницы будут преобразованы. количество страниц в документе]) будет выдано исключение. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout) { get; set; } | Получает или задает значение, указывающее, создан ли этот HTML как фиксированный макет. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth) { get; set; } | Этот атрибут определяет текст абзаца полной ширины для режима Flow, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources) { get; } | Источники предварительно сохраненных шрифтов. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution) { get; set; } | Получает или задает разрешение для рендеринга изображения. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth) { get; set; } | Этот атрибут устанавливает минимальную ширину линии графического контура. Если толщина линии меньше 1 пикселя, Adobe Acrobat округляет ее до этого значения. Таким образом, этот атрибут может использоваться для эмуляции этого поведения для HTML-браузеров. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping) { get; set; } | Этот атрибут включает режим, при котором текстовые глифы не будут группироваться в слова и строки Этот режим позволяет сохранить максимальную точность при позиционировании глифов на странице и может быть использован для преобразования документов с нотами или глифами, которые должны быть размещены отдельно друг друга. Этот параметр будет применяться к документу только в том случае, если значение атрибута FixedLayout равно true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage) { get; set; } | Если для атрибута RenderTextAsImage задано значение true, текст из источника становится изображением в HTML. Может быть полезно, чтобы сделать текст недоступным для выбора или текст HTML отображается неправильно. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Формат сохранения данных. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping) { get; set; } | Этот атрибут определяет последовательное группирование глифов и слов в строки Например, теги и слова имеют разный порядок в преобразованном HTML, и вы хотите, чтобы они совпадали. Этот параметр будет применяться к документу, только если значение атрибута FixedLayout равно true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages) { get; set; } | Когда выбран многостраничный режим (т.е. "SplitIntoPages" имеет значение "true"), тогда этот атрибут определяет, следует ли создавать отдельный CSS-файл для каждой HTML-страницы результата. По умолчанию этот атрибут равен false, поэтому будет создан один большой общий CSS для всех создаваемых страниц. Суммарный размер всех CSS, сгенерированных в этом режиме (один CSS на страницу) обычно намного больше, чем размер одного большого файла CSS, потому что в первом случае классы CSS дублируются в таком случае в нескольких файлах CSS для каждой страницы. Итак, это параметр хуже использовать только тогда, когда Вы заинтересованы в дальнейшей обработке каждой HTML-страницы независимо, и поэтому размер CSS каждой отдельной страницы, разобранной на части, является наиболее важным вопросом. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages) { get; set; } | Получает или устанавливает флаг, указывающий, будет ли каждая страница исходного документа преобразована в собственный целевой HTML-документ, т.е. будет ли результирующий HTML разбит на несколько HTML-страниц. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder) { get; set; } | Если для атрибута UseZORder установлено значение true, графика и текст добавляются в результирующий HTML-документ в соответствии с Z-порядком в исходном PDF-документе. Если этот атрибут имеет значение false, вся графика помещается как один слой, что может вызвать некоторые ненужные эффекты для перекрывающихся объектов. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция сохранения продолжается, однако пользователь может также вернуть команду Прервать, и в этом случае операция сохранения должна быть прекращена. |

## Поля

| Имя | Описание |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing) | Этот параметр определяет необходимые меры по сглаживанию при преобразовании составных фоновых изображений из PDF в HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix) | Когда конвертер PDFtoHTML генерирует результирующие CSS, имена классов CSS (что-то вроде ".stl_01 {}" ... ".stl_NN {}) генерируются и используются в результирующем CSS. Это свойство позволяет принудительно установить префикс имени класса Например, если вы хотите, чтобы все имена классов начинались с 'my_prefix_' (т.е. были чем-то вроде 'my_prefix_1'... 'my_prefix_NNN'), , тогда просто назначьте 'my_prefix_' этому свойству перед преобразованием. Если это свойство останется нетронутым (т.е. null будет оставлен как значение ), тогда конвертер сам сгенерирует имена классов (это будет что-то вроде ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy) | Это поле может содержать стратегию сохранения , которая должна использоваться (если присутствует) во время преобразования Pdf в HTML для управления сохранением CSS, связанных с созданным HTML-документом целиком или с его страницами (если создается несколько HTML-страниц) Если хотите обрабатывать файл CSS определенным образом, просто создайте соответствующий метод и назначьте делегата, созданного из него, этому свойству. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy) | Результат конвертации может содержать одну или несколько HTML-страниц Этому свойству можно присвоить делегат, созданный из пользовательского метода, который реализует обработку одной HTML-страницы (точнее - разметки-HTML, без внешних связанных файлов, если они есть) что был создан во время преобразования. В этом случае обработка (например, сохранение HTML страницы в потоке или на диске) может быть выполнена в этом пользовательском коде. В этом случае все необходимые действия по сохранению HTML-страницы должны быть выполнены в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка в том или ином случае по какой-либо причине должна производиться самим кодом конвертера, не в пользовательском коде, пожалуйста, установите в пользовательском коде флаг CustomProcessingCancelled' переменной параметра htmlSavingInfo: это будет сигнализировать конвертеру, что все необходимые шаги для обработки этого ресурса должны быть выполнены в самом конвертере так же как если бы не было никакого внешнего пользовательского кода для обработки . |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler) | Этот обработчик может использоваться для обработки событий процесса преобразования например, его можно использовать для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц, пример кода обработчика, который показывает ход выполнения на консоли: : |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy) | Это поле может содержать стратегию сохранения , которая должна использоваться (если присутствует) во время преобразования для индивидуальной обработки созданных файлов ресурсов (таких как изображения и шрифты), связанных с узлами сохраненного HTML. Эта стратегия должна обрабатывать ресурсы и возвращать строку, которая представляет желаемый URL-адрес сохраненного resource в сгенерированном HTML. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation) | Это поле может содержать пользовательский метод, который возвращает URL-адрес (или шаблон URL-адреса, если включена многостраничная генерация - см. подробности ниже) subject CSS, поскольку он должен быть помещен в сгенерированный результат HTML. Имя файла CSS в сгенерированный CSS, затем вам нужно просто создать и поместить в это свойство method , который генерирует желаемый URL. Если установлен флаг «SplitCssIntoPages», тогда эта пользовательская стратегия (если есть) должна возвращать не точный URL CSS, а скорее шаблон строка that (после замены заполнителя номером страницы с помощью функции string.Format() внутри конвертера) может быть преобразована в URL для той или иной CSS-URL той или иной страницы. Примеры ожидаемой возвращаемой строки в таком случае: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist) | Список названий встроенных шрифтов PDF, которые не могут быть встроены в HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy) | Определяет специальное правило кодирования для настройки декодирования PDF для текущего документа |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode) | Определяет режим сохранения шрифта, который будет использоваться при сохранении PDF в желаемом формате |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode) | Иногда предъявляются особые требования к созданию HTML-разметки. Этот параметр определяет режимы подготовки HTML, которые можно использовать при преобразовании PDF в HTML для соответствия таким конкретным требованиям. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod) | Устанавливает режим расположения букв в словах в результате HTML |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany) | Этот атрибут представляет собой набор настроек, используемых для рисования границы (если есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. По сути, он касается отображения краев бумаги страницы, не границы страницы, на которую ссылается сама страница PDF. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany) | Этот атрибут представляет набор дополнительных полей страницы (если есть) в результирующем HTML-документе вокруг области, представляющей исходную страницу PDF. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize) | Если атрибут 'SplitOnPages=false', весь HTML-код, представляющий все входные PDF-страницы, будет помещен в один большой результирующий HTML-файл. Этот флаг определяет, будет ли HTML-результат генерироваться таким образом, что поток областей, представляющих PDF-страницы в HTML-результате, будет зависеть от разрешения экрана вьювера. Предположим, что ширина экрана со стороны зрителя достаточно велика, чтобы поместить 2 или более страниц одну рядом с другой в горизонтальном направлении. Если этот флаг установлен в true, то будет использоваться эта возможность (будет показано столько страниц в горизонтальном направлении одна рядом с другой , сколько возможно, тогда следующая горизонтальная группа страниц будет показана под первой). В противном случае страницы будут перетекать друг в друга таким образом: следующая страница всегда идет под предыдущей. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode) | Определяет, будут ли файлы ссылок (HTML, шрифты, изображения, CSS) встроены в основной файл HTML или будут сгенерированы как отдельные двоичные объекты |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode) | Преобразованный PDF может содержать растровые изображения Этот параметр определяет, как они должны обрабатываться во время преобразования PDF в HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom) | Определяет, будут ли в созданном HTML удаляться верхняя и нижняя пустые области без содержимого (если оно есть). |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont) | Указывает, что будет сохранен полный шрифт, поддерживаются только шрифты True Type. По умолчанию SaveFullFont = false и конвертер сохраняет подмножество исходного шрифта , необходимое для отображения текста документа. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts) | Pdf может содержать текст, который затенен другими элементами (например, изображениями), но может быть выделен в буфер обмена в Acrobat Reader (обычно это происходит, когда документ содержит изображения и извлеченные из них тексты с распознанным текстом). Эти настройки сообщают конвертеру, необходимо сохранять такие тексты как прозрачные выбираемые тексты в результирующем HTML, чтобы имитировать поведение Acrobat Reader (иначе такие тексты обычно сохраняются как скрытые, недоступные для копирования в буфер обмена) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts) | Pdf может содержать прозрачные тексты, которые можно выбрать в буфер обмена (обычно это происходит, когда документ содержит изображения и извлеченные из них тексты, обработанные распознанным кодом). Эта настройка сообщает конвертеру, нужно ли сохранять такие тексты как Transparent выбираемые тексты в результате HTML |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages) | Получает или задает путь к каталогу, в который должны быть сохранены любые изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пуст или null , то файлы изображений (если они есть) будут сохранены вместе с другими файлами, связанными с HTML . Это ни на что не влияет, если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages) | Получает или задает путь к каталогу, в который должны быть сохранены только SVG-изображения, если они встречаются при сохранении документа в формате HTML. Если параметр пустой или null , то файлы SVG(если есть) будут сохраняться вместе с другими файлами изображений (рядом с выходным файлом) или в специальную папку для изображений (если она указана в опции SpecialImagesFolderIfAny). Ни на что не влияет если свойство CustomImageSavingStrategy было успешно использовано для обработки соответствующего файла изображения. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы) составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений , , потому что их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательный эффект. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss) | Сам PDF не содержит маркеров подчеркивания для текстов. Он эмулируется строкой, расположенной под текстом. Эта опция позволяет конвертеру попытаться угадать, что та или иная строка является подчеркиванием текста и ввести эту информацию в CSS вместо рисования или подчеркивания графически |

### Смотрите также

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPageSetOptions](../ipagesetoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->