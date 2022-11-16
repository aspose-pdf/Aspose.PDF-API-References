---
title: IDocument
second_title: Aspose.PDF для справки по Java API
description: интерфейс, представляющий PDF-документ
type: docs
weight: 433
url: /ru/java/com.aspose.pdf/idocument/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IDocument extends System.IDisposable, Closeable
```

интерфейс, представляющий PDF-документ
## Методы

| Метод | Описание |
| --- | --- |
| [afterImport()](#afterImport--) | Перечислите все зарегистрированные аннотации и вызовите AfterImport для каждой из них. |
| [bindXml(InputStream stream)](#bindXml-java.io.InputStream-) | Привязать xml к документу |
| [bindXml(String file)](#bindXml-java.lang.String-) | Привязать xml к документу |
| [bindXml(String xmlFile, String xslFile)](#bindXml-java.lang.String-java.lang.String-) | Привязать xml/xsl к документу |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Изменяет пароли к документам. |
| [check(boolean doRepair)](#check-boolean-) | Утверждает документ. |
| [close()](#close--) | Закрывает все ресурсы, используемые этим документом. |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | Преобразование документа в доступный для поиска документ. |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-) | Преобразование документа и сохранение ошибок в указанный файл. |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-) | Преобразование документа и сохранение ошибок в указанный файл. |
| [convert(PdfFormatConversionOptions options)](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Преобразование документа с использованием указанных параметров преобразования |
| [convert(OutputStream outputLogStream, PdfFormat format, int action)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) |  |
| [convert(String outputLogFileName, PdfFormat format, int action)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-) | Преобразование документа и сохранение ошибок в указанный файл. |
| [convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | Преобразование документа и сохранение ошибок в указанный файл. |
| [convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none)](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-) | Внутренний метод |
| [convertWithSkippingErrors(Document.CallBackGetHocr callback)](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-) | Преобразуйте документ в доступный для поиска документ и пропустите ошибки hochr, которые не могут быть преобразованы. |
| [decrypt()](#decrypt--) | Расшифровывает документ. |
| [dispose()](#dispose--) | Закрывает все ресурсы, используемые этим документом. |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-) | Шифрует документ. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Шифрует документ. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-int-boolean-) | Шифрует документ. |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | Экспортирует все аннотации документа в файл XFDF. |
| [flatten()](#flatten--) | Удаляет все поля из документа и вместо них помещает их значения. |
| [flatten(Form.FlattenSettings flattenSettings)](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Удаляет все поля из документа и вместо них помещает их значения. |
| [freeMemory()](#freeMemory--) | Очищает память |
| [getActions()](#getActions--) | Получает действия документа. |
| [getBackground()](#getBackground--) | Получает цвет фона документа. |
| [getCatalogValue(String key)](#getCatalogValue-java.lang.String-) | Возвращает значение элемента из словаря каталога. |
| [getCollection()](#getCollection--) | Получает коллекцию документов. |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | Получает параметры безопасности, если документ зашифрован. |
| [getDefaultCopier()](#getDefaultCopier--) | Возвращает копир, используемый для копирования страниц в этот документ. |
| [getDestinations()](#getDestinations--) | Получает коллекцию пунктов назначения. |
| [getDirection()](#getDirection--) | Получает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [getDuplex()](#getDuplex--) | Получает или задает параметр обработки режима двусторонней печати для использования при печати файла из диалогового окна печати. |
| [getEmbedStandardFonts()](#getEmbedStandardFonts--) | Свойство, которое объявляет, что документ должен включать все стандартные шрифты Type1, для которых флаг IsEmbedded установлен в значение true. |
| [getEmbeddedFiles()](#getEmbeddedFiles--) | Получает коллекцию файлов, встроенных в документ. |
| [getEnableSignatureSanitization()](#getEnableSignatureSanitization--) | Получает или задает флаг для управления очисткой полей подписи. |
| [getEngineDoc()](#getEngineDoc--) | Экземпляр IPdfDocument, используемый для доступа к внутренней структуре документа. |
| [getFileName()](#getFileName--) | Имя PDF-файла, вызвавшего этот документ |
| [getForm()](#getForm--) | Получает акроформу документа. |
| [getId()](#getId--) | Получает идентификатор. |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | Получает или устанавливает флаг игнорирования ошибок в исходных файлах. |
| [getInfo()](#getInfo--) | Получает информацию о документе. |
| [getLogicalStructure()](#getLogicalStructure--) | Получает логическую структуру документа. |
| [getMetadata()](#getMetadata--) | Метаданные документа. |
| [getMetadataStream()](#getMetadataStream--) | Возвращает необработанный поток метаданных |
| [getNamedDestinations()](#getNamedDestinations--) | Коллекция Named Destination в документе. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Получает режим страницы, определяя способ отображения документа при выходе из полноэкранного режима. |
| [getObjectById(String id)](#getObjectById-java.lang.String-) | Получает объект с указанным идентификатором в документе. |
| [getOpenAction()](#getOpenAction--) | Получает действие, выполняемое при открытии документа. |
| [getOptimizeSize()](#getOptimizeSize--) | Получает флаг оптимизации. |
| [getOutlines()](#getOutlines--) | Получает структуру документа. |
| [getPageInfo()](#getPageInfo--) | Получает информацию о странице. |
| [getPageLabels()](#getPageLabels--) | Получает метки страниц в документе. |
| [getPageLayout()](#getPageLayout--) | Получает макет страницы, который будет использоваться при открытии документа. |
| [getPageMode()](#getPageMode--) | Получает режим страницы, определяя, как документ должен отображаться при открытии. |
| [getPages()](#getPages--) | Получает коллекцию страниц документа. |
| [getPdfFormat()](#getPdfFormat--) |  |
| [getPermissions()](#getPermissions--) | Получает разрешения документа. |
| [getVersion()](#getVersion--) | Получает версию Pdf из заголовка файла Pdf. |
| [getXmpMetadata(OutputStream stream)](#getXmpMetadata-java.io.OutputStream-) | Получить метаданные XMP из документа. |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | Импорт аннотаций из файла XFDF в документ. |
| [isAbsentFontTryToSubstitute()](#isAbsentFontTryToSubstitute--) | Уведомление об отсутствующих шрифтах при обработке документов |
| [isCenterWindow()](#isCenterWindow--) | Получает флаг, указывающий, будет ли положение окна документа центрировано на экране. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией на этот шрифт. |
| [isDisplayDocTitle()](#isDisplayDocTitle--) | Получает флаг, указывающий, должна ли строка заголовка окна документа отображать заголовок документа. |
| [isEncrypted()](#isEncrypted--) | Получает зашифрованный статус документа. |
| [isFitWindow()](#isFitWindow--) | Получает флаг, указывающий, нужно ли изменять размер окна документа, чтобы он соответствовал первой отображаемой странице. |
| [isHideMenubar()](#isHideMenubar--) | Получает флаг, указывающий, следует ли скрывать строку меню, когда документ активен. |
| [isHideToolBar()](#isHideToolBar--) | Получает флаг, указывающий, должна ли быть скрыта панель инструментов, когда документ активен. |
| [isHideWindowUI()](#isHideWindowUI--) | Получает или задает флаг, указывающий, следует ли скрывать элементы пользовательского интерфейса, когда документ активен. |
| [isLinearized()](#isLinearized--) | Получает или задает значение, указывающее, является ли документ линеаризованным. |
| [isManualDisposeEnabled()](#isManualDisposeEnabled--) | По умолчанию метод сохраняет закрытые внутренние потоки и освобождает ресурсы памяти. |
| [isPdfUaCompliant()](#isPdfUaCompliant--) | Получает документ, совместимый с pdfua. |
| [isPdfaCompliant()](#isPdfaCompliant--) |  |
| [isXrefGapsAllowed()](#isXrefGapsAllowed--) | Получает или задает документ, совместимый с pdfa. |
| [optimize()](#optimize--) | Линеаризовать документ, чтобы - как можно быстрее открыть первую страницу; - отображать следующую страницу или переходить по ссылке на следующую страницу как можно быстрее; - отображать страницу постепенно по мере ее поступления, когда данные для страницы доставляются по медленному каналу (сначала отображать наиболее полезные данные); - разрешить взаимодействие с пользователем, например переход по ссылке, даже до того, как вся страница будет получена и отображена. |
| [optimizeResources()](#optimizeResources--) | Оптимизируйте ресурсы в документе: 1. |
| [optimizeResources(OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Оптимизируйте ресурсы в документе в соответствии с определенной стратегией оптимизации. |
| [processParagraphs()](#processParagraphs--) | Сохраняет документ в поток. |
| [removeMetadata()](#removeMetadata--) | Удаляет метаданные из документа. |
| [removePdfUaCompliance()](#removePdfUaCompliance--) | Удалить соответствие pdfUa из документа |
| [removePdfaCompliance()](#removePdfaCompliance--) | Удалить соответствие pdfa из документа |
| [repair()](#repair--) | Восстанавливает поврежденный документ. |
| [возобновить обновление()](#resumeUpdate--) | resumeUpdate |
| [save()](#save--) | Сохраняйте документ инкрементно (т. е. используя технику инкрементного обновления). |
| [save(OutputStream output)](#save-java.io.OutputStream-) | Сохраняет документ в поток. |
| [save(OutputStream outputStream, SaveFormat format)](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Сохранить документ |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Сохраняет документ под новым именем, задавая параметры сохранения. |
| [save(String outputFileName)](#save-java.lang.String-) | Сохраняет документ в указанный файл. |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Сохраняет документ под новым именем, задавая параметры сохранения. |
| [saveIncrementally(System.IO.Stream output)](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Поэтапно сохраняет документ PDF в указанный поток. |
| [saveIncrementally(OutputStream output)](#saveIncrementally-java.io.OutputStream-) | Поэтапно сохраняет документ PDF в указанный поток. |
| [saveIncrementally(String outputFileName)](#saveIncrementally-java.lang.String-) | Поэтапно сохраняет документ PDF в указанный поток. |
| [saveXml(String file)](#saveXml-java.lang.String-) | Сохранить документ в XML. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Отправляет определенные страницы документа на устройство для обработки документов. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Отправляет весь документ на устройство для обработки документов. |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Отправляет весь документ на устройство для обработки документов. |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Отправляет весь документ на устройство для обработки документов. |
| [setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)](#setAbsentFontTryToSubstitute-boolean-) | Установка флага установки определяемого программой шрифта в случае отсутствия шрифта. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Устанавливает цвет фона документа. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Устанавливает флаг, определяющий, будет ли положение окна документа центрировано на экране. |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | Устанавливает коллекцию документа. |
| [setConvertMetadataAndCatalogOnly(boolean value)](#setConvertMetadataAndCatalogOnly-boolean-) | Получает параметр преобразования для конвертера pdf/ua (преобразовывать только метаданные и каталог документов, если установлено значение true) |
| [setDirection(int value)](#setDirection-int-) | Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [setDisableFontLicenseVerifications(boolean value)](#setDisableFontLicenseVerifications-boolean-) | Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией на этот шрифт. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Устанавливает флаг, определяющий, должна ли строка заголовка окна документа отображать заголовок документа. |
| [setDuplex(int value)](#setDuplex-int-) | Получает или задает параметр обработки режима двусторонней печати для использования при печати файла из диалогового окна печати. |
| [setEmbedStandardFonts(boolean value)](#setEmbedStandardFonts-boolean-) | Свойство, которое объявляет, что документ должен включать все стандартные шрифты Type1, для которых флаг IsEmbedded установлен в значение true. |
| [setEnableSignatureSanitization(boolean value)](#setEnableSignatureSanitization-boolean-) | Получает или задает флаг для управления очисткой полей подписи. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Устанавливает флаг, указывающий, нужно ли изменять размер окна документа, чтобы он соответствовал первой отображаемой странице. |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | Устанавливает флаг, указывающий, должна ли строка меню быть скрыта, когда документ активен. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Установите флаг, указывающий, должна ли панель инструментов быть скрыта, когда документ активен. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Устанавливает флаг, указывающий, должны ли быть скрыты элементы пользовательского интерфейса, когда документ активен. |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLayersAdded(boolean value)](#setLayersAdded-boolean-) | Установить значение LayersAdded |
| [setLinearized(boolean value)](#setLinearized-boolean-) | Устанавливает значение, указывающее, является ли документ линеаризованным. |
| [setManualDisposeEnabled(boolean manualDisposeEnabled)](#setManualDisposeEnabled-boolean-) | По умолчанию метод save закрывает внутренние потоки и освобождает ресурсы памяти. |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | Устанавливает режим страницы, определяя, как отображать документ при выходе из полноэкранного режима. |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | Задает действие, выполняемое при открытии документа. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Устанавливает флаг оптимизации. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Устанавливает информацию о странице. |
| [setPageLayout(int value)](#setPageLayout-int-) | Задает макет страницы, который будет использоваться при открытии документа. |
| [setPageMode(int value)](#setPageMode-int-) | Устанавливает режим страницы, определяя, как документ должен отображаться при открытии. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Установить заголовок для документа PDF |
| [setXmpMetadata(InputStream stream)](#setXmpMetadata-java.io.InputStream-) | Установить метаданные XMP документа. |
| [setXrefGapsAllowed(boolean value)](#setXrefGapsAllowed-boolean-) | Получает или задает документ, совместимый с pdfa. |
| [подавлять обновление()](#suppressUpdate--) | suppressUpdate |
| [обновление страниц()](#updatePages--) | updatePages |
| [validate(OutputStream outputLogStream, PdfFormat format)](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Подтвердить документ в указанный файл. |
| [validate(String outputLogFileName, PdfFormat format)](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Подтвердить документ в указанный файл. |
### afterImport() {#afterImport--}
```
public abstract void afterImport()
```


Перечислите все зарегистрированные аннотации и вызовите AfterImport для каждой из них.

### bindXml(InputStream stream) {#bindXml-java.io.InputStream-}
```
public abstract void bindXml(InputStream stream)
```


Привязать xml к документу

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток с xml файлом |

### bindXml(String file) {#bindXml-java.lang.String-}
```
public abstract void bindXml(String file)
```


Привязать xml к документу

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | XML-файл |

### bindXml(String xmlFile, String xslFile) {#bindXml-java.lang.String-java.lang.String-}
```
public abstract void bindXml(String xmlFile, String xslFile)
```


Привязать xml/xsl к документу

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | java.lang.String | XML-файл. |
| xslFile | java.lang.String | Файл xsl, если используется XSLT. |

### changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract void changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Изменяет пароли к документам. Это действие можно выполнить только с использованием пароля владельца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |

### check(boolean doRepair) {#check-boolean-}
```
public abstract boolean check(boolean doRepair)
```


Утверждает документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doRepair | boolean | Если правда найденные проблемы будут устранены. |

**Возвращает:**
boolean - логическое значение
### close() {#close--}
```
public abstract void close()
```


Закрывает все ресурсы, используемые этим документом.

### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public abstract boolean convert(Document.CallBackGetHocr callback)
```


