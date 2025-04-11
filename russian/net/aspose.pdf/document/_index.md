---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Document. Класс, представляющий PDF-документ
type: docs
weight: 3780
url: /ru/net/aspose.pdf/document/
---
## Класс Document

Класс, представляющий PDF-документ.

```csharp
public sealed class Document : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Document](document/#constructor)() | Инициализирует пустой документ. |
| [Document](document/#constructor_1)(PdfVersion) | Инициализирует пустой документ по версии. |
| [Document](document/#constructor_2)(Stream) | Инициализирует новый экземпляр Document из *входного* потока. |
| [Document](document/#constructor_7)(string) | Просто инициализирует Document, используя *имя файла*. То же самое, что и [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Инициализирует новый экземпляр Document из *входного* потока. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Открывает существующий документ из потока, предоставляя необходимые параметры для преобразования в PDF-документ. |
| [Document](document/#constructor_5)(Stream, string) | Инициализирует новый экземпляр Document из *входного* потока. |
| [Document](document/#constructor_9)(string, bool) | Просто инициализирует Document, используя *имя файла*. То же самое, что и [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Открывает существующий документ из файла, предоставляя необходимые параметры для преобразования в PDF-документ. |
| [Document](document/#constructor_10)(string, string) | Инициализирует новый экземпляр класса `Document` для работы с зашифрованным документом. |
| [Document](document/#constructor_6)(Stream, string, bool) | Инициализирует новый экземпляр Document из *входного* потока. |
| [Document](document/#constructor_11)(string, string, bool) | Инициализирует новый экземпляр класса `Document` для работы с зашифрованным документом. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Позволяет объединять содержимое страниц для оптимизации размера документа. Если используется, то разные, но дублирующиеся страницы могут ссылаться на один и тот же объект содержимого. Обратите внимание, что этот режим может вызвать побочные эффекты, такие как изменение содержимого страницы, когда изменяется другая страница. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Получает или устанавливает цвет фона документа. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Получает или устанавливает флаг, указывающий, будет ли позиция окна документа центрирована на экране. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Получает коллекцию документа. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Получает настройки безопасности, если документ зашифрован. Если документ не зашифрован, то соответствующее исключение будет вызвано в .net 1.1 или CryptoAlgorithm будет равен null для других версий .net. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Получает коллекцию назначений. Устарело. Пожалуйста, используйте NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Получает или устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Многие операции с шрифтами не могут быть выполнены, если эти операции запрещены лицензией этого шрифта. Например, некоторые шрифты не могут быть встроены в PDF-документ, если правила лицензии отключают встраивание для этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем PDF-документе. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что лицо, которое устанавливает этот флаг, берет на себя всю ответственность за возможные нарушения лицензии/закона. Поэтому он берет это на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете закон об авторском праве. По умолчанию false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Получает или устанавливает флаг, указывающий, должен ли заголовок окна документа отображать название документа. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Получает или устанавливает параметр обработки режима дуплекса печати, который будет использоваться при печати файла из диалогового окна печати. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Получает коллекцию файлов, встроенных в документ. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Свойство, которое объявляет, что документ должен встраивать все стандартные шрифты Type1, у которых установлен флаг IsEmbedded в true. Все PDF-шрифты могут быть встроены в документ просто путем установки флага IsEmbedded в true, но стандартные шрифты Type1 являются исключением из этого правила. Встраивание стандартных шрифтов Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа - EmbedStandardFonts = true; Это свойство может быть установлено только один раз для всех шрифтов. По умолчанию false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Получает или устанавливает флаг, который позволяет частично выгружать документ из памяти. Это позволяет уменьшить использование памяти, но может негативно сказаться на производительности. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Получает или устанавливает флаг для управления очисткой полей подписи. Включено по умолчанию. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Имя PDF-файла, который вызвал этот документ |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Получает или устанавливает флаг, указывающий, должно ли окно документа быть изменено по размеру, чтобы соответствовать первой отображаемой странице. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Экземпляр IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Получает Acro Form документа. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Вызывает исключение, если документ будет сохранен с изменениями и имеет подпись |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Получает или устанавливает флаг, указывающий, должен ли меню скрываться, когда документ активен. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Получает или устанавливает флаг, указывающий, должен ли панель инструментов скрываться, когда документ активен. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Получает или устанавливает флаг, указывающий, должны ли элементы пользовательского интерфейса скрываться, когда документ активен. |
| [Id](../../aspose.pdf/document/id/) { get; } | Получает ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Получает или устанавливает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается с исключением, если некоторые объекты в исходных файлах повреждены, когда этот флаг равен false. пример: dest.Pages.Add(src.Pages); Если этот флаг установлен в true, то поврежденные объекты будут заменены пустыми значениями. По умолчанию: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Получает информацию о документе. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Получает статус шифрования документа. True, если документ зашифрован. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Получает или устанавливает значение, указывающее, является ли документ линейным. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Получает, соответствует ли документ стандарту pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Получает, соответствует ли документ стандарту pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Получает или устанавливает, соответствует ли документ стандарту pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Коллекция JavaScript на уровне документа. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Получает логическую структуру документа. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Метаданные документа. (PDF-документ может включать общую информацию, такую как название документа, автор и даты создания и изменения. Такая глобальная информация о документе (в отличие от его содержимого или структуры) называется метаданными и предназначена для помощи в каталогизации и поиске документов во внешних базах данных.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Коллекция именованных назначений в документе. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Получает или устанавливает режим страницы, указывающий, как отображать документ при выходе из полноэкранного режима. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Получает или устанавливает действие, выполняемое при открытии документа. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Получает или устанавливает флаг оптимизации. Когда страницы добавляются в документ, равные потоки ресурсов в результирующем файле объединяются в один PDF-объект, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может вызвать более медленное выполнение и большие требования к памяти. Значение по умолчанию: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Получает контуры документа. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Получает коллекцию выходных намерений в документе. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Получает или устанавливает информацию о странице. (только для генератора, не заполняется при чтении документа) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Получает метки страниц в документе. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Получает или устанавливает макет страницы, который будет использоваться при открытии документа. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Получает или устанавливает режим страницы, указывающий, как документ должен отображаться при открытии. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Получает или устанавливает коллекцию страниц документа. Обратите внимание, что страницы нумеруются с 1 в коллекции. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Получает формат PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Получает разрешения документа. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Получает или устанавливает флаг, указывающий, следует ли использовать размер страницы PDF для выбора входного лотка бумаги. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Получает или устанавливает параметр масштабирования страницы, который будет выбран, когда диалоговое окно печати отображается для этого документа. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Получает доступ к содержимому TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Получает версию PDF из заголовка PDF-файла. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Получает и устанавливает предел размера файла для загрузки всего файла в память. Значение устанавливается в мегабайтах. Значение по умолчанию - 210 Мб. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Получает лицензионное состояние системы. Возвращает true, если система работает в лицензионном режиме, и false в противном случае. |

## Методы

| Имя | Описание |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Объединяет документы. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Объединяет PDF-файлы. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Объединяет документы. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Объединяет документы. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Привязывает XML к документу |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Привязывает XML к документу |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Привязывает XML/XSL к документу |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Привязывает XML/XSL к документу |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Привязывает XML/XSL к документу |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Изменяет пароли документа. Это действие можно выполнить только с использованием пароля владельца. |
| [Check](../../aspose.pdf/document/check/)(bool) | Проверяет документ. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Преобразует документ с использованием указанных параметров преобразования |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Распознает изображения внутри документа и добавляет строки hocr поверх них. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Распознает изображения внутри документа и добавляет строки hocr поверх них. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Преобразует документ и сохраняет ошибки в указанный поток. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Преобразует документ и сохраняет ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Преобразует документ, применяя Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Преобразует документ, применяя Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Преобразует документ и сохраняет ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Преобразует документ и сохраняет ошибки в указанный файл. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Преобразует страницу в PNG для DSR, OMR, потока изображений OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Закрывает все ресурсы, используемые этим документом. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Экспортирует все аннотации документа в поток. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Экспортирует все аннотации документа в файл XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Удаляет все поля из документа и помещает их значения вместо этого. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Удаляет все поля (и аннотации) из документа и помещает их значения вместо этого. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Заменяет прозрачное содержимое непроницаемой растровой и векторной графикой. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Очищает память |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Возвращает значение элемента из словаря каталога. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Получает объект с указанным ID в документе. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Получает XMP-метаданные из документа. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Проверяет, был ли текущий PDF-документ сохранен с инкрементальными обновлениями. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Импортирует аннотации из потока в документ. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Импортирует аннотации из файла XFDF в документ. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Проверяет, требует ли документ вызова метода Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Загружает файл, преобразуя его в PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Объединяет документы. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Объединяет PDF-файлы. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Объединяет документы. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Объединяет документы. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Линейно упорядочивает документ, чтобы - открыть первую страницу как можно быстрее; - отобразить следующую страницу или перейти по ссылке на следующую страницу как можно быстрее; - отображать страницу по мере поступления данных, когда данные для страницы передаются по медленному каналу (сначала отображать наиболее полезные данные); - разрешить взаимодействие пользователя, такое как переход по ссылке, даже до того, как вся страница будет получена и отображена. Вызов этого метода фактически не сохраняет документ. Напротив, документ только подготавливается к оптимизированной структуре, затем вызовите Save, чтобы получить оптимизированный документ. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Оптимизирует ресурсы в документе: 1. Ресурсы, которые не используются на страницах документа, удаляются; 2. Равные ресурсы объединяются в один объект; 3. Неиспользуемые объекты удаляются. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Оптимизирует ресурсы в документе в соответствии с определенной стратегией оптимизации. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Организует узлы дерева страниц в документе в сбалансированное дерево. Только если в документе больше, чем nodesNumInSubtrees объектов страниц, в противном случае ничего не делает. Не вызывайте этот метод во время итерации по элементам Pages, это может дать непредсказуемые результаты |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Обрабатывает абзацы для генератора. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Удаляет метаданные из документа. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Удаляет соответствие pdfa из документа |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Удаляет соответствие pdfUa из документа |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Ремонтирует поврежденный документ. |
| [Save](../../aspose.pdf/document/save/#save)() | Сохраняет документ инкрементально (т.е. с использованием техники инкрементального обновления). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Сохраняет документ с параметрами сохранения. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Сохраняет документ в поток. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Сохраняет документ в указанный файл. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Сохраняет документ с новым именем вместе с форматом файла. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Сохраняет документ в поток с параметрами сохранения. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Сохраняет документ с новым именем вместе с форматом файла. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Сохраняет документ с новым именем, устанавливая его параметры сохранения. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Сохраняет документ инкрементально (т.е. с использованием техники инкрементального обновления). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Сохраняет документ с параметрами сохранения. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Сохраняет документ в поток. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Сохраняет документ в указанный файл. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Сохраняет документ с новым именем вместе с форматом файла. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Сохраняет документ в поток с параметрами сохранения. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Сохраняет документ с новым именем вместе с форматом файла. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Сохраняет документ с новым именем, устанавливая его параметры сохранения. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Сохраняет документ в XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Отправляет весь документ на устройство документа для обработки. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Отправляет весь документ на устройство документа для обработки. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Отправляет определенные страницы документа на устройство документа для обработки. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Отправляет весь документ на устройство документа для обработки. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Устанавливает заголовок для PDF-документа |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Устанавливает XMP-метаданные документа. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Проверяет документ в указанный файл. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Проверяет документ в указанный файл. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Проверяет документ в указанный файл. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Преобразует поток в исходном формате в поток в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Преобразует поток в исходном формате в целевой файл в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Преобразует исходный файл в исходном формате в поток в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Преобразует исходный файл в исходном формате в целевой файл в целевом формате. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Устанавливает предел размера файла для загрузки всего файла в память на значение по умолчанию, равное 210 Мб. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## События

| Имя | Описание |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Происходит, когда шрифт заменяет другой шрифт в документе. |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Представляет метод, который будет обрабатывать событие FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Содержит функциональность для настройки шрифтов |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Представляет параметры для методов объединения. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Представляет параметры для ремонта PDF-документа. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)