---
title: "Класс Document"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Document class. Класс, представляющий PDF‑документ"
type: docs
weight: 3900
url: /ru/net/aspose.pdf/document/
---
## Document class

Класс, представляющий PDF‑документ.

```csharp
public sealed class Document : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Document](document/#constructor)() | Инициализирует пустой документ. |
| [Document](document/#constructor_1)(PdfVersion) | Инициализирует пустой документ по версии. |
| [Document](document/#constructor_2)(Stream) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_11)(string) | Просто инициализирует Document, используя *filename*. То же самое, что [`Document`](./document/). |
| [Document](document/#constructor_6)(Stream, bool) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Открывает существующий документ из потока, предоставляя необходимые преобразования для получения pdf‑документа. |
| [Document](document/#constructor_7)(Stream, string) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_15)(string, bool) | Просто инициализирует Document, используя *filename*. То же самое, что [`Document`](./document/). |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | Инициализирует новый экземпляр Document из класса `Document` для работы с зашифрованным документом. |
| [Document](document/#constructor_12)(string, LoadOptions) | Открывает существующий документ из файла, предоставляя необходимые параметры преобразования для получения pdf‑документа. |
| [Document](document/#constructor_16)(string, string) | Инициализирует новый экземпляр Document из класса `Document` для работы с зашифрованным документом. |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_9)(Stream, string, bool) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | Инициализирует новый экземпляр Document из класса `Document` для работы с зашифрованным документом. |
| [Document](document/#constructor_18)(string, string, bool) | Инициализирует новый экземпляр Document из класса `Document` для работы с зашифрованным документом. |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | Инициализирует новый экземпляр Document из класса `Document` для работы с зашифрованным документом. |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | Инициализирует новый экземпляр Document из *input* потока. |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | Инициализирует новый экземпляр Document из класса `Document` для работы с зашифрованным документом. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Позволяет объединять содержимое страниц для оптимизации размера документа. При использовании разные, но дублированные страницы могут ссылаться на один и тот же объект содержимого. Обратите внимание, что этот режим может вызвать побочные эффекты, такие как изменение содержимого страницы при изменении другой страницы. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Получает или задаёт цвет фона документа. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Получает или задаёт флаг, указывающий, будет ли позиция окна документа центрирована на экране. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Получает коллекцию документа. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Получает настройки безопасности, если документ зашифрован. Если документ не зашифрован, то будет выброшено соответствующее исключение в .net 1.1 или CryptoAlgorithm будет null в других версиях .net. |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | Получает пользовательский обработчик безопасности. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Получает коллекцию назначений. Устарело. Пожалуйста, используйте NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Получает или задаёт порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта. Например, некоторый шрифт нельзя встроить в PDF документ, если правила лицензии отключают встраивание для этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем PDF документе. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий этот флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он делает это на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете закон об авторском праве. По умолчанию false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Получает или задаёт флаг, указывающий, должно ли заголовок окна документа отображать название документа. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Получает или задаёт параметр обработки режима двусторонней печати, используемый при печати файла из диалогового окна печати. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Получает коллекцию файлов, встроенных в документ. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Свойство, которое объявляет, что документ должен встраивать все стандартные шрифты Type1, у которых флаг IsEmbedded установлен в true. Все шрифты PDF могут быть встроены в документ простым установлением флага IsEmbedded в true, но стандартные шрифты Type1 PDF являются исключением из этого правила. Встраивание стандартных шрифтов Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа — EmbedStandardFonts = true; Это свойство можно задать только один раз для всех шрифтов. По умолчанию false. |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | Получает или задаёт значение, указывающее, следует ли включить журналирование уведомлений. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Получает или задаёт флаг, который позволяет частично выгружать документ из памяти. Это позволяет уменьшить использование памяти, но может негативно сказаться на производительности. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Получает или задаёт флаг для управления санитизацией полей подписи. Включено по умолчанию. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Имя PDF файла, который вызвал этот документ. |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Получает или задаёт флаг, указывающий, должно ли окно документа изменять размер, чтобы соответствовать первой отображаемой странице. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Экземпляр IDocumentFontUtilities. |
| [Form](../../aspose.pdf/document/form/) { get; } | Получает Acro Form документа. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Выбрасывает Exception, если документ будет сохранён с изменениями и имеет подпись. |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Получает или задаёт флаг, указывающий, должна ли строка меню быть скрыта, когда документ активен. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Получает или задаёт флаг, указывающий, должна ли панель инструментов быть скрыта, когда документ активен. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Получает или задаёт флаг, указывающий, должны ли элементы пользовательского интерфейса быть скрыты, когда документ активен. |
| [Id](../../aspose.pdf/document/id/) { get; } | Получает ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Получает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается с исключением, если некоторые объекты в исходных файлах повреждены, при условии, что этот флаг установлен в false. пример: dest.Pages.Add(src.Pages); Если этот флаг установлен в true, повреждённые объекты будут заменены пустыми значениями. По умолчанию: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Получает информацию о документе. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Получает статус шифрования документа. True, если документ зашифрован. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Получает или задаёт значение, указывающее, линейризирован ли документ. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Получает, является ли документ соответствующим pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Получает, является ли документ соответствующим pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Получает или задаёт, является ли документ соответствующим pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Коллекция JavaScript уровня документа. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Получает логическую структуру document. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Метаданные Document. (PDF document может включать общую информацию, такую как title документа, author, а также даты создания и изменения. Такая глобальная информация о документе (в отличие от его содержимого или структуры) называется метаданными и предназначена для помощи в каталогизации и поиске документов во внешних базах данных.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Коллекция Named Destination в document. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Получает или задает режим страницы, указывая, как отображать document при выходе из полноэкранного режима. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Получает или задает действие, выполняемое при открытии document. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Получает или задает флаг оптимизации. Когда страницы добавляются в document, одинаковые потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может вызвать более медленное выполнение и большие требования к памяти. Значение по умолчанию: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Получает outlines document. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Получает коллекцию Output intents в document. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Получает или задает информацию о странице. (только для генератора, не заполняется при чтении document) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Получает метки страниц в document. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Получает или задает макет страницы, который будет использоваться при открытии document. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Получает или задает режим страницы, указывая, как document должен отображаться при открытии. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Получает или задает коллекцию страниц document. Обратите внимание, что страницы нумеруются с 1 в коллекции. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Получает формат PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Получает разрешения document. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Получает или задает флаг, указывающий, следует ли использовать размер страницы PDF для выбора входного лотка бумаги. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Получает или задает параметр масштабирования страницы, который будет выбран при отображении диалогового окна печати для этого document. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Получает доступ к содержимому TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Получает версию Pdf из заголовка файла Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Получает и задает ограничение размера файла для загрузки полного файла в память. Значение задается в мегабайтах. Значение по умолчанию — 210 МБ. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Получает состояние лицензии системы. Возвращает true, если система работает в лицензированном режиме, и false в противном случае. |

## Методы

| Имя | Описание |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Объединяет documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Объединяет pdf файлы. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Объединяет documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Объединяет documents. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Привязать xml к document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Привязать xml к document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Привязать xml/xsl к document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Привязать xml/xsl к document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Привязать xml/xsl к document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Изменяет пароли документа. Это действие может быть выполнено только с использованием пароля владельца. |
| [Check](../../aspose.pdf/document/check/)(bool) | Проверяет документ. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Конвертировать документ, используя указанные параметры конверсии |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Распознаёт изображения внутри документа и добавляет hocr‑строки поверх них. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Распознаёт изображения внутри документа и добавляет hocr‑строки поверх них. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Конвертировать документ и сохранить ошибки в указанный поток. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Конвертировать документ и сохранить ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Конвертировать документ, применяя Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Конвертировать документ, применяя Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конвертировать документ и сохранить ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конвертировать документ и сохранить ошибки в указанный файл. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Конвертировать страницу в PNG для потока изображений DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Закрывает все ресурсы, используемые этим документом. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | Шифрует документ. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Шифрует документ. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | Шифрует документ. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | Шифрует документ. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Шифрует документ. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | Шифрует документ. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Экспортировать все аннотации документа в поток. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Экспортировать все аннотации документа в файл XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Удаляет все поля из документа и вместо них размещает их значения. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Удаляет все поля (и аннотации) из документа и вместо них размещает их значения. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Заменяет прозрачный контент на непрозрачные растровые и векторные графики. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Очищает память |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Возвращает значение элемента из словаря каталога. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Получает объект с указанным ID в документе. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Получить XMP‑метаданные из документа. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Проверяет, был ли текущий PDF‑документ сохранён с инкрементными обновлениями. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Импортирует аннотации из потока в документ. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Импортирует аннотации из файла XFDF в документ. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Проверяет, требует ли документ вызова метода Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Загружает файл, конвертируя его в PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Объединяет documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Объединяет pdf файлы. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Объединяет documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Объединяет documents. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Линеаризовать документ, чтобы - открыть первую страницу как можно быстрее; - отобразить следующую страницу или перейти по ссылке на следующую страницу как можно быстрее; - отображать страницу постепенно по мере поступления данных, когда данные для страницы передаются по медленному каналу (отображать наиболее полезные данные в первую очередь); - позволить взаимодействие пользователя, например переход по ссылке, выполняться даже до того, как вся страница будет получена и отображена. Вызов этого метода фактически не сохраняет документ. Напротив, документ только подготавливается к оптимизированной структуре, затем вызовите Save, чтобы получить оптимизированный документ. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Оптимизировать ресурсы в документе: 1. Ресурсы, не используемые на страницах документа, удаляются; 2. Одинаковые ресурсы объединяются в один объект; 3. Неиспользуемые объекты удаляются. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Оптимизировать ресурсы в документе в соответствии с определённой стратегией оптимизации. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Организует узлы дерева страниц в документе в сбалансированное дерево. Только если документ содержит более чем nodesNumInSubtrees объектов страниц, иначе метод ничего не делает. Не вызывайте этот метод во время итерации по элементам Pages, это может дать непредсказуемые результаты. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Обработать абзацы для генератора. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Удаляет метаданные из документа. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Удалить соответствие pdfa из документа |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Удалить соответствие pdfUa из документа |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Восстанавливает повреждённый документ. |
| [Save](../../aspose.pdf/document/save/#save)() | Сохранять документ инкрементно (т.е. используя технику инкрементного обновления). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Сохраняет документ с параметрами сохранения. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Сохраняет документ в поток. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Сохраняет документ в указанный файл. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Сохраняет документ под новым именем вместе с форматом файла. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Сохраняет документ в поток с параметрами сохранения. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Сохраняет документ под новым именем вместе с форматом файла. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Сохраняет документ под новым именем, задавая его параметры сохранения. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Сохранять документ инкрементно (т.е. используя технику инкрементного обновления). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Сохраняет документ с параметрами сохранения. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Сохраняет документ в поток. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Сохраняет документ в указанный файл. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Сохраняет документ под новым именем вместе с форматом файла. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Сохраняет документ в поток с параметрами сохранения. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Сохраняет документ под новым именем вместе с форматом файла. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Сохраняет документ под новым именем, задавая его параметры сохранения. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Сохранить документ в XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Отправляет весь документ в устройство документа для обработки. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Отправляет весь документ в устройство документа для обработки. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Отправляет определённые страницы документа в устройство документа для обработки. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Отправляет весь документ в устройство документа для обработки. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Установить заголовок для PDF‑документа |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Установить XMP‑метаданные документа. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Проверить документ и сохранить в указанный файл. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Проверить документ и сохранить в указанный файл. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Проверить документ и сохранить в указанный файл. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Преобразует поток из исходного формата в поток в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Преобразует поток из исходного формата в целевой файл в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Преобразует исходный файл из исходного формата в поток в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Преобразует исходный файл в исходном формате в файл назначения в целевом формате. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Устанавливает ограничение размера файла для загрузки полного файла в память, значение по умолчанию равно 210 МБ. |

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
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Содержит функциональность для настройки шрифтов. |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Представляет параметры для методов Merge. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Представляет параметры восстановления PDF document. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