Преобразование документа в доступный для поиска документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Процедура обратного вызова для распознавания hocr. |

**Возвращает:**
boolean - логическое значение
### convert(Document.CallBackGetHocr callback, boolean isTestVisible) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-}
```
public abstract boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible)
```


Преобразование документа и сохранение ошибок в указанный файл.

Это позволяет показать/скрыть доступный для поиска текст на странице. Значение по умолчанию — ЛОЖЬ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Действие для объектов, которые нельзя конвертировать |
| isTestVisible | boolean | логическое значение |

**Возвращает:**
boolean - Результат операции
### convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-}
```
public abstract boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage)
```


Преобразование документа и сохранение ошибок в указанный файл.

Это позволяет показать/скрыть доступный для поиска текст на странице. Значение по умолчанию — ЛОЖЬ. Это позволяет получить исходное изображение из pdf. Значение по умолчанию — ЛОЖЬ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Действие для объектов, которые нельзя конвертировать |
| isTestVisible | boolean | логическое значение |
| isOriginalImage | boolean | логическое значение |

**Возвращает:**
boolean - Результат операции
### convert(PdfFormatConversionOptions options) {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
```
public abstract boolean convert(PdfFormatConversionOptions options)
```


Преобразование документа с использованием указанных параметров преобразования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | набор опций для преобразования документа PDF |

