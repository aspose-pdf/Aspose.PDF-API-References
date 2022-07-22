---
title: Document
second_title: Aspose.PDF для справочника API .NET
description: Класс представляющий PDF-документ
type: docs
weight: 1870
url: /ru/net/aspose.pdf/document/
---
## Document class

Класс, представляющий PDF-документ

```csharp
public sealed class Document : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Document](document#constructor)() | Инициализирует пустой документ. |
| [Document](document#constructor_1)(Stream) | Инициализировать новый экземпляр документа из*input* поток. |
| [Document](document#constructor_6)(string) | Просто запустите документ, используя*filename* . Такой же как[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Инициализировать новый экземпляр документа из*input* поток. |
| [Document](document#constructor_2)(Stream, LoadOptions) | Открывает существующий документ из потока, обеспечивая необходимое преобразование для получения pdf-документа. |
| [Document](document#constructor_4)(Stream, string) | Инициализировать новый экземпляр документа из*input* поток. |
| [Document](document#constructor_7)(string, LoadOptions) | Открывает существующий документ из файла, предоставляя необходимые параметры преобразования для получения документа в формате pdf. |
| [Document](document#constructor_8)(string, string) | Инициализирует новый экземпляр[`Document`](../document) класс для работы с зашифрованным документом. |
| [Document](document#constructor_5)(Stream, string, bool) | Инициализировать новый экземпляр документа из*input* поток. |
| [Document](document#constructor_9)(string, string, bool) | Инициализирует новый экземпляр[`Document`](../document) класс для работы с зашифрованным документом. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получить/установить действия BeforClosing, BeforSaving и т.д. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Позволяет объединять содержимое страниц для оптимизации размера документа. Если используется, то разные, но дублированные страницы могут ссылаться на один и тот же объект контента . Обратите внимание, что этот режим может вызвать побочные эффекты, такие как изменение содержимого страницы при изменении другой страницы. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Получает или задает цвет фона документа. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Получает или устанавливает флаг, определяющий, будет ли положение окна документа центрировано на экране. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Получает коллекцию документов. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Получает настройки безопасности, если документ зашифрован. Если документ не зашифрован, то соответствующее исключение будет вызвано в .net 1.1 или CryptoAlgorithm будет нулевым для других версий .net. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Получает коллекцию адресатов. Устарело. Пожалуйста, используйте NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Получает или задает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией на этот шрифт. Например, какой-то шрифт не может быть встроен в документ PDF, если правила лицензии запрещают встраивание для этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем документе PDF. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что лицо, установившее этот флаг, берет на себя всю ответственность за возможные нарушения лицензии/закона. Так что он берет это на свой страх и риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете закон об авторском праве. По умолчанию ложь. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Получает или устанавливает флаг, определяющий, должна ли строка заголовка окна документа отображать заголовок документа. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Получает или задает параметр обработки режима двусторонней печати для использования при печати файла из диалогового окна печати. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Получает коллекцию файлов, встроенных в документ. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Свойство, указывающее, что документ должен включать все стандартные шрифты Type1 , для которых флаг IsEmbedded установлен в значение true. Все шрифты PDF можно встроить в документ, просто установив флаг IsEmbedded в true, но стандартные шрифты PDF Type1 являются исключением из этого правила. IsEmbedded в true для указанного шрифта, но также установите дополнительный флаг на уровне документа - EmbedStandardFonts = true; Это свойство можно установить только один раз для всех шрифтов. По умолчанию false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Получить или установить флаг, разрешающий частичную выгрузку документа из памяти. Это позволяет уменьшить использование памяти, но может отрицательно сказаться на производительности. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | Получает или устанавливает флаг для управления очисткой полей подписи. Включено по умолчанию. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Имя файла PDF, вызвавшего этот документ |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Получает или устанавливает флаг, указывающий, должно ли быть изменено окно документа, чтобы оно соответствовало первой отображаемой странице. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | Экземпляр IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form) { get; } | Получает акроформу документа. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Выдать исключение, если документ сохранится с изменениями и будет иметь подпись |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Получает или устанавливает флаг, указывающий, следует ли скрывать строку меню, когда документ активен. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Получает или устанавливает флаг, указывающий, должна ли быть скрыта панель инструментов, когда документ активен. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Получает или устанавливает флаг, указывающий, должны ли быть скрыты элементы пользовательского интерфейса, когда документ активен. |
| [Id](../../aspose.pdf/document/id) { get; } | Получает идентификатор. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Получает или устанавливает флаг игнорирования ошибок в исходных файлах. Когда страницы исходного документа копируются в конечный документ, процесс копирования останавливается с исключением , если некоторые объекты в исходных файлах повреждены, когда этот флаг установлен в false. пример: dest.Pages.Add(src.Pages); Если для этого флага установлено значение true, поврежденные объекты будут заменены пустыми значениями. По умолчанию: true. |
| [Info](../../aspose.pdf/document/info) { get; } | Получает информацию о документе. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Получает зашифрованный статус документа. Истинно, если документ зашифрован. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Получает или задает значение, указывающее, является ли документ линеаризованным. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | Получает документ в формате pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | Получает документ, совместимый с pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | Получает или задает документ, совместимый с pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Коллекция JavaScript уровня документа. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Получает логическую структуру документа. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Метаданные документа. (Документ PDF может включать общую информацию, , такую как название документа, автора, а также даты создания и изменения. Такая глобальная информация о документе (в отличие от его содержимого или структуры) называется метаданными и предназначен для помощи в каталогизации и поиске документов во внешних базах данных.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Коллекция Named Destination в документе. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Получает или задает режим страницы, определяя способ отображения документа при выходе из полноэкранного режима. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Получает или задает действие, выполняемое при открытии документа. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Получает или устанавливает флаг оптимизации. Когда страницы добавляются в документ, равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: false. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Получает структуру документа. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Получает или устанавливает информацию о странице (только для генератора) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Получает метки страниц в документе. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Получает или задает макет страницы, который будет использоваться при открытии документа. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Получает или задает режим страницы, определяя, как документ должен отображаться при открытии. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Получает или задает коллекцию страниц документа. Обратите внимание, что страницы в коллекции нумеруются с 1. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | Получает формат PDF |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Получает права доступа к документу. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | Получает доступ к содержимому TaggedPdf. |
| [Version](../../aspose.pdf/document/version) { get; } | Получает версию Pdf из заголовка файла Pdf. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Получает лицензированное состояние системы. Возвращает true, если система работает в лицензионном режиме, и false в противном случае. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | Привязать xml к документу |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | Привязать xml к документу |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | Привязать xml/xsl к документу |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | Привязать xml/xsl к документу |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | Привязать xml/xsl к документу |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Изменяет пароли документов. Это действие можно выполнить только с использованием пароля владельца. |
| [Check](../../aspose.pdf/document/check)(bool) | Проверяет документ. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Преобразовать документ и сохранить ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Преобразование документа с использованием указанных параметров преобразования |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Преобразование документа и сохранение ошибок в указанный поток. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Преобразовать документ и сохранить ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Преобразовать документ, применив Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Преобразовать документ, применив Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Преобразовать документ и сохранить ошибки в указанный файл. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Преобразовать документ и сохранить ошибки в указанный файл. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | Преобразование страницы в PNG для потока изображений DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Расшифровывает документ. Вызовите затем Сохранить, чтобы получить расшифрованную версию документа. |
| [Dispose](../../aspose.pdf/document/dispose)() | Закрывает все ресурсы, используемые этим документом. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Шифрует документ. Позвоните, затем сохраните, чтобы получить зашифрованную версию документа. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Шифрует документ. Позвоните, затем сохраните, чтобы получить зашифрованную версию документа. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Шифрует документ. Позвоните, затем сохраните, чтобы получить зашифрованную версию документа. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Экспорт всех аннотаций документа в поток. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Экспорт всех аннотаций документа в файл XFDF |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Удаляет все поля из документа и помещает вместо них их значения. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Удаляет все поля из документа и помещает вместо них их значения. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Очищает память |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Возвращает значение элемента из словаря каталога. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Получает объект с указанным идентификатором в документе. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | Получить метаданные XMP из документа. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Импорт аннотаций из потока в документ. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Импорт аннотаций из файла XFDF в документ. |
| [Optimize](../../aspose.pdf/document/optimize)() | Линеаризовать документ, чтобы — открыть первую страницу как можно быстрее; — отобразить следующую страницу или перейти по ссылке на следующую страницу как можно быстрее; — отобразить страницу постепенно по мере ее поступления при доставке данных для страницы по медленному каналу (сначала отображать наиболее полезные данные); — разрешить взаимодействие с пользователем, например переход по ссылке, даже до того, как вся страница будет получена и отображена. Вызов этого метода фактически не сохраняет документ . Напротив, документ подготовлен только для того, чтобы иметь оптимизированную структуру, вызовите затем Сохранить, чтобы получить оптимизированный документ. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Оптимизировать ресурсы в документе: 1. Удалены ресурсы, которые не используются на страницах документа; 2. Равные ресурсы объединены в один объект; 3. Неиспользуемые объекты удаляются. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Оптимизировать ресурсы в документе в соответствии с определенной стратегией оптимизации. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Обработать абзацы для генератора. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Удаляет метаданные из документа. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | Удалить соответствие pdfa из документа |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | Удалить соответствие pdfUa из документа |
| [Repair](../../aspose.pdf/document/repair)() | Восстанавливает поврежденный документ. |
| [Save](../../aspose.pdf/document/save#save)() | Сохранить документ инкрементно (т. е. используя метод инкрементного обновления). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Сохраняет документ с параметрами сохранения. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Сохраняет документ в потоке. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Сохраняет документ в указанный файл. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Сохраняет документ под новым именем вместе с форматом файла. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Сохраняет документ в поток с параметрами сохранения. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Сохраняет документ под новым именем вместе с форматом файла. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Сохраняет документ с новым именем, задавая параметры сохранения. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Сохраняет документ в поток ответов с параметрами сохранения. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Сохранить документ в формате XML. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Отправляет весь документ на устройство для обработки документов. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Отправляет весь документ на устройство для обработки документов. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Отправляет определенные страницы документа на устройство для обработки документов. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Отправляет весь документ на устройство для обработки документов. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Установить заголовок для PDF-документа |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | Установить метаданные XMP документа. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Утвердить документ в указанном файле. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Утвердить документ в указанном файле. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Утвердить документ в указанном файле. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Преобразует поток исходного формата в поток целевого формата. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Преобразует поток в исходном формате в целевой файл в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Преобразует исходный файл в исходном формате в поток в целевом формате. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Преобразует исходный файл в исходном формате в целевой файл в целевом формате. |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | Процедура обратного вызова для распознавания hocr. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | Представляет метод, который будет обрабатывать событие FontSubstitution. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Содержит функциональность для настройки fonts |

### Смотрите также

* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
