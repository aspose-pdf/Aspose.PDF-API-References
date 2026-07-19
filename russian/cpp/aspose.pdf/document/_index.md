---
title: "Aspose::Pdf::Document класс"
linktitle: "Document"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Document класс. Класс, представляющий PDF‑документ в C++."
type: docs
weight: 3900
url: /ru/cpp/aspose.pdf/document/
---
## Document class


Класс, представляющий PDF‑документ.

```cpp
class Document : public System::IDisposable,
                 public Aspose::Pdf::ISupportsMemoryCleanup,
                 public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Nested classes

* Class [IDocumentFontUtilities](./idocumentfontutilities/)
* Class [MergeOptions](./mergeoptions/)
* Class [OptimizationOptions](./optimizationoptions/)
* Class [RepairOptions](./repairoptions/)
## Методы

| Метод | Описание |
| --- | --- |
| [BindXml](./bindxml/)(System::String) | Привязать xml к документу. |
| [BindXml](./bindxml/)(const System::String\&, const System::String\&) | Привязать xml/xsl к документу. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Привязать xml/xsl к документу. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Xml::XmlReaderSettings\>\&) | Привязать xml/xsl к документу. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Привязать xml к документу. |
| [ChangePasswords](./changepasswords/)(const System::String\&, const System::String\&, const System::String\&) | Изменяет пароли документа. Это действие можно выполнить только с помощью пароля владельца. |
| [Check](./check/)(bool) | Проверяет документ. |
| [Convert](./convert/)(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конвертировать документ и сохранить ошибки в указанный файл. |
| [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конвертировать документ и сохранить ошибки в указанный файл. |
| [Convert](./convert/)(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Конвертировать документ и сохранить ошибки в указанный файл. |
| [Convert](./convert/)(const System::SharedPtr\<PdfFormatConversionOptions\>\&) | Конвертировать документ, используя указанные параметры конвертации. |
| [Convert](./convert/)(Document::CallBackGetHocrWithPage, bool) | Распознавать изображения внутри документа и добавлять hocr‑строки поверх него. |
| [Convert](./convert/)(Document::CallBackGetHocr, bool) | Распознавать изображения внутри документа и добавлять hocr‑строки поверх него. |
| [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Конвертировать документ и сохранить ошибки в указанный поток. |
| [Convert](./convert/)(Fixup, const System::SharedPtr\<System::IO::Stream\>\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Конвертировать документ, применяя [Fixup](../fixup/). |
| [Convert](./convert/)(Fixup, const System::String\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Конвертировать документ, применяя [Fixup](../fixup/). |
| static [Convert](./convert/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) | Конвертирует исходный файл в исходном формате в целевой файл в целевом формате. |
| static [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) | Конвертирует поток в исходном формате в целевой файл в целевом формате. |
| static [Convert](./convert/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) | Конвертирует исходный файл в исходном формате в поток в целевом формате. |
| static [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) | Конвертирует поток в исходном формате в поток в целевом формате. |
| [ConvertPageToPNGMemoryStream](./convertpagetopngmemorystream/)(const System::SharedPtr\<Page\>\&) | Конвертировать страницу в PNG для потока изображений DSR, OMR, OCR. |
| [Decrypt](./decrypt/)() | Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа. |
| [Dispose](./dispose/)() override | Закрывает все ресурсы, используемые этим документом. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) | Инициализирует новый экземпляр класса [Document](./) для работы с зашифрованным документом. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) | Инициализирует новый экземпляр класса [Document](./) для работы с зашифрованным документом. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Инициализировать новый экземпляр [Document](./) из *входного* потока. |
| [Document](./document/)(const System::String\&) | Просто инициализируйте [Document](./), используя *filename*. То же самое, что и [Document(Stream)](../). |
| [Document](./document/)(const System::String\&, bool) | Просто инициализируйте [Document](./), используя *filename*. То же самое, что и [Document(Stream)](../). |
| [Document](./document/)(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Инициализирует новый экземпляр класса [Document](./) для работы с зашифрованным документом. |
| [Document](./document/)(const System::String\&, const System::String\&) | Инициализирует новый экземпляр класса [Document](./) для работы с зашифрованным документом. |
| [Document](./document/)(const System::String\&, const System::String\&, bool) | Инициализирует новый экземпляр класса [Document](./) для работы с зашифрованным документом. |
| [Document](./document/)(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Инициализирует новый экземпляр класса [Document](./) для работы с зашифрованным документом. |
| [Document](./document/)() | Инициализирует пустой документ. |
| [Document](./document/)(PdfVersion) | Инициализирует пустой документ по версии. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Открывает существующий документ из файла, предоставляя необходимые параметры конвертации для получения PDF‑документа. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) | Открывает существующий документ из потока, предоставляя необходимые параметры конвертации для получения PDF‑документа. |
| [Encrypt](./encrypt/)(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\&) | Шифрует документ. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Шифрует документ. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Шифрует документ. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm, bool) | Шифрует документ. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) | Шифрует документ. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) | Шифрует документ. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::String\&) | Экспортирует все аннотации документа в файл XFDF. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Экспортирует все аннотации документа в поток. |
| [Flatten](./flatten/)() | Удаляет все поля из документа и вместо них размещает их значения. |
| [Flatten](./flatten/)(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) | Удаляет все поля (и аннотации) из документа и вместо них размещает их значения. |
| [FlattenTransparency](./flattentransparency/)() | Заменяет прозрачный контент на непрозрачную растровую и векторную графику. |
| [FreeMemory](./freememory/)() override | Очищает память. |
| [get_Actions](./get_actions/)() | Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д. |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() | Позволяет объединять содержимое страниц для оптимизации размера документа. При использовании разные, но дублированные страницы могут ссылаться на один и тот же объект контента. Обратите внимание, что этот режим может вызвать побочные эффекты, такие как изменение содержимого одной страницы при изменении другой. |
| [get_Background](./get_background/)() | Получает цвет фона документа. |
| [get_CenterWindow](./get_centerwindow/)() | Получает флаг, указывающий, будет ли позиция окна документа центрирована на экране. |
| [get_Collection](./get_collection/)() | Получает коллекцию документа. |
| [get_CryptoAlgorithm](./get_cryptoalgorithm/)() | Получает параметры безопасности, если документ зашифрован. Если документ не зашифрован, то соответствующее исключение будет выброшено в .net 1.1, а [CryptoAlgorithm](../cryptoalgorithm/) будет равен null в других версиях .net. |
| [get_CustomSecurityHandler](./get_customsecurityhandler/)() const | Получает пользовательский обработчик безопасности. |
| [get_Destinations](./get_destinations/)() | Получает коллекцию назначений. Устарело. Пожалуйста, используйте NamedDestinations. |
| [get_Direction](./get_direction/)() | Получает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Многие операции с шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта. Например, некоторые шрифты нельзя встроить в PDF‑документ, если правила лицензии запрещают встраивание этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем PDF‑документе. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он действует на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторское право. По умолчанию false. |
| [get_DisplayDocTitle](./get_displaydoctitle/)() | Получает флаг, указывающий, должно ли заголовок окна документа отображать название документа. |
| [get_Duplex](./get_duplex/)() | Получает параметр обработки режима двусторонней печати, используемый при печати файла из диалогового окна печати. |
| [get_EmbeddedFiles](./get_embeddedfiles/)() | Получает коллекцию файлов, встроенных в документ. |
| [get_EmbedStandardFonts](./get_embedstandardfonts/)() const | Свойство, которое объявляет, что документ должен встраивать все стандартные шрифты Type1, у которых флаг IsEmbedded установлен в true. Все шрифты PDF могут быть встроены в документ просто путем установки флага IsEmbedded в true, но стандартные шрифты PDF Type1 являются исключением из этого правила. Встраивание стандартных шрифтов Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа — EmbedStandardFonts = true; Это свойство можно задать только один раз для всех шрифтов. По умолчанию false. |
| [get_EnableNotificationLogging](./get_enablenotificationlogging/)() const | Получает значение, указывающее, следует ли включить журналирование уведомлений. |
| [get_EnableObjectUnload](./get_enableobjectunload/)() | Получает или задает флаг, который позволяет частично выгружать документ из памяти. Это позволяет уменьшить использование памяти, но может негативно сказаться на производительности. |
| [get_EnableSignatureSanitization](./get_enablesignaturesanitization/)() const | Получает флаг для управления очисткой полей подписи. Включено по умолчанию. |
| [get_FileName](./get_filename/)() | Имя PDF‑файла, вызвавшего этот документ. |
| static [get_FileSizeLimitToMemoryLoading](./get_filesizelimittomemoryloading/)() | Получает и задает ограничение размера файла для загрузки полного файла в память. Значение задаётся в мегабайтах. Значение по умолчанию — 210 МБ. |
| [get_FitWindow](./get_fitwindow/)() | Получает флаг, указывающий, должно ли окно документа изменять размер, чтобы соответствовать первой отображаемой странице. |
| [get_FontUtilities](./get_fontutilities/)() | [IDocumentFontUtilities](./idocumentfontutilities/) экземпляр. |
| [get_Form](./get_form/)() | Получает Acro Form документа. |
| [get_HandleSignatureChange](./get_handlesignaturechange/)() const | Выбрасывает исключение, если документ будет сохранён с изменениями и имеет подпись. |
| [get_HideMenubar](./get_hidemenubar/)() | Получает флаг, указывающий, следует ли скрывать строку меню, когда документ активен. |
| [get_HideToolBar](./get_hidetoolbar/)() | Получает флаг, указывающий, следует ли скрывать панель инструментов, когда документ активен. |
| [get_HideWindowUI](./get_hidewindowui/)() | Получает флаг, указывающий, следует ли скрывать элементы пользовательского интерфейса, когда документ активен. |
| [get_Id](./get_id/)() | Получает идентификатор. |
| [get_IgnoreCorruptedObjects](./get_ignorecorruptedobjects/)() | Получает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается с исключением, если некоторые объекты в исходных файлах повреждены и этот флаг установлен в false. пример: dest.Pages.Add(src.Pages); Если этот флаг установлен в true, повреждённые объекты будут заменены пустыми значениями. По умолчанию: true. |
| [get_Info](./get_info/)() | Получает информацию о документе. |
| [get_IsEncrypted](./get_isencrypted/)() | Получает статус шифрования документа. True, если документ зашифрован. |
| static [get_IsLicensed](./get_islicensed/)() | Получает состояние лицензии системы. Возвращает true, если система работает в лицензированном режиме, и false в противном случае. |
| [get_IsLinearized](./get_islinearized/)() | Получает значение, указывающее, линейризирован ли документ. |
| [get_IsPdfaCompliant](./get_ispdfacompliant/)() | Получает, соответствует ли документ стандарту PDF/A. |
| [get_IsPdfUaCompliant](./get_ispdfuacompliant/)() | Получает, соответствует ли документ стандарту PDF/UA. |
| [get_IsXrefGapsAllowed](./get_isxrefgapsallowed/)() | Получает, соответствует ли документ стандарту PDF/A. |
| [get_JavaScript](./get_javascript/)() | [Collection](../collection/) JavaScript уровня документа. |
| [get_LogicalStructure](./get_logicalstructure/)() | Получает логическую структуру документа. |
| [get_Metadata](./get_metadata/)() | [Document](./) метаданные. (PDF‑документ может включать общую информацию, такую как название документа, автор, даты создания и изменения. Такая глобальная информация о документе (в отличие от его содержимого или структуры) называется метаданными и предназначена для помощи в каталогизации и поиске документов во внешних базах данных.) |
| [get_NamedDestinations](./get_nameddestinations/)() | Коллекция [Collection](../collection/) именованных пунктов назначения в документе. |
| [get_NonFullScreenPageMode](./get_nonfullscreenpagemode/)() | Получает режим страницы, указывающий, как отображать документ при выходе из полноэкранного режима. |
| [get_OpenAction](./get_openaction/)() | Получает действие, выполняемое при открытии документа. |
| [get_OptimizeSize](./get_optimizesize/)() | Получает флаг оптимизации. Когда страницы добавляются в документ, одинаковые потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может привести к более медленному выполнению и повышенным требованиям к памяти. Значение по умолчанию: false. |
| [get_Outlines](./get_outlines/)() | Получает оглавление документа. |
| [get_OutputIntents](./get_outputintents/)() | Получает коллекцию output intents в документе. |
| [get_PageInfo](./get_pageinfo/)() | Получает информацию о странице (только для генератора, не заполняется при чтении документа). |
| [get_PageLabels](./get_pagelabels/)() | Получает метки страниц в документе. |
| [get_PageLayout](./get_pagelayout/)() | Получает макет страницы, который будет использоваться при открытии документа. |
| [get_PageMode](./get_pagemode/)() | Получает режим страницы, указывающий, как документ должен отображаться при открытии. |
| [get_Pages](./get_pages/)() | Получает коллекцию страниц документа. [Note](../note/) что страницы нумеруются с 1 в коллекции. |
| [get_PdfFormat](./get_pdfformat/)() | Получает формат PDF. |
| [get_Permissions](./get_permissions/)() | Получает разрешения документа. |
| [get_PickTrayByPdfSize](./get_picktraybypdfsize/)() | Получает флаг, указывающий, следует ли использовать размер страницы PDF для выбора входного лотка бумаги. |
| [get_PrintScaling](./get_printscaling/)() | Получает параметр масштабирования страницы, который будет выбран при отображении диалогового окна печати для этого документа. |
| [get_TaggedContent](./get_taggedcontent/)() |  |
| [get_Version](./get_version/)() | Получает версию [Pdf](../) из заголовка файла [Pdf](../). |
| [GetCatalogValue](./getcatalogvalue/)(const System::String\&) | Возвращает значение элемента из словаря каталога. |
| [GetObjectById](./getobjectbyid/)(const System::String\&) | Получает объект с указанным идентификатором в документе. |
| [GetXmpMetadata](./getxmpmetadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Получить XMP-метаданные из документа. |
| [HasIncrementalUpdate](./hasincrementalupdate/)() | Проверяет, был ли текущий PDF-документ сохранён с инкрементными обновлениями. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::String\&) | Импортирует аннотации из файла XFDF в документ. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует аннотации из потока в документ. |
| [IsRepairNeeded](./isrepairneeded/)(System::SharedPtr\<Document::RepairOptions\>\&) | Проверяет, требует ли документ вызова метода Repair. |
| [LoadFrom](./loadfrom/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Загружает файл, преобразуя его в PDF. |
| [Merge](./merge/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Объединяет документы. |
| [Merge](./merge/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::String\>\&) | Объединяет документы. |
| [Merge](./merge/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Объединяет документы. |
| [Merge](./merge/)(const System::ArrayPtr\<System::String\>\&) | Объединяет pdf‑файлы. |
| static [MergeDocuments](./mergedocuments/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::String\>\&) | Объединяет документы. |
| static [MergeDocuments](./mergedocuments/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Объединяет документы. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::String\>\&) | Объединяет pdf‑файлы. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Объединяет документы. |
| [Optimize](./optimize/)() | Линеаризует документ, чтобы. |
| [OptimizeResources](./optimizeresources/)() | Оптимизировать ресурсы в документе: |
| [OptimizeResources](./optimizeresources/)(const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\&) | Оптимизировать ресурсы в документе согласно определённой стратегии оптимизации. |
| [PageNodesToBalancedTree](./pagenodestobalancedtree/)(uint8_t) | Организует узлы дерева страниц в документе в сбалансированное дерево. Только если в документе более чем nodesNumInSubtrees объектов страниц, иначе ничего не делает. Не вызывайте этот метод во время итерации по элементам Pages, это может дать непредсказуемые результаты. |
| [ProcessParagraphs](./processparagraphs/)() | Обрабатывает абзацы для генератора. |
| [RemoveMetadata](./removemetadata/)() | Удаляет метаданные из документа. |
| [RemovePdfaCompliance](./removepdfacompliance/)() | Удалить соответствие pdfa из документа. |
| [RemovePdfUaCompliance](./removepdfuacompliance/)() | Удалить соответствие pdfUa из документа. |
| [Repair](./repair/)(System::SharedPtr\<Document::RepairOptions\>) | Восстанавливает повреждённый документ. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет документ в поток. |
| [Save](./save/)(const System::String\&) | Сохраняет документ в указанный файл. |
| [Save](./save/)() | Сохраняет документ инкрементно (т.е. используя технику инкрементного обновления). |
| [Save](./save/)(const System::SharedPtr\<SaveOptions\>\&) | Сохраняет документ с параметрами сохранения. |
| [Save](./save/)(const System::String\&, SaveFormat) | Сохраняет документ под новым именем вместе с форматом файла. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) | Сохраняет документ под новым именем вместе с форматом файла. |
| [Save](./save/)(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) | Сохраняет документ под новым именем, задавая его параметры сохранения. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) | Сохраняет документ в поток с параметрами сохранения. |
| [Save](./save/)(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) | Сохраняет документ в поток ответа с параметрами сохранения. |
| [SaveXml](./savexml/)(System::String) | Сохранить документ в XML. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Отправляет весь документ на устройство документа для обработки. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) | Отправляет определённые страницы документа на устройство документа для обработки. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) | Отправляет весь документ на устройство документа для обработки. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) | Отправляет весь документ на устройство документа для обработки. |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Позволяет объединять содержимое страниц для оптимизации размера документа. При использовании разные, но дублированные страницы могут ссылаться на один и тот же объект контента. Обратите внимание, что этот режим может вызвать побочные эффекты, такие как изменение содержимого одной страницы при изменении другой. |
| [set_Background](./set_background/)(const System::SharedPtr\<Color\>\&) | Устанавливает цвет фона документа. |
| [set_CenterWindow](./set_centerwindow/)(bool) | Устанавливает флаг, указывающий, будет ли позиция окна документа центрирована на экране. |
| [set_Collection](./set_collection/)(const System::SharedPtr\<Aspose::Pdf::Collection\>\&) | Получает коллекцию документа. |
| [set_Direction](./set_direction/)(Aspose::Pdf::Direction) | Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Многие операции с шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта. Например, некоторые шрифты нельзя встроить в PDF‑документ, если правила лицензии запрещают встраивание этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем PDF‑документе. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он действует на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторское право. По умолчанию false. |
| [set_DisplayDocTitle](./set_displaydoctitle/)(bool) | Устанавливает флаг, указывающий, должно ли заголовок окна документа отображать название документа. |
| [set_Duplex](./set_duplex/)(PrintDuplex) | Устанавливает параметр обработки двустороннего режима печати, используемый при печати файла из диалогового окна печати. |
| [set_EmbedStandardFonts](./set_embedstandardfonts/)(bool) | Свойство, которое объявляет, что документ должен встраивать все стандартные шрифты Type1, у которых флаг IsEmbedded установлен в true. Все шрифты PDF могут быть встроены в документ просто путем установки флага IsEmbedded в true, но стандартные шрифты PDF Type1 являются исключением из этого правила. Встраивание стандартных шрифтов Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа — EmbedStandardFonts = true; Это свойство можно задать только один раз для всех шрифтов. По умолчанию false. |
| [set_EnableNotificationLogging](./set_enablenotificationlogging/)(bool) | Устанавливает значение, указывающее, следует ли включить журналирование уведомлений. |
| [set_EnableObjectUnload](./set_enableobjectunload/)(bool) | Получает или задает флаг, который позволяет частично выгружать документ из памяти. Это позволяет уменьшить использование памяти, но может негативно сказаться на производительности. |
| [set_EnableSignatureSanitization](./set_enablesignaturesanitization/)(bool) | Устанавливает флаг для управления очисткой полей подписи. Включено по умолчанию. |
| static [set_FileSizeLimitToMemoryLoading](./set_filesizelimittomemoryloading/)(int32_t) | Получает и задает ограничение размера файла для загрузки полного файла в память. Значение задаётся в мегабайтах. Значение по умолчанию — 210 МБ. |
| [set_FitWindow](./set_fitwindow/)(bool) | Устанавливает флаг, указывающий, должно ли окно документа изменять размер, чтобы соответствовать первой отображаемой странице. |
| [set_HandleSignatureChange](./set_handlesignaturechange/)(bool) | Выбрасывает исключение, если документ будет сохранён с изменениями и имеет подпись. |
| [set_HideMenubar](./set_hidemenubar/)(bool) | Устанавливает флаг, указывающий, должна ли строка меню скрываться, когда документ активен. |
| [set_HideToolBar](./set_hidetoolbar/)(bool) | Устанавливает флаг, указывающий, должна ли панель инструментов скрываться, когда документ активен. |
| [set_HideWindowUI](./set_hidewindowui/)(bool) | Устанавливает флаг, указывающий, должны ли элементы пользовательского интерфейса скрываться, когда документ активен. |
| [set_IgnoreCorruptedObjects](./set_ignorecorruptedobjects/)(bool) | Устанавливает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается с исключением, если некоторые объекты в исходных файлах повреждены, при значении флага false. пример: dest.Pages.Add(src.Pages); Если флаг установлен в true, повреждённые объекты будут заменены пустыми значениями. По умолчанию: true. |
| [set_IsLinearized](./set_islinearized/)(bool) | Устанавливает значение, указывающее, линейризирован ли документ. |
| [set_IsXrefGapsAllowed](./set_isxrefgapsallowed/)(bool) | Устанавливает, является ли документ совместимым с PDF/A. |
| [set_NonFullScreenPageMode](./set_nonfullscreenpagemode/)(Aspose::Pdf::PageMode) | Устанавливает режим страницы, указывающий, как отображать документ при выходе из полноэкранного режима. |
| [set_OpenAction](./set_openaction/)(const System::SharedPtr\<Annotations::IAppointment\>\&) | Устанавливает действие, выполняемое при открытии документа. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Устанавливает флаг оптимизации. Когда страницы добавляются в документ, одинаковые потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может привести к более медленному выполнению и повышенным требованиям к памяти. Значение по умолчанию: false. |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Устанавливает информацию о странице (только для генератора, не заполняется при чтении документа). |
| [set_PageLayout](./set_pagelayout/)(Aspose::Pdf::PageLayout) | Устанавливает макет страницы, который будет использоваться при открытии документа. |
| [set_PageMode](./set_pagemode/)(Aspose::Pdf::PageMode) | Устанавливает режим страницы, указывающий, как документ должен отображаться при открытии. |
| [set_PickTrayByPdfSize](./set_picktraybypdfsize/)(bool) | Устанавливает флаг, указывающий, следует ли использовать размер PDF-страницы для выбора входного лотка бумаги. |
| [set_PrintScaling](./set_printscaling/)(Aspose::Pdf::PrintScaling) | Устанавливает параметр масштабирования страницы, который будет выбран при отображении диалогового окна печати для этого документа. |
| static [SetDefaultFileSizeLimitToMemoryLoading](./setdefaultfilesizelimittomemoryloading/)() | Устанавливает предельный размер файла для загрузки всего файла в память, значение по умолчанию равно 210 МБ. |
| [SetTitle](./settitle/)(const System::String\&) | Установить заголовок для [Pdf](../)[Document](./). |
| [SetXmpMetadata](./setxmpmetadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Установить XMP-метаданные документа. |
| [Validate](./validate/)(const System::String\&, Aspose::Pdf::PdfFormat) | Проверить документ в указанный файл. |
| [Validate](./validate/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) | Проверить документ в указанный файл. |
| [Validate](./validate/)(const System::SharedPtr\<PdfFormatConversionOptions\>\&) | Проверить документ в указанный файл. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultNodesNumInSubtrees](./defaultnodesnuminsubtrees/) |  |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [CallBackGetHocr](./callbackgethocr/) | Обратный вызов процедуры для распознавания hocr. |
| [CallBackGetHocrWithPage](./callbackgethocrwithpage/) | Обратный вызов процедуры для распознавания hocr. |
| [FontSubstitutionHandler](./fontsubstitutionhandler/) | Представляет метод, который будет обрабатывать событие FontSubstitution. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