**Возвращает:**
boolean - Результат операции
### convert(OutputStream outputLogStream, PdfFormat format, int action) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convert(OutputStream outputLogStream, PdfFormat format, int action)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream |  |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) |  |
| action | int |  |

**Возвращает:**
логический
### convert(String outputLogFileName, PdfFormat format, int action) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convert(String outputLogFileName, PdfFormat format, int action)
```


Преобразование документа и сохранение ошибок в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Путь к файлу, в котором будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |
| action | int | Действие для объектов, которые нельзя конвертировать |

**Возвращает:**
boolean - Результат операции
### convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public abstract boolean convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
```


Преобразование документа и сохранение ошибок в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Путь к файлу, в котором будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |
| action | int | Действие для объектов, которые нельзя конвертировать |
| transparencyAction | int | Действие для объектов, замаскированных изображением |

**Возвращает:**
boolean - Результат операции
### convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none) {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none)
```


Внутренний метод

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| log | com.aspose.ms.System.IO.Stream | Внутренний объект |
| _convertTo | [PdfFormat](../../com.aspose.pdf/pdfformat) | Внутренний объект |
| none | int | Внутренний объект |

**Возвращает:**
логическое значение — внутреннее значение
### convertWithSkippingErrors(Document.CallBackGetHocr callback) {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-}
```
public abstract boolean convertWithSkippingErrors(Document.CallBackGetHocr callback)
```


Преобразуйте документ в доступный для поиска документ и пропустите ошибки hochr, которые не могут быть преобразованы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Процедура обратного вызова для распознавания hocr. |

**Возвращает:**
boolean - логическое значение
### decrypt() {#decrypt--}
```
public abstract void decrypt()
```


Расшифровывает документ. Вызовите затем Сохранить, чтобы получить расшифрованную версию документа.

### dispose() {#dispose--}
```
public abstract void dispose()
```


Закрывает все ресурсы, используемые этим документом.

Этот метод устарел, вместо него используйте close().

### encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-}
```
public abstract void encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)
```


Шифрует документ. Позвоните, затем Сохранить, чтобы получить зашифрованную версию документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Пользовательский пароль. |
| ownerPassword | java.lang.String | Пароль владельца. |
| privileges | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Права доступа к документу, подробности см. в разделе Разрешения. |
| cryptoAlgorithm | int | Криптографический алгоритм, подробности см. в CryptoAlgorithm. |
| usePdf20 | boolean | Поддержка версии 6 (расширение 8). |

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


Шифрует документ. Позвоните, затем Сохранить, чтобы получить зашифрованную версию документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Пользовательский пароль. |
| ownerPassword | java.lang.String | Пароль владельца. |
| permissions | int | Права доступа к документу, подробности см. в разделе Разрешения. |
| cryptoAlgorithm | int | Криптографический алгоритм, подробности см. в CryptoAlgorithm. |

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-int-int-boolean-}
```
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)
```


Шифрует документ. Позвоните, затем Сохранить, чтобы получить зашифрованную версию документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Пользовательский пароль. |
| ownerPassword | java.lang.String | Пароль владельца. |
| permissions | int | Права доступа к документу, подробности см. в разделе Разрешения. |
| cryptoAlgorithm | int | Криптографический алгоритм, подробности см. в CryptoAlgorithm. |
| usePdf20 | boolean | Поддержка версии 6 (расширение 8). |

### exportAnnotationsToXfdf(String fileName) {#exportAnnotationsToXfdf-java.lang.String-}
```
public abstract void exportAnnotationsToXfdf(String fileName)
```


Экспортирует все аннотации документа в файл XFDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя XFDF-файла |

### flatten() {#flatten--}
```
public abstract void flatten()
```


Удаляет все поля из документа и вместо них помещает их значения.

### flatten(Form.FlattenSettings flattenSettings) {#flatten-com.aspose.pdf.Form.FlattenSettings-}
```
public abstract void flatten(Form.FlattenSettings flattenSettings)
```


Удаляет все поля из документа и вместо них помещает их значения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | Настройки процесса выравнивания. |

### freeMemory() {#freeMemory--}
```
public abstract void freeMemory()
```


Очищает память

### getActions() {#getActions--}
```
public abstract DocumentActionCollection getActions()
```


Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получить/установить действия BeforClosing, BeforSaving и т.д.

--------------------

```
This example demonstrates how to obtain after open action of the document:

 Document document = new Document("PdfWithOpenAction.pdf");
 DocumentActions actions = document.getActions();
 com.aspose.pdf.Action afterSavingAction = actions.getAfterSaving();
```

**Возвращает:**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection) - Объект DocumentActionCollection
### getBackground() {#getBackground--}
```
public abstract Color getBackground()
```


Получает цвет фона документа.

**Возвращает:**
[Color](../../java.awt/color) - объект java.awt.Color
### getCatalogValue(String key) {#getCatalogValue-java.lang.String-}
```
public abstract Object getCatalogValue(String key)
```


Возвращает значение элемента из словаря каталога.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ предмета. |

**Возвращает:**
java.lang.Object — Значение элемента — если ключ найден успешно; в противном случае ноль.
### getCollection() {#getCollection--}
```
public abstract Collection getCollection()
```


Получает коллекцию документов.

**Возвращает:**
[Collection](../../com.aspose.pdf/collection) - Объект коллекции
### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public abstract int getCryptoAlgorithm()
```


Получает параметры безопасности, если документ зашифрован. Если документ не зашифрован, то соответствующее исключение будет вызвано в .net 1.1 или CryptoAlgorithm будет нулевым для других версий .net.

**Возвращает:**
интервал - целочисленное значение
### getDefaultCopier() {#getDefaultCopier--}
```
public abstract Copier getDefaultCopier()
```


Возвращает копир, используемый для копирования страниц в этот документ.

**Возвращает:**
[Copier](../../com.aspose.pdf/copier) - Копировальный объект
### getDestinations() {#getDestinations--}
```
public abstract DestinationCollection getDestinations()
```


Получает коллекцию пунктов назначения.

**Возвращает:**
[DestinationCollection](../../com.aspose.pdf/destinationcollection) Объект DestinationCollection
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Получает порядок чтения текста: L2R (слева направо) или R2L (справа налево).

**Возвращает:**
int - элемент направления
### getDuplex() {#getDuplex--}
```
public abstract int getDuplex()
```


Получает или задает параметр обработки режима двусторонней печати для использования при печати файла из диалогового окна печати.

**Возвращает:**
int — элемент PrintDuplex
### getEmbedStandardFonts() {#getEmbedStandardFonts--}
```
public abstract boolean getEmbedStandardFonts()
```


Свойство, которое объявляет, что документ должен включать все стандартные шрифты Type1, для которых флаг IsEmbedded установлен в значение true. Все шрифты PDF можно встроить в документ, просто установив для флага IsEmbedded значение true, но стандартные шрифты PDF Type1 являются исключением из этого правила. Встраивание стандартного шрифта Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа - EmbedStandardFonts = true; Это свойство можно установить только один раз для всех шрифтов. По умолчанию ложь.

**Возвращает:**
boolean - логическое значение
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public abstract EmbeddedFileCollection getEmbeddedFiles()
```


Получает коллекцию файлов, встроенных в документ.

**Возвращает:**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection) - Объект EmbeddedFileCollection
### getEnableSignatureSanitization() {#getEnableSignatureSanitization--}
```
public abstract boolean getEnableSignatureSanitization()
```


Получает или задает флаг для управления очисткой полей подписи. Включено по умолчанию.

**Возвращает:**
boolean - логическое значение
### getEngineDoc() {#getEngineDoc--}
```
public abstract IPdfDocument getEngineDoc()
```


Экземпляр IPdfDocument, используемый для доступа к внутренней структуре документа. Только внутренний

**Возвращает:**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument) - Объект IPdfDocument
### getFileName() {#getFileName--}
```
public abstract String getFileName()
```


Имя PDF-файла, вызвавшего этот документ

**Возвращает:**
java.lang.String — строковый объект
### getForm() {#getForm--}
```
public abstract Form getForm()
```


Получает акроформу документа.

**Возвращает:**
[Form](../../com.aspose.pdf/form) - Форма объекта
### getId() {#getId--}
```
public abstract Id getId()
```


Получает идентификатор.

**Возвращает:**
[Id](../../com.aspose.pdf/id) - Идентификатор объекта
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public abstract boolean getIgnoreCorruptedObjects()
```


Получает или устанавливает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается, за исключением случаев, когда некоторые объекты в исходных файлах повреждены, когда этот флаг установлен в false. пример: dest.Pages.Add(src.Pages); Если для этого флага установлено значение true, поврежденные объекты будут заменены пустыми значениями. По умолчанию: правда.

**Возвращает:**
boolean - логическое значение
### getInfo() {#getInfo--}
```
public abstract DocumentInfo getInfo()
```


Получает информацию о документе.

**Возвращает:**
[DocumentInfo](../../com.aspose.pdf/documentinfo) - объект DocumentInfo
### getLogicalStructure() {#getLogicalStructure--}
```
public abstract RootElement getLogicalStructure()
```


Получает логическую структуру документа.

**Возвращает:**
[RootElement](../../com.aspose.pdf/rootelement) - объект корневого элемента
### getMetadata() {#getMetadata--}
```
public abstract Metadata getMetadata()
```


Метаданные документа. (Документ PDF может включать общую информацию, такую как название документа, автора, даты создания и изменения. Такая глобальная информация о документе (в отличие от его содержания или структуры) называется метаданными и предназначена для помощи в каталогизации и поиске. для документов во внешних базах данных.)

**Возвращает:**
[Metadata](../../com.aspose.pdf/metadata) - Объект метаданных
### getMetadataStream() {#getMetadataStream--}
```
public abstract IPdfStreamAccessor getMetadataStream()
```


Возвращает необработанный поток метаданных

**Возвращает:**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) - Объект IPdfStreamAccessor
### getNamedDestinations() {#getNamedDestinations--}
```
public abstract NamedDestinationCollection getNamedDestinations()
```


Коллекция Named Destination в документе.

**Возвращает:**
[NamedDestinationCollection](../../com.aspose.pdf.nameddestinations/nameddestinationcollection) - Экземпляр NamedDestinationCollection
### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public abstract int getNonFullScreenPageMode()
```


Получает режим страницы, определяя способ отображения документа при выходе из полноэкранного режима.

**Возвращает:**
int - элемент PageMode
### getObjectById(String id) {#getObjectById-java.lang.String-}
```
public abstract Object getObjectById(String id)
```


Получает объект с указанным идентификатором в документе.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | java.lang.String | Идентификатор объекта. |

**Возвращает:**
java.lang.Object — объект с указанным идентификатором. Null, если идентификатор не найден.
### getOpenAction() {#getOpenAction--}
```
public abstract IAppointment getOpenAction()
```


Получает действие, выполняемое при открытии документа.

--------------------

```
Example demonstrates how to get CenterWindow flag:
 Document document = new Document("sample.pdf");
 IAppointment value = document.getOpenAction();
```

**Возвращает:**
[IAppointment](../../com.aspose.pdf/iappointment) - объект IAppointment
### getOptimizeSize() {#getOptimizeSize--}
```
public abstract boolean getOptimizeSize()
```


Получает флаг оптимизации. Когда страницы добавляются в документ, равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: ложь.

**Возвращает:**
boolean - логическое значение
### getOutlines() {#getOutlines--}
```
public abstract OutlineCollection getOutlines()
```


Получает структуру документа.

**Возвращает:**
[OutlineCollection](../../com.aspose.pdf/outlinecollection) - Объект OutlineCollection
### getPageInfo() {#getPageInfo--}
```
public abstract PageInfo getPageInfo()
```


Получает информацию о странице (только для генератора)

**Возвращает:**
[PageInfo](../../com.aspose.pdf/pageinfo) - Информация о странице.
### getPageLabels() {#getPageLabels--}
```
public abstract PageLabelCollection getPageLabels()
```


Получает метки страниц в документе.

**Возвращает:**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection) - Объект PageLabelCollection
### getPageLayout() {#getPageLayout--}
```
public abstract int getPageLayout()
```


Получает макет страницы, который будет использоваться при открытии документа.

**Возвращает:**
int — элемент PageLayout
### getPageMode() {#getPageMode--}
```
public abstract int getPageMode()
```


Получает режим страницы, определяя, как документ должен отображаться при открытии.

**Возвращает:**
int - элемент PageMode
### getPages() {#getPages--}
```
public abstract PageCollection getPages()
```


Получает коллекцию страниц документа. Обратите внимание, что страницы в коллекции нумеруются с 1.

--------------------

```
Example below demonstrates how to operate with the document pages:
 How to obtain number of pages and how to obtain rectangle of starting page of the document.

 Document document = new Document("sample.pdf");
 Pages pages = document.getPages();
 System.out.println("Document contains " + pages.size());
 Page page = pages.get_Item(1);
 Rectangle rect = page.getRect();
```

**Возвращает:**
[PageCollection](../../com.aspose.pdf/pagecollection) - логическое значение
### getPdfFormat() {#getPdfFormat--}
```
public abstract PdfFormat getPdfFormat()
```




**Возвращает:**
[PdfFormat](../../com.aspose.pdf/pdfformat) - Элемент PDFFormat
### getPermissions() {#getPermissions--}
```
public abstract int getPermissions()
```


Получает разрешения документа.

**Возвращает:**
интервал - целочисленное значение
### getVersion() {#getVersion--}
```
public abstract String getVersion()
```


Получает версию Pdf из заголовка файла Pdf.

**Возвращает:**
java.lang.String — строковый объект
### getXmpMetadata(OutputStream stream) {#getXmpMetadata-java.io.OutputStream-}
```
public abstract void getXmpMetadata(OutputStream stream)
```


Получить метаданные XMP из документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в котором будут храниться метаданные. |

### importAnnotationsFromXfdf(String fileName) {#importAnnotationsFromXfdf-java.lang.String-}
```
public abstract void importAnnotationsFromXfdf(String fileName)
```


Импорт аннотаций из файла XFDF в документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя XFDF-файла |

### isAbsentFontTryToSubstitute() {#isAbsentFontTryToSubstitute--}
```
public abstract boolean isAbsentFontTryToSubstitute()
```


Уведомление об отсутствующих шрифтах при обработке документов

**Возвращает:**
boolean - логическое значение
### isCenterWindow() {#isCenterWindow--}
```
public abstract boolean isCenterWindow()
```


Получает флаг, указывающий, будет ли положение окна документа центрировано на экране.

--------------------

```
Example demonstrates how to get CenterWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isCenterWindow();
```

**Возвращает:**
boolean - логическое значение
### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public abstract boolean isDisableFontLicenseVerifications()
```


Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией на этот шрифт. Например, какой-то шрифт не может быть встроен в документ PDF, если правила лицензии запрещают встраивание для этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем PDF-документе. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что лицо, установившее этот флаг, берет на себя всю ответственность за возможные нарушения лицензии/закона. Так что Он берет это на свой страх и риск. Настоятельно рекомендуется использовать этот флаг только в том случае, если вы полностью уверены, что не нарушаете закон об авторском праве.

**Возвращает:**
boolean - логическое значение По умолчанию false.
### isDisplayDocTitle() {#isDisplayDocTitle--}
```
public abstract boolean isDisplayDocTitle()
```


Получает флаг, указывающий, должна ли строка заголовка окна документа отображать заголовок документа.

--------------------

```
Example demonstrates how to get DisplayDocTitle flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isDisplayDocTitle();
```

**Возвращает:**
boolean - логическое значение
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Получает зашифрованный статус документа. Истинно, если документ зашифрован.

**Возвращает:**
boolean - логическое значение
### isFitWindow() {#isFitWindow--}
```
public abstract boolean isFitWindow()
```


Получает флаг, указывающий, нужно ли изменять размер окна документа, чтобы он соответствовал первой отображаемой странице.

--------------------

```
Example demonstrates how to get FitWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isFitWindow();
```

**Возвращает:**
boolean - логическое значение
### isHideMenubar() {#isHideMenubar--}
```
public abstract boolean isHideMenubar()
```


Получает флаг, указывающий, следует ли скрывать строку меню, когда документ активен.

--------------------

```
Example demonstrates how to get HideMenubar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideMenubar();
```

**Возвращает:**
boolean - логическое значение
### isHideToolBar() {#isHideToolBar--}
```
public abstract boolean isHideToolBar()
```


Получает флаг, указывающий, должна ли быть скрыта панель инструментов, когда документ активен.

--------------------

```
Example demonstrates how to get HideToolBar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideToolBar();
```

**Возвращает:**
boolean - логическое значение
### isHideWindowUI() {#isHideWindowUI--}
```
public abstract boolean isHideWindowUI()
```


Получает или задает флаг, указывающий, следует ли скрывать элементы пользовательского интерфейса, когда документ активен.

--------------------

```
Example demonstrates how to get HideWindowUI flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideWindowUI();
```

**Возвращает:**
boolean - логическое значение
### isLinearized() {#isLinearized--}
```
public abstract boolean isLinearized()
```


Получает или задает значение, указывающее, является ли документ линеаризованным.

**Возвращает:**
boolean - логическое значение
### isManualDisposeEnabled() {#isManualDisposeEnabled--}
```
public abstract boolean isManualDisposeEnabled()
```


По умолчанию метод сохраняет закрытые внутренние потоки и освобождает ресурсы памяти. Мы можем сделать некоторые операции и продолжить работу с документом после сохранения метода, если этот параметр ManualDispose включен.

**Возвращает:**
boolean - логическое значение. (значение по умолчанию == ложь)
### isPdfUaCompliant() {#isPdfUaCompliant--}
```
public abstract boolean isPdfUaCompliant()
```


Получает документ, совместимый с pdfua.

**Возвращает:**
boolean - логическое значение
### isPdfaCompliant() {#isPdfaCompliant--}
```
public abstract boolean isPdfaCompliant()
```




**Возвращает:**
логический
### isXrefGapsAllowed() {#isXrefGapsAllowed--}
```
public abstract boolean isXrefGapsAllowed()
```


Получает или задает документ, совместимый с pdfa.

**Возвращает:**
boolean - логическое значение
### optimize() {#optimize--}
```
public abstract void optimize()
```


Линеаризовать документ, чтобы - как можно быстрее открыть первую страницу; - отображать следующую страницу или переходить по ссылке на следующую страницу как можно быстрее; - отображать страницу постепенно по мере ее поступления, когда данные для страницы доставляются по медленному каналу (сначала отображать наиболее полезные данные); - разрешить взаимодействие с пользователем, например переход по ссылке, даже до того, как вся страница будет получена и отображена. Вызов этого метода фактически не сохраняет документ. Напротив, документ подготовлен только для оптимизированной структуры, затем вызовите Сохранить, чтобы получить оптимизированный документ.

### optimizeResources() {#optimizeResources--}
```
public abstract void optimizeResources()
```


Оптимизировать ресурсы в документе: 1. Удалены ресурсы, которые не используются на страницах документа; 2. Равные ресурсы объединены в один объект; 3. Неиспользуемые объекты удаляются.

### optimizeResources(OptimizationOptions strategy) {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
```
public abstract void optimizeResources(OptimizationOptions strategy)
```


Оптимизируйте ресурсы в документе в соответствии с определенной стратегией оптимизации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| strategy | [OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) | Стратегия оптимизации. |

### processParagraphs() {#processParagraphs--}
```
public abstract void processParagraphs()
```


Сохраняет документ в поток.

### removeMetadata() {#removeMetadata--}
```
public abstract void removeMetadata()
```


Удаляет метаданные из документа.

### removePdfUaCompliance() {#removePdfUaCompliance--}
```
public abstract void removePdfUaCompliance()
```


Удалить соответствие pdfUa из документа

### removePdfaCompliance() {#removePdfaCompliance--}
```
public abstract void removePdfaCompliance()
```


Удалить соответствие pdfa из документа

### repair() {#repair--}
```
public abstract void repair()
```


Восстанавливает поврежденный документ.

### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


возобновить обновление

### save() {#save--}
```
public abstract void save()
```


Сохраняйте документ инкрементно (т. е. используя технику инкрементного обновления).

--------------------

Чтобы сохранить документ постепенно, мы должны открыть файл документа для записи. Поэтому Document нужно инициализировать не с помощью InputStream, а с путем к файлу, как в следующем фрагменте кода: Document doc = new Document("document.pdf"); // внести некоторые изменения и постепенно сохранить документ doc.save();

В случае, когда документ был инициализирован с помощью InputStream, запись в InputStream невозможна, поэтому мы рекомендуем использовать отдельные методы «save» для сохранения документа или «saveIncrementally» для сохранения документа инкрементально.

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream output)
```


Сохраняет документ в поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | java.io.OutputStream | Поток, где будет храниться оболочка документа. |

### save(OutputStream outputStream, SaveFormat format) {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
```
public abstract void save(OutputStream outputStream, SaveFormat format)
```


Сохранить документ

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Объект OutputStream |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | СохранитьФормат значение |

### save(OutputStream outputStream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public abstract void save(OutputStream outputStream, SaveOptions options)
```


Сохраняет документ под новым именем, задавая параметры сохранения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | OutputStream, где будет храниться документ. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Сохранить параметры. |

### save(String outputFileName) {#save-java.lang.String-}
```
public abstract void save(String outputFileName)
```


Сохраняет документ в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | java.lang.String | Путь к файлу, в котором будет храниться документ. |

### save(String outputFileName, SaveOptions options) {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public abstract void save(String outputFileName, SaveOptions options)
```


Сохраняет документ под новым именем, задавая параметры сохранения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | java.lang.String | Путь к файлу, в котором будет храниться документ. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Сохранить параметры. |

### saveIncrementally(System.IO.Stream output) {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
```
public abstract void saveIncrementally(System.IO.Stream output)
```


Поэтапно сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | Объект OutputStream |

### saveIncrementally(OutputStream output) {#saveIncrementally-java.io.OutputStream-}
```
public abstract void saveIncrementally(OutputStream output)
```


Поэтапно сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | java.io.OutputStream | Объект OutputStream |

### saveIncrementally(String outputFileName) {#saveIncrementally-java.lang.String-}
```
public abstract void saveIncrementally(String outputFileName)
```


Поэтапно сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | java.lang.String | Строковое значение |

### saveXml(String file) {#saveXml-java.lang.String-}
```
public abstract void saveXml(String file)
```


Сохранить документ в XML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | XML-файл модели документа |

### sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
```
public abstract void sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)
```


Отправляет определенные страницы документа на устройство для обработки документов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Устройство документа, которое используется для обработки документа. |
| fromPage | int | Первая страница для обработки. |
| toPage | int | Последняя страница для обработки. |
| output | java.io.OutputStream | Выходной поток содержит результаты обработки страниц документа на данном устройстве. |

### sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
```
public abstract void sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)
```


Отправляет весь документ на устройство для обработки документов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Устройство документа, которое используется для обработки документа. |
| fromPage | int | Первая страница для обработки. |
| toPage | int | Последняя страница для обработки. |
| outputFileName | java.lang.String | Имя выходного файла с результатами обработки. |

### sendTo(DocumentDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
```
public abstract void sendTo(DocumentDevice device, OutputStream output)
```


Отправляет весь документ на устройство для обработки документов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Объект DocumentDevice |
| output | java.io.OutputStream | Объект OutputStream |

### sendTo(DocumentDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
```
public abstract void sendTo(DocumentDevice device, String outputFileName)
```


Отправляет весь документ на устройство для обработки документов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Устройство документа, которое используется для обработки документа. |
| outputFileName | java.lang.String | Имя выходного файла с результатами обработки. |

### setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute) {#setAbsentFontTryToSubstitute-boolean-}
```
public abstract void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```


Установка флага установки определяемого программой шрифта в случае отсутствия шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| setAbsentFontTryToSubstitute | boolean | логическое значение |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public abstract void setBackground(Color value)
```


Устанавливает цвет фона документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color | объект java.awt.Color |

### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public abstract void setCenterWindow(boolean value)
```


Устанавливает флаг, определяющий, будет ли положение окна документа центрировано на экране.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public abstract void setCollection(Collection value)
```


Устанавливает коллекцию документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) | Объект коллекции |

### setConvertMetadataAndCatalogOnly(boolean value) {#setConvertMetadataAndCatalogOnly-boolean-}
```
public abstract void setConvertMetadataAndCatalogOnly(boolean value)
```


Получает параметр преобразования для конвертера pdf/ua (преобразовывать только метаданные и каталог документов, если установлено значение true)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент направления |

### setDisableFontLicenseVerifications(boolean value) {#setDisableFontLicenseVerifications-boolean-}
```
public abstract void setDisableFontLicenseVerifications(boolean value)
```


Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией на этот шрифт. Например, какой-то шрифт не может быть встроен в документ PDF, если правила лицензии запрещают встраивание для этого шрифта. Этот флаг используется для отключения любых лицензионных ограничений для всех шрифтов в текущем PDF-документе. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что лицо, установившее этот флаг, берет на себя всю ответственность за возможные нарушения лицензии/закона. Так что Он берет это на свой страх и риск. Настоятельно рекомендуется использовать этот флаг только в том случае, если вы полностью уверены, что не нарушаете закон об авторском праве.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение По умолчанию false. |

### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public abstract void setDisplayDocTitle(boolean value)
```


Устанавливает флаг, определяющий, должна ли строка заголовка окна документа отображать заголовок документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setDuplex(int value) {#setDuplex-int-}
```
public abstract void setDuplex(int value)
```


Получает или задает параметр обработки режима двусторонней печати для использования при печати файла из диалогового окна печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PrintDuplex |

### setEmbedStandardFonts(boolean value) {#setEmbedStandardFonts-boolean-}
```
public abstract void setEmbedStandardFonts(boolean value)
```


Свойство, которое объявляет, что документ должен включать все стандартные шрифты Type1, для которых флаг IsEmbedded установлен в значение true. Все шрифты PDF можно встроить в документ, просто установив для флага IsEmbedded значение true, но стандартные шрифты PDF Type1 являются исключением из этого правила. Встраивание стандартного шрифта Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа - EmbedStandardFonts = true; Это свойство можно установить только один раз для всех шрифтов. По умолчанию ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setEnableSignatureSanitization(boolean value) {#setEnableSignatureSanitization-boolean-}
```
public abstract void setEnableSignatureSanitization(boolean value)
```


Получает или задает флаг для управления очисткой полей подписи. Включено по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public abstract void setFitWindow(boolean value)
```


Устанавливает флаг, указывающий, нужно ли изменять размер окна документа, чтобы он соответствовал первой отображаемой странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public abstract void setHideMenubar(boolean value)
```


Устанавливает флаг, указывающий, должна ли строка меню быть скрыта, когда документ активен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public abstract void setHideToolBar(boolean value)
```


Установите флаг, указывающий, должна ли панель инструментов быть скрыта, когда документ активен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public abstract void setHideWindowUI(boolean value)
```


Устанавливает флаг, указывающий, должны ли быть скрыты элементы пользовательского интерфейса, когда документ активен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public abstract void setIgnoreCorruptedObjects(boolean value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setLayersAdded(boolean value) {#setLayersAdded-boolean-}
```
public abstract void setLayersAdded(boolean value)
```


Установить значение LayersAdded

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLinearized(boolean value) {#setLinearized-boolean-}
```
public abstract void setLinearized(boolean value)
```


Устанавливает значение, указывающее, является ли документ линеаризованным.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setManualDisposeEnabled(boolean manualDisposeEnabled) {#setManualDisposeEnabled-boolean-}
```
public abstract void setManualDisposeEnabled(boolean manualDisposeEnabled)
```


По умолчанию метод save закрывает внутренние потоки и освобождает ресурсы памяти. Мы можем сделать некоторые операции и продолжить работу с документом после вызова метода сохранения, если этот параметр ManualDispose включен. Но настоятельно рекомендуется вызывать метод dispose, когда экземпляр Document больше не нужен.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| manualDisposeEnabled | boolean | логическое значение. (значение по умолчанию == ложь) |

### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public abstract void setNonFullScreenPageMode(int value)
```


Устанавливает режим страницы, определяя, как отображать документ при выходе из полноэкранного режима.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PageMode |

### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public abstract void setOpenAction(IAppointment value)
```


Задает действие, выполняемое при открытии документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | Объект IAppointment |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public abstract void setOptimizeSize(boolean value)
```


Устанавливает флаг оптимизации. Когда страницы добавляются в документ, равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public abstract void setPageInfo(PageInfo value)
```


Устанавливает информацию о странице (только для генератора).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | Объект PageInfo |

### setPageLayout(int value) {#setPageLayout-int-}
```
public abstract void setPageLayout(int value)
```


Задает макет страницы, который будет использоваться при открытии документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PageLayout |

### setPageMode(int value) {#setPageMode-int-}
```
public abstract void setPageMode(int value)
```


Устанавливает режим страницы, определяя, как документ должен отображаться при открытии.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PageMode |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String title)
```


Установить заголовок для документа PDF

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | java.lang.String | Название документа |

### setXmpMetadata(InputStream stream) {#setXmpMetadata-java.io.InputStream-}
```
public abstract void setXmpMetadata(InputStream stream)
```


Установить метаданные XMP документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий метаданные XMP. |

### setXrefGapsAllowed(boolean value) {#setXrefGapsAllowed-boolean-}
```
public abstract void setXrefGapsAllowed(boolean value)
```


Получает или задает документ, совместимый с pdfa.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


подавлять обновление

### updatePages() {#updatePages--}
```
public abstract void updatePages()
```


обновление страниц

### validate(OutputStream outputLogStream, PdfFormat format) {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
```
public abstract boolean validate(OutputStream outputLogStream, PdfFormat format)
```


Подтвердить документ в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Поток, где будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |

**Возвращает:**
boolean - Результат операции
### validate(String outputLogFileName, PdfFormat format) {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public abstract boolean validate(String outputLogFileName, PdfFormat format)
```


Подтвердить документ в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Путь к файлу, в котором будут храниться комментарии. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Формат пдф. |

**Возвращает:**
boolean - логическое значение