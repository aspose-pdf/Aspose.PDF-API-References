---
title: PdfFileEditorWeb
second_title: Aspose.PDF для справки по Java API
description: Представляет класс PdfFileEditorWeb.
type: docs
weight: 40
url: /ru/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, com.aspose.pdf.facades.APdfFileEditor

**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IPdfFileEditor](../../com.aspose.pdf.facades/ipdffileeditor)
```
public final class PdfFileEditorWeb extends APdfFileEditor implements IPdfFileEditor
```

Представляет класс PdfFileEditorWeb.

Реализует операции с файлом PDF: объединение, разбиение, извлечение страниц, создание буклета и др.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileEditorWeb()](#PdfFileEditorWeb--) | PdfFileEditorВеб-конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream. |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-) | Добавляет страницы, выбранные из массива документов в portStreams. |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response)](#append-java.io.InputStream-java.io.InputStream---int-int-javax.servlet.http.HttpServletResponse-) | Добавляет документы к исходному документу и сохраняет результат в объект ответа. |
| [append(String inputFile, String portFile, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile. |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String---int-int-java.lang.String-) | Добавляет страницы, выбранные из документов portFiles. |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response)](#append-java.lang.String-java.lang.String---int-int-javax.servlet.http.HttpServletResponse-) | Добавляет документы к исходному документу и сохраняет результат в объекте HttpServletResponse. |
| [concatenate(IDocument[] src, IDocument dest)](#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-) | Объединяет документы. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Объединяет два файла. |
| [concatenate(InputStream[] inputStream, OutputStream outputStream)](#concatenate-java.io.InputStream---java.io.OutputStream-) | Объединяет файлы |
| [concatenate(InputStream[] inputStream, HttpServletResponse response)](#concatenate-java.io.InputStream---javax.servlet.http.HttpServletResponse-) | Объединяет файлы и сохраняет результат в объекте HttpServletResponse. |
| [concatenate(String firstInputFile, String secInputFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Объединяет два файла. |
| [concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. |
| [concatenate(String[] inputFiles, String outputFile)](#concatenate-java.lang.String---java.lang.String-) | Объединяет файлы в один файл. |
| [concatenate(String[] inputFiles, HttpServletResponse response)](#concatenate-java.lang.String---javax.servlet.http.HttpServletResponse-) | Объединяет файлы и сохраняет результат в объекте HttpResposnse. |
| [delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#delete-java.io.InputStream-int---java.io.OutputStream-) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response)](#delete-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | Удаляет указанные страницы из документа и сохраняет результат в объекте HttpServletResponse. |
| [delete(String inputFile, int[] pageNumber, String outputFile)](#delete-java.lang.String-int---java.lang.String-) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [delete(String inputFile, int[] pageNumber, HttpServletResponse response)](#delete-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | Удаляет указанные страницы из документа и сохраняет результат в объекте HttpServletResponse. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Извлекает страницы из входного файла, сохраняет как новый файл Pdf. |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf. |
| [extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response)](#extract-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | Извлекает указанные страницы из исходного файла и сохраняет результат в объекте HttpServletResponse. |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | Извлекает страницы из входного файла, сохраняет как новый файл Pdf. |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF. |
| [extract(String inputFile, int[] pageNumber, HttpServletResponse response)](#extract-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | Извлекает указанные страницы из исходного файла и сохраняет результат в объекте HttpServletResponse. |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | Если установлено значение true, при возникновении ошибки генерируются исключения. |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение. |
| [getClass()](#getClass--) |  |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | Если установлено значение true, потоки закрываются после операции. |
| [getConcatenationPacketSize()](#getConcatenationPacketSize--) | Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true. |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpServletResponse. |
| [getConversionLog()](#getConversionLog--) | Получает журнал процесса преобразования. |
| [getCopyLogicalStructure()](#getCopyLogicalStructure--) | Если true, то логическая структура файла копируется при выполнении конкатенации. |
| [getCopyOutlines()](#getCopyOutlines--) | Если true, контуры будут скопированы. |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. |
| [getCorruptedItems()](#getCorruptedItems--) | Массив проблем, возникших при выполнении конкатенации. |
| [getCustomProgressConcatenationHandler()](#getCustomProgressConcatenationHandler--) | Представление внутреннего обработчика событий прогресса, который работает во время конкатенации и транслирует события конкатенации внутренних стадий конкатенации во внешний код заказчика. |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | Если true, во время конкатенации выполняются добавочные обновления. |
| [getKeepActions()](#getKeepActions--) | Если правда действия будут скопированы из исходных документов. |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | Если true, то имена полей будут уникальными при объединении форм. |
| [getLastException()](#getLastException--) | Получает последнее произошедшее исключение. |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | Если true, повторяющиеся контуры объединяются. |
| [getOptimizeSize()](#getOptimizeSize--) | Получает или устанавливает флаг оптимизации. |
| [getOwnerPassword()](#getOwnerPassword--) | Получает пароль владельца, если исходный входной файл Pdf зашифрован. |
| [getPreserveUserRights()](#getPreserveUserRights--) | Если true, права пользователя первого документа применяются к объединенному документу. |
| [getRemoveSignatures()](#getRemoveSignatures--) | Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [getSaveOptions()](#getSaveOptions--) | Получает или задает параметры сохранения, когда результат сохраняется как HttpServletResponse. |
| [getUniqueSuffix()](#getUniqueSuffix--) | Получить формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. |
| [hashCode()](#hashCode--) |  |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response)](#insert-java.io.InputStream-int-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | Вставляет документ в другой документ и сохраняет результат в объект ответа. |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Вставляет страницы из другого файла в файл Pdf в позицию. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response)](#insert-java.lang.String-int-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | Вставляет содержимое файла в исходный файл и сохраняет результат в объекте HttpServletResponse. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [isUseDiskBuffer()](#isUseDiskBuffer--) | Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений. |
| [makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-) | Создайте буклет из файла PDF и сохраните его в HttpServletResponse. |
| [makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response)](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Создает буклет из исходного файла и сохраняет результат в HttpServletResponse. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream)](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Создает буклет из InputStream в outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Делает буклет из входного потока и сохраняет результат в выходной поток. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---) | Создает буклет из firstInputStream в outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---) | Создает настраиваемый буклет из firstInputStream в outputStream. |
| [makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-) | Создает буклет из исходного файла и сохраняет результат в объектах HttpServletResponse. |
| [makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response)](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Создает буклет из исходного файла и сохраняет результат в объектах HttpServletResponse. |
| [makeBooklet(String inputFile, String outputFile)](#makeBooklet-java.lang.String-java.lang.String-) | Делает буклет из входного файла в выходной файл. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Делает буклет из inputFile в outputFile. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---) | Создает настраиваемый буклет из файла firstInputFile в файл outputFile. |
| [makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-int---int---) | Создает настраиваемый буклет из файла firstInputFile в файл outputFile. |
| [makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response)](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Создает документ N-up и сохраняет результат в объекте HttpServletResponse. |
| [makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response)](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Создает документ N-up и сохраняет результат в HttpServletResponse. |
| [makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Создает документ N-Up из двух входных потоков PDF в outputStream. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Создает документ N-Up из входного потока и сохраняет результат в выходной поток. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Создает документ N-Up из первого входного потока в выходной поток. |
| [makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)](#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-) | Создает документ N-Up из нескольких входных потоков PDF в outputStream. |
| [makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response)](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Создает документ N-up и сохраняет результат в объекте HttpServletResponse. |
| [makeNUp(String inputFile, int x, int y, HttpServletResponse response)](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Создает документ N-up и сохраняет результат в HttpServletResponse. |
| [makeNUp(String inputFile, String outputFile, int x, int y)](#makeNUp-java.lang.String-java.lang.String-int-int-) | Создает документ N-Up из firstInputFile в outputFile. |
| [makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Создает документ N-Up из входного файла в outputFile. |
| [makeNUp(String firstInputFile, String secondInputFile, String outputFile)](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Создает документ N-Up из двух входных PDF-файлов в outputFile. |
| [makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)](#makeNUp-java.lang.String---java.lang.String-boolean-) | Создает документ N-Up из нескольких входных PDF-файлов в outputFile. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)](#resizeContents-com.aspose.ms.System.IO.Stream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Изменяет размер содержимого страниц в документе. |
| [resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размер содержимого страниц документа. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)](#resizeContents-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Изменяет размер содержимого страниц в документе. |
| [resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размер содержимого страниц в документе. |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | Если установлено значение true, при возникновении ошибки генерируются исключения. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение. |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | Если установлено значение true, потоки закрываются после операции. |
| [setConcatenationPacketSize(int value)](#setConcatenationPacketSize-int-) | Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpServletResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setCopyLogicalStructure(boolean value)](#setCopyLogicalStructure-boolean-) | Если true, то логическая структура файла копируется при выполнении конкатенации. |
| [setCopyOutlines(boolean value)](#setCopyOutlines-boolean-) | Если true, контуры будут скопированы. |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. |
| [setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Представление внутреннего обработчика событий прогресса, который работает во время конкатенации и транслирует события конкатенации внутренних стадий конкатенации во внешний код заказчика. |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | Если true, во время конкатенации выполняются добавочные обновления. |
| [setKeepActions(boolean value)](#setKeepActions-boolean-) | Если правда действия будут скопированы из исходных документов. |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | Если true, то имена полей будут уникальными при объединении форм. |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) |  |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | Если true, повторяющиеся контуры объединяются. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Получает или устанавливает флаг оптимизации. |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Устанавливает пароль владельца, если исходный входной файл Pdf зашифрован. |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | Если true, права пользователя первого документа применяются к объединенному документу. |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | Установите формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. |
| [setUseDiskBuffer(boolean value)](#setUseDiskBuffer-boolean-) | Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений. |
| [splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Разбивается от начала до указанного места и сохраняет переднюю часть в выходном потоке. |
| [splitFromFirst(InputStream inputStream, int location, HttpServletResponse response)](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Разбивает документ от начала до указанного места и сохраняет результат в объекте HttpServletResponse. |
| [splitFromFirst(String inputFile, int location, String outputFile)](#splitFromFirst-java.lang.String-int-java.lang.String-) | Разбивает файл Pdf с первой страницы в указанное место и сохраняет переднюю часть как новый файл. |
| [splitFromFirst(String inputFile, int location, HttpServletResponse response)](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Разделяет документ с первой страницы на место и сохраняет результат в объектах HttpServletResponse. |
| [splitToBulks(InputStream inputStream, int[][] numberOfPage)](#splitToBulks-java.io.InputStream-int-----) | Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [splitToBulks(String inputFile, int[][] numberOfPage)](#splitToBulks-java.lang.String-int-----) | Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [splitToEnd(InputStream inputStream, int location, OutputStream outputStream)](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Разбивается из указанного места и сохраняет заднюю часть как новый файловый поток. |
| [splitToEnd(InputStream inputStream, int location, HttpServletResponse response)](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Разделяется из указанного места и сохраняет заднюю часть в объекте HttpServletResponse. |
| [splitToEnd(String inputFile, int location, String outputFile)](#splitToEnd-java.lang.String-int-java.lang.String-) | Отделяется от местоположения и сохраняет заднюю часть как новый файл. |
| [splitToEnd(String inputFile, int location, HttpServletResponse response)](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Разделяется из указанного места и сохраняет заднюю часть в объекте HttpServletResponse. |
| [splitToPages(InputStream inputStream)](#splitToPages-java.io.InputStream-) | Разбивает файл Pdf на одностраничные документы. |
| [splitToPages(InputStream inputStream, String fileNameTemplate)](#splitToPages-java.io.InputStream-java.lang.String-) | Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. |
| [splitToPages(String inputFile)](#splitToPages-java.lang.String-) | Разбивает файл PDF на одностраничные документы. |
| [splitToPages(String inputFile, String fileNameTemplate)](#splitToPages-java.lang.String-java.lang.String-) | Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileEditorWeb() {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```


PdfFileEditorВеб-конструктор.

### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InputStream src = new FileInputStream("input.pdf", FileMode.Open);
  OutputStream dest = new FileOutputStream("output.pdf", FileMode.Create);
  fileEditor.addMargins(src, dest,
      //обрабатывать страницы 1, 2, 3
      new int[] { 1, 2, 3},
      //левое поле 10 единиц
      10,
      //правое поле 5 единиц
      5,
      //верхнее поле 5 единиц
      5,
      //нижнее поле 5 единиц
      5);
      dest.Close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле. |
| rightMargin | double | Правая маржа. |
| topMargin | double | Верхнее поле. |
| bottomMargin | double | Нижний край. |

**Возвращает:**
boolean - истина, если операция прошла успешно.
### addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMargins("input.pdf", "output.pdf",
      //обрабатывать страницы 1, 2, 3
      new int[] { 1, 2, 3},
      //левое поле 10 единиц
      10,
      //правое поле 5 единиц
      5,
      //верхнее поле 5 единиц
      5,
      //нижнее поле 5 единиц
      5);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле. |
| rightMargin | double | Правая маржа. |
| topMargin | double | Верхнее поле. |
| bottomMargin | double | Нижний край. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно.
### addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в процентах от исходного размера страницы.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InputStream src = new FileInputStream("input.pdf", FileMode.Open);
  OutputStream dest = new FileOutputStream("output.pdf", FileMode.Create);
  fileEditor.addMarginsPct(src, dest,
      //обрабатывать страницы 1, 2, 3
      new int[] { 1, 2, 3},
      //левое поле составляет 15% от ширины страницы
      15,
      //правое поле составляет 10% от ширины страницы
      10,
      //верхнее поле составляет 20% от ширины страницы
      20,
      //нижнее поле составляет 5% от ширины страницы
      5);
      dest.Close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле в процентах от исходного размера страницы. |
| rightMargin | double | Правое поле в процентах от исходного размера страницы. |
| topMargin | double | Верхнее поле в процентах от исходного размера страницы. |
| bottomMargin | double | Нижнее поле в процентах от исходного размера страницы. |

**Возвращает:**
boolean - истина, если действие было выполнено успешно.
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в процентах от исходного размера страницы.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMarginsPct("input.pdf", "output.pdf",
      //обрабатывать страницы 1, 2, 3
      new int[] { 1, 2, 3},
      //левое поле составляет 15% от ширины страницы
      15,
      //правое поле составляет 10% от ширины страницы
      10,
      //верхнее поле составляет 20% от ширины страницы
      20,
      //нижнее поле составляет 5% от ширины страницы
      5);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле в процентах от исходного размера страницы. |
| rightMargin | double | Правое поле в процентах от исходного размера страницы. |
| topMargin | double | Верхнее поле в процентах от исходного размера страницы. |
| bottomMargin | double | Нижнее поле в процентах от исходного размера страницы. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно
### addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [Document](../../com.aspose.pdf/document) | Исходный документ. |
| dest | [Document](../../com.aspose.pdf/document) | Документ назначения. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объектов PageBreak, описывающих места разрывов страниц. |

### addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [IDocument](../../com.aspose.pdf/idocument) | Исходный документ. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Документ назначения. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объектов PageBreak, описывающих места разрывов страниц. |

### addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.io.InputStream | Источник, который содержит исходный документ. |
| dest | java.io.OutputStream | Источник, в котором будет сохранен целевой документ. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объекта PageBreak, описывающего страницы и места, где будет добавлен разрыв страницы. |

### addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.lang.String | Путь к исходному документу. |
| dest | java.lang.String | Путь к целевому документу. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объекта PageBreak, описывающего страницы и места, где будет добавлен разрыв страницы. |

### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1,  3, 5, "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| portStream | java.io.InputStream | Страницы из файла Pdf Stream. |
| startPage | int | Страница начинается в порту File Stream. |
| endPage | int | Страница заканчивается в portFile Stream. |
| outputStream | java.io.OutputStream | Выходной файл Pdf Stream. |

**Возвращает:**
boolean - True для успеха или false.
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает страницы firstInputFile и всех документов portStreams в диапазоне от startPage до endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| portStreams | java.io.InputStream[] | Документы, из которых нужно скопировать страницы. |
| startPage | int | Страница начинается в документах portStreams. |
| endPage | int | Страница заканчивается в документах portStreams. |
| outputStream | java.io.OutputStream | Выходной поток PDF. |

**Возвращает:**
boolean - True для успеха или false.
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response) {#append-java.io.InputStream-java.io.InputStream---int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response)
```


Добавляет документы к исходному документу и сохраняет результат в объект ответа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток, содержащий исходный документ. |
| portStreams | java.io.InputStream[] | Массив потоков с добавляемыми документами. |
| startPage | int | Стартовая страница добавленной страницы. |
| endPage | int | Конечная страница добавленных страниц. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа, в котором будет сохранен документ. |

**Возвращает:**
boolean - истина, если операция прошла успешно.
### append(String inputFile, String portFile, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
```
public boolean append(String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| portFile | java.lang.String | Страницы из файла PDF. |
| startPage | int | Страница начинается в portFile. |
| endPage | int | Страница заканчивается в portFile. |
| outputFile | java.lang.String | Выходной PDF-документ. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String---int-int-java.lang.String-}
```
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


Добавляет страницы, выбранные из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", new String[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| portFiles | java.lang.String[] | Документы, из которых нужно скопировать страницы. |
| startPage | int | Страница начинается в документах portFiles. |
| endPage | int | Страница заканчивается в документах portFiles. |
| outputFile | java.lang.String | Выходной PDF-документ. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response) {#append-java.lang.String-java.lang.String---int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response)
```


Добавляет документы к исходному документу и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя файла, содержащего исходный документ. |
| portFiles | java.lang.String[] | Массив имен файлов, содержащих присоединенные документы |
| startPage | int | Стартовая страница добавленных страниц. |
| endPage | int | Конечная страница добавленных страниц. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа, в котором будет сохранен документ. |

**Возвращает:**
boolean - истина, если операция прошла успешно.
### concatenate(IDocument[] src, IDocument dest) {#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-}
```
public boolean concatenate(IDocument[] src, IDocument dest)
```


Объединяет документы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [IDocument\[\]](../../com.aspose.pdf/idocument) | Массив исходных документов. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Документ назначения. |

**Возвращает:**
boolean — Истинно, если конкатенация прошла успешно.
### concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)
```


Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 InputStream blank = new FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new InputStream[] { stream1, stream2, blank } , outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | Первый Pdf-поток. |
| secInputStream | java.io.InputStream | Второй поток PDF. |
| blankPageStream | java.io.InputStream | Поток Pdf с пустой страницей |
| outputStream | java.io.OutputStream | Выходной поток PDF. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
```


Объединяет два файла.

\*

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Stream stream1 = new FileInputStream("file1.pdf", FileMode.Open, FileAccess.Read);
 Stream stream2 = new FileInputStream("file2.pdf", FileMode.Open, FileAccess.Read);
 Stream outstream = new FileInputStream("outfile.pdf", FileMode.Create, FileAccess.Write);
 fileEditor.concatenate(stream1, stream2, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | Поток первого файла. |
| secInputStream | java.io.InputStream | Поток второго файла. |
| outputStream | java.io.OutputStream | Поток, в котором будет храниться файл результатов. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(InputStream[] inputStream, OutputStream outputStream) {#concatenate-java.io.InputStream---java.io.OutputStream-}
```
public boolean concatenate(InputStream[] inputStream, OutputStream outputStream)
```


Объединяет файлы

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new InputStream[] { stream1, stream2 } , outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | Массив потоков для объединения. |
| outputStream | java.io.OutputStream | Поток, в котором будет храниться файл результатов. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(InputStream[] inputStream, HttpServletResponse response) {#concatenate-java.io.InputStream---javax.servlet.http.HttpServletResponse-}
```
public boolean concatenate(InputStream[] inputStream, HttpServletResponse response)
```


Объединяет файлы и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | Массив потоков, содержащий файлы для объединения. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа/ |

**Возвращает:**
boolean - истина, если операция прошла успешно.
### concatenate(String firstInputFile, String secInputFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean concatenate(String firstInputFile, String secInputFile, String outputFile)
```


Объединяет два файла.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | java.lang.String | Первый файл для объединения. |
| secInputFile | java.lang.String | Второй файл для объединения. |
| outputFile | java.lang.String | Выходной файл. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)
```


Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | java.lang.String | Первый файл. |
| secInputFile | java.lang.String | Второй файл. |
| blankPageFile | java.lang.String | PDF-файл с пустой страницей. |
| outputFile | java.lang.String | Файл результата. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(String[] inputFiles, String outputFile) {#concatenate-java.lang.String---java.lang.String-}
```
public boolean concatenate(String[] inputFiles, String outputFile)
```


Объединяет файлы в один файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate(new String[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Массив файлов для объединения. |
| outputFile | java.lang.String | Имя выходного файла. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(String[] inputFiles, HttpServletResponse response) {#concatenate-java.lang.String---javax.servlet.http.HttpServletResponse-}
```
public boolean concatenate(String[] inputFiles, HttpServletResponse response)
```


Объединяет файлы и сохраняет результат в объекте HttpResposnse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Массив файлов для объединения. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа. |

**Возвращает:**
boolean - true, если конкатенация прошла успешно.
### delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#delete-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.delete(inputStream, new int[] { 2, 3 }, outputStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputStream | java.io.OutputStream | Выходной файловый поток. |

**Возвращает:**
boolean - True для успеха или false.
### delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response) {#delete-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response)
```


Удаляет указанные страницы из документа и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| pageNumber | int[] | Массив номеров страниц, которые будут удалены. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse |

**Возвращает:**
boolean — Истинно, если операция прошла успешно.
### delete(String inputFile, int[] pageNumber, String outputFile) {#delete-java.lang.String-int---java.lang.String-}
```
public boolean delete(String inputFile, int[] pageNumber, String outputFile)
```


Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к входному файлу. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputFile | java.lang.String | Путь к выходному файлу. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### delete(String inputFile, int[] pageNumber, HttpServletResponse response) {#delete-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean delete(String inputFile, int[] pageNumber, HttpServletResponse response)
```


Удаляет указанные страницы из документа и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь исходного файла. |
| pageNumber | int[] | Массив номеров страниц, которые необходимо удалить. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа, в котором будет храниться результирующий документ. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
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
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
```


Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, 1, 3, 6, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| startPage | int | Номер стартовой страницы. |
| endPage | int | Конечный номер страницы. |
| outputStream | java.io.OutputStream | Выходной файл Pdf Stream. |

**Возвращает:**
boolean - True для успеха или false.
### extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#extract-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputStream | java.io.OutputStream | Выходной файловый поток. |

**Возвращает:**
boolean - True для успеха или false.
### extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response) {#extract-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response)
```


Извлекает указанные страницы из исходного файла и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| pageNumber | int[] | Массив номеров страниц, которые будут извлечены. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### extract(String inputFile, int startPage, int endPage, String outputFile) {#extract-java.lang.String-int-int-java.lang.String-}
```
public boolean extract(String inputFile, int startPage, int endPage, String outputFile)
```


Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.extract("input.pdf", 3, 7, "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь к файлу PDF. |
| startPage | int | Номер стартовой страницы. |
| endPage | int | Конечный номер страницы. |
| outputFile | java.lang.String | Выходной путь к файлу Pdf. |

**Возвращает:**
boolean - True для успеха или false.
### extract(String inputFile, int[] pageNumber, String outputFile) {#extract-java.lang.String-int---java.lang.String-}
```
public boolean extract(String inputFile, int[] pageNumber, String outputFile)
```


Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к входному файлу. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputFile | java.lang.String | Путь к выходному файлу. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### extract(String inputFile, int[] pageNumber, HttpServletResponse response) {#extract-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean extract(String inputFile, int[] pageNumber, HttpServletResponse response)
```


Извлекает указанные страницы из исходного файла и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к исходному файлу. |
| pageNumber | int[] | Массив номеров страниц, которые будут извлечены. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - true, если страницы были извлечены успешно.
### getAllowConcatenateExceptions() {#getAllowConcatenateExceptions--}
```
public boolean getAllowConcatenateExceptions()
```


Если установлено значение true, при возникновении ошибки генерируются исключения. В противном случае исключение не генерируется, а методы возвращают false в случае сбоя.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException ( true);
```

**Возвращает:**
boolean - логическое значение
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение.

**Возвращает:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```


Если установлено значение true, потоки закрываются после операции.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setCloseConcatenatedStreams ( true);
```

**Возвращает:**
boolean - логическое значение
### getConcatenationPacketSize() {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```


Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true.

**Возвращает:**
интервал - целочисленное значение
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


Получает способ хранения содержимого при сохранении результата операции в объекте HttpServletResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
инт
### getConversionLog() {#getConversionLog--}
```
public String getConversionLog()
```


Получает журнал процесса преобразования.

**Возвращает:**
java.lang.String
### getCopyLogicalStructure() {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```


Если true, то логическая структура файла копируется при выполнении конкатенации.

**Возвращает:**
boolean - логическое значение
### getCopyOutlines() {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```


Если true, контуры будут скопированы.

**Возвращает:**
boolean - логическое значение
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```


Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted.

**Возвращает:**
int — элемент ConcatenateCorruptedFileAction
### getCorruptedItems() {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem[] getCorruptedItems()
```


Массив проблем, возникших при выполнении конкатенации. Для каждого поврежденного документа, переданного в функцию Concatenate(), создается новая запись CorruptedItem. Это свойство можно использовать, только если CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted.

--------------------

```
//объединять документы и показывать информацию о поврежденных документах
 PdfFileEditor pfe = new PdfFileEditor();
 pfe.setCorruptedFileAction( PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted);
 ```
если (pfe.getCorruptedItems().length > 0)
```
 {
 for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems())
 {
 System.out.println(item.getIndex() + " reason: " + item.getException());
 }
 }
```

**Возвращает:**
com.aspose.pdf.facades.PdfFileEditor.CorruptedItem[] - Массив PdfFileEditor.CorruptedItem
### getCustomProgressConcatenationHandler() {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```


Представление внутреннего обработчика событий прогресса, который работает во время конкатенации и транслирует события конкатенации внутренних стадий конкатенации во внешний код заказчика. В этом поле используются различные типы событий.

Простая конкатенация имеет 8 событий:
1)Все страницы скопированы
2)ДокументВстроенные файлы
3)Формы Документов
4)Контуры документа
5)Документ JavaScript
6)Логическая структура документа
7)Документконкатед.
8)Общий процент.

Параллельная конкатенация информирует о каждой конкатенации страниц и имеет 3 события:
1)Сцепление страниц
2) Пустая страница
3)Общий процент

**Возвращает:**
[ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) - Экземпляр ConcatenationProgressHandler
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```


Если true, во время конкатенации выполняются добавочные обновления.

**Возвращает:**
boolean - логическое значение
### getKeepActions() {#getKeepActions--}
```
public final boolean getKeepActions()
```


Если правда действия будут скопированы из исходных документов. Значение по умолчанию: правда.

**Возвращает:**
boolean - логическое значение
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```


Если true, то имена полей будут уникальными при объединении форм. К именам полей будут добавлены суффиксы, шаблон суффикса можно указать в свойстве UniqueSuffix.

**Возвращает:**
boolean - логическое значение
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


Получает последнее произошедшее исключение. Может использоваться для проверки причины сбоя.

```
PdfFileEditor pfe = new PdfFileEditor();
  if (!pfe.tryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
  {
     System.out.println("Error occured:");
     if (pfe.getLastException() != null)
     {
         System.out.println((pfe.getLastException().getMessage());
         if (pfe.getLastException().getInnerException() != null)
             System.out.println((pfe.getLastException().getInnerException().getMessage());
     }
  }
```

**Возвращает:**
java.lang.RuntimeException
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```


Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. В противном случае слои с одинаковыми именами будут сохранены в результирующем документе как разные слои.

**Возвращает:**
логический
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```


Если true, повторяющиеся контуры объединяются.

**Возвращает:**
boolean - логическое значение
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: ложь.

**Возвращает:**
boolean - логическое значение
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


Получает пароль владельца, если исходный входной файл Pdf зашифрован. Это свойство еще не реализовано.

**Возвращает:**
java.lang.String — строковый объект
### getPreserveUserRights() {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```


Если true, права пользователя первого документа применяются к объединенному документу. Права пользователя на все остальные документы игнорируются.

**Возвращает:**
boolean - логическое значение
### getRemoveSignatures() {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```


Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи.

**Возвращает:**
boolean - логическое значение
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


Получает или задает параметры сохранения, когда результат сохраняется как HttpServletResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions)
### getUniqueSuffix() {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```


Получить формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" будут имена: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.

**Возвращает:**
java.lang.String — строковый объект
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Вставляет страницы из другого файла во входной файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток файла PDF. |
| insertLocation | int | Вставить позицию во входной файл. |
| portStream | java.io.InputStream | Поток файла Pdf для страниц. |
| startPage | int | С какой страницы начать. |
| endPage | int | На какой странице закончить. |
| outputStream | java.io.OutputStream | Выходной поток. |

**Возвращает:**
boolean - True для успеха или false.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


Вставляет страницы из другого файла во входной файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток файла PDF. |
| insertLocation | int | Вставить позицию во входной файл. |
| portStream | java.io.InputStream | Поток файла Pdf для страниц. |
| pageNumber | int[] | Номер страницы портированного файла portFile. |
| outputStream | java.io.OutputStream | Выходной поток. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response) {#insert-java.io.InputStream-int-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response)
```


Вставляет документ в другой документ и сохраняет результат в объект ответа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток с исходным документом |
| insertLocation | int | Место, куда будет вставлен другой документ. |
| portStream | java.io.InputStream | Документ для вставки. |
| pageNumber | int[] | Массив номеров страниц во втором документе, который будет вставлен. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


Вставляет страницы из другого файла в файл Pdf в позицию.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| insertLocation | int | Позиция во входном файле. |
| portFile | java.lang.String | Файл переноса в формате PDF. |
| startPage | int | Начальная позиция в portFile. |
| endPage | int | Конечная позиция в portFile. |
| outputFile | java.lang.String | Выходной PDF-файл. |

**Возвращает:**
boolean - True для успеха или false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


Вставляет страницы из другого файла во входной файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| insertLocation | int | Вставить позицию во входной файл. |
| portFile | java.lang.String | Страницы из файла PDF. |
| pageNumber | int[] | Номер страницы портированного файла portFile. |
| outputFile | java.lang.String | Выходной PDF-файл. |

**Возвращает:**
boolean - True для успеха или false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response) {#insert-java.lang.String-int-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response)
```


Вставляет содержимое файла в исходный файл и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя исходного файла. |
| insertLocation | int | Номер страницы, на которую будет вставлен второй файл. |
| portFile | java.lang.String | Путь к файлу, который будет вставлен. |
| pageNumber | int[] | Массив номеров страниц в исходном файле, который будет вставлен. |
| response | javax.servlet.http.HttpServletResponse | Объект ответа, в котором будет храниться результат. |

**Возвращает:**
boolean - верно, что вставка прошла успешно.
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

**Возвращает:**
boolean - логическое значение
### isUseDiskBuffer() {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```


Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений.

**Возвращает:**
boolean - логическое значение
### makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response) {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)
```


Создайте буклет из файла PDF и сохраните его в HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток документов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Желаемый размер страницы. |
| leftPages | int[] | Массив номеров страниц, которые будут размещены слева. |
| rightPages | int[] | Массив номеров страниц, которые будут заменены справа. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response) {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response)
```


Создает буклет из исходного файла и сохраняет результат в HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток документов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Желаемый размер страницы в выходном файле. |
| response | javax.servlet.http.HttpServletResponse | Объект Respose, в котором будут сохранены результаты. |

**Возвращает:**
boolean - true, если буклет был построен успешно.
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream)
```


Создает буклет из InputStream в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной pdf-поток. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


Делает буклет из входного потока и сохраняет результат в выходной поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)
```


Создает буклет из firstInputStream в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |
| leftPages | int[] | Левые страницы. |
| rightPages | int[] | Правильные страницы. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)
```


Создает настраиваемый буклет из firstInputStream в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |
| leftPages | int[] | Левые страницы. |
| rightPages | int[] | Правильные страницы. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response) {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)
```


Создает буклет из исходного файла и сохраняет результат в объектах HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к исходному файлу. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Желаемый размер страницы. |
| leftPages | int[] | Массив номеров страниц для размещения слева. |
| rightPages | int[] | Массив номеров страниц, которые должны быть размещены справа. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response) {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response)
```


Создает буклет из исходного файла и сохраняет результат в объектах HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к исходному файлу. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Желаемый размер страницы в выходном файле. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean — Истинно, если операция прошла успешно.
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
public boolean makeBooklet(String inputFile, String outputFile)
```


Делает буклет из входного файла в выходной файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize)
```


Делает буклет из inputFile в outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean — Истинно, если операция прошла успешно.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)
```


Создает настраиваемый буклет из файла firstInputFile в файл outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |
| leftPages | int[] | Левые страницы. |
| rightPages | int[] | Правильные страницы. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)
```


Создает настраиваемый буклет из файла firstInputFile в файл outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| leftPages | int[] | Левые страницы буклета. |
| rightPages | int[] | Правые страницы буклета. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response) {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response)
```


Создает документ N-up и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы в файле результатов. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response) {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response)
```


Создает документ N-up и сохраняет результат в HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток входного документа. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse, где будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
```


Создает документ N-Up из двух входных потоков PDF в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream input1 = new FileInputStream("input1.pdf");
 InputStream input2 = new FileInputStream("input2.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(input1, input2, output);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | первый входной поток. |
| secondInputStream | java.io.InputStream | второй входной поток. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)
```


Создает документ N-Up из входного потока и сохраняет результат в выходной поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной pdf-поток. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


Создает документ N-Up из первого входного потока в выходной поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной pdf-поток. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
public boolean makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


Создает документ N-Up из нескольких входных потоков PDF в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые объединяются со страницами во входных потоках с тем же номером страницы. Многостраничные страницы складываются горизонтально, если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("input1.pdf");
 InputStream stream2 = new FileInputStream("input2.pdf");
 InputStream stream3 = new FileInputStream("input3.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | Входные потоки Pdf. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |
| isSidewise | boolean | Сложенный путь, верно для горизонтального и ложного для вертикального |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response) {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response)
```


Создает документ N-up и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к исходному файлу. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы в файле результатов. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeNUp(String inputFile, int x, int y, HttpServletResponse response) {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(String inputFile, int x, int y, HttpServletResponse response)
```


Создает документ N-up и сохраняет результат в HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя исходного файла. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y)
```


Создает документ N-Up из firstInputFile в outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


Создает документ N-Up из входного файла в outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean makeNUp(String firstInputFile, String secondInputFile, String outputFile)
```


Создает документ N-Up из двух входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла, а другая из второго входного файла. Две страницы сложены горизонтально.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | java.lang.String | первый входной файл. |
| secondInputFile | java.lang.String | второй входной файл. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
public boolean makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)
```


Создает документ N-Up из нескольких входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые объединяются со страницами во входных файлах с тем же номером страницы. Несколько страниц складываются горизонтально, если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Входные PDF-файлы. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| isSidewise | boolean | Нагроможденный путь, верный для горизонтали и ложный для вертикали. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response) {#resizeContents-com.aspose.ms.System.IO.Stream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
```
public boolean resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)
```


Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | com.aspose.ms.System.IO.Stream | Поток исходного файла. |
| pages | int[] | Массив страниц, размер которых нужно изменить. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Параметры изменения размера. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором сохраняется результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)
```


Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Document src = new Document("input.pdf");
 Document dest = new Document();
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //левое поле = 10% ширины страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
     null,
     //правое поле составляет 10% страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //верхнее поле = 10% высоты
     PdfFileEditor.ContentsResizeValue.percents(10),
     //высота нового содержимого рассчитывается автоматически (аналогично ширине)
     null,
     //нижняя маржа 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, parameters);
 dest.save("output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Исходный документ. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Параметры изменения размера. |

### resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Document doc = new Document("input.pdf");
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //левое поле = 10% ширины страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
     null,
     //правое поле составляет 10% страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //верхнее поле = 10% высоты
     PdfFileEditor.ContentsResizeValue.percents(10),
     //высота нового содержимого рассчитывается автоматически (аналогично ширине)
     null,
     //нижняя маржа 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, new int[] { 1, 2,.3}, parameters);
 doc.save("output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Исходный документ. |
| pages | int[] | Список индексов страниц. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Параметры изменения размера. |

### resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Изменяет размер содержимого страниц документа.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new fileOutputStream("output.pdf");
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
 //левое поле = 10% ширины страницы
 PdfFileEditor.ContentsResizeValue.percents(10),
 //ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
 null,
 //правое поле составляет 10% страницы
 PdfFileEditor.ContentsResizeValue.percents(10),
 //верхнее поле = 10% высоты
 PdfFileEditor.ContentsResizeValue.percents(10),
 //высота нового содержимого рассчитывается автоматически (аналогично ширине)
 null,
 //нижняя маржа 10%
 PdfFileEditor.ContentsResizeValue.percents(10)
 );
 fileEditor.resizeContents(src, dest, new int[] { 1, 2, 3}, parameters);
 dest.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток с исходным документом. |
| destination | java.io.OutputStream | Потоковая передача с целевым документом. |
| pages | int[] | Массив индексов страниц. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Параметры изменения размера. |

**Возвращает:**
boolean — возвращает true в случае успеха.
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents(src, dest,
 //изменить размер всех страниц документа
 null,
 //ширина нового содержимого = 200
 200,
 //высота нового содержимого = 300
 300);
 // остальная часть страницы будет пустой
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

**Возвращает:**
boolean - True, если изменение размера прошло успешно.
### resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response) {#resizeContents-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
```
public boolean resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)
```


Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному файлу. |
| pages | int[] | Массив страниц, размер которых нужно изменить. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Параметры изменения размера. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором сохраняется результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //левое поле = 10% ширины страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
     null,
     //правое поле составляет 10% страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //верхнее поле = 10% высоты
     PdfFileEditor.ContentsResizeValue.percents(10),
     //высота нового содержимого рассчитывается автоматически (аналогично ширине)
     null,
     //нижняя маржа 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2,.3}, parameters);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь к целевому документу. |
| pages | int[] | Массив индексов страниц (индекс страницы начинается с 1). |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Параметры изменения размера страницы. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно.
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf",
 //изменить размер всех страниц документа
 null,
 //ширина нового содержимого = 200
 200,
 //высота нового содержимого = 300
 300);
 // остальная часть страницы будет пустой
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно.
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Размер нового содержимого указывается в процентах.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct(src, dest,
 //изменить размер всех страниц документа
 null,
 //ширина нового содержимого = 60% от исходного размера
 60,
 //высота нового содержимого = 60% от исходного размера
 60);
 //Остальная часть страницы будет пустой (поля страницы). Размер левого и правого полей (100% - 60%) / 2 = 20%
 // То же самое для верхнего и нижнего полей.
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в процентах. |
| newHeight | double | Новая высота содержимого страницы в процентах. |

**Возвращает:**
boolean - true, если размер изменен успешно.
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Размер нового содержимого указывается в процентах.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizePct("input.pdf", "output.pdf",
 //изменить размер всех страниц документа
 null,
 //ширина нового содержимого = 60% от исходного размера
 60,
 //высота нового содержимого = 60% от исходного размера
 60);
 //Остальная часть страницы будет пустой (поля страницы). Размер левого и правого полей (100% - 60%) / 2 = 20%
 // То же самое для верхнего и нижнего полей.
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в процентах. |
| newHeight | double | Новая высота содержимого страницы в процентах. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно.
### resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)
```


Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля. Нормализация помогает избежать неожиданного поведения несгруппированного сохраненного состояния содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Экземпляр документа |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Экземпляр ContentsResizeParameters |

### resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля. Нормализация помогает избежать неожиданного поведения несгруппированного сохраненного состояния содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Экземпляр документа |
| pages | int[] | массив значений int |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Экземпляр ContentsResizeParameters |

### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public void setAllowConcatenateExceptions(boolean value)
```


Если установлено значение true, при возникновении ошибки генерируются исключения. В противном случае исключение не генерируется, а методы возвращают false в случае сбоя.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException ( true);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | Логическое значение |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


Задает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```


Если установлено значение true, потоки закрываются после операции.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setCloseConcatenatedStreams ( true);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setConcatenationPacketSize(int value) {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```


Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpServletResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | Элемент PdfFormat |

### setCopyLogicalStructure(boolean value) {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```


Если true, то логическая структура файла копируется при выполнении конкатенации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCopyOutlines(boolean value) {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```


Если true, контуры будут скопированы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```


Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler) {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
```
public void setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)
```


Представление внутреннего обработчика событий прогресса, который работает во время конкатенации и транслирует события конкатенации внутренних стадий конкатенации во внешний код заказчика. В этом поле используются различные типы событий.

Простая конкатенация имеет 8 событий:
1)Все страницы скопированы
2)ДокументВстроенные файлы
3)Формы Документов
4)Контуры документа
5)Документ JavaScript
6)Логическая структура документа
7)Документконкатед.
8)Общий процент.

Параллельная конкатенация информирует о каждой конкатенации страниц и имеет 3 события:
1)Сцепление страниц
2) Пустая страница
3)Общий процент

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customProgressConcatenationHandler | [ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) | Экземпляр ConcatenationProgressHandler |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```


Если true, во время конкатенации выполняются добавочные обновления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeepActions(boolean value) {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```


Если правда действия будут скопированы из исходных документов. Значение по умолчанию: правда.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```


Если true, то имена полей будут уникальными при объединении форм. К именам полей будут добавлены суффиксы, шаблон суффикса можно указать в свойстве UniqueSuffix.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```


Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. В противном случае слои с одинаковыми именами будут сохранены в результирующем документе как разные слои.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```


Если true, повторяющиеся контуры объединяются.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


Устанавливает пароль владельца, если исходный входной файл Pdf зашифрован. Это свойство еще не реализовано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```


Если true, права пользователя первого документа применяются к объединенному документу. Права пользователя на все остальные документы игнорируются.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```


Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Задает параметры сохранения, когда результат сохраняется как HttpServletResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | логическое значение |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public void setUniqueSuffix(String value)
```


Установите формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" будут имена: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.

--------------------

```
PdfFileEditor ed = new PdfFileEditor();
   ed.setUniqueSuffix ( "_%NUM%");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setUseDiskBuffer(boolean value) {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```


Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)
```


Разбивается от начала до указанного места и сохраняет переднюю часть в выходном потоке.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitFromFirst(sourceStream, 5, outStream);
```

--------------------

Потоки НЕ закрываются после этой операции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Исходный файл Pdf Stream. |
| location | int | Точка разделения. |
| outputStream | java.io.OutputStream | Выходной файл Поток. |

**Возвращает:**
boolean - True для успеха или false.
### splitFromFirst(InputStream inputStream, int location, HttpServletResponse response) {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitFromFirst(InputStream inputStream, int location, HttpServletResponse response)
```


Разбивает документ от начала до указанного места и сохраняет результат в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| location | int | Точка разделения. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse, в котором будет храниться результат. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public boolean splitFromFirst(String inputFile, int location, String outputFile)
```


Разбивает файл Pdf с первой страницы в указанное место и сохраняет переднюю часть как новый файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitFromFirst("input.pdf", 5, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Исходный PDF-файл. |
| location | int | Точка разделения. |
| outputFile | java.lang.String | Выходной PDF-файл. |

**Возвращает:**
boolean - True для успеха или false.
### splitFromFirst(String inputFile, int location, HttpServletResponse response) {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitFromFirst(String inputFile, int location, HttpServletResponse response)
```


Разделяет документ с первой страницы на место и сохраняет результат в объектах HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя исходного файла. |
| location | int | Точка разделения. |
| response | javax.servlet.http.HttpServletResponse | Объекты HttpServletResponse. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
public ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] numberOfPage)
```


Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| numberOfPage | int[][] | Начальная страница и конечная страница каждого документа. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Выходные потоки PDF, каждый поток буферизует документ PDF.
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
public ByteArrayInputStream[] splitToBulks(String inputFile, int[][] numberOfPage)
```


Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите PDF-файл. |
| numberOfPage | int[][] | Массив, содержащий массив двойных элементов, являющийся начальной и конечной страницами документа. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Выходные потоки PDF, каждый поток буферизует документ PDF.
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitToEnd(InputStream inputStream, int location, OutputStream outputStream)
```


Разбивается из указанного места и сохраняет заднюю часть как новый файловый поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitToEnd(sourceStream, 5, outStream);
```

--------------------

Потоки НЕ закрываются после этой операции, если не указано значение CloseConcatedStreams.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Исходный файл Pdf Stream. |
| location | int | Позиция разделения. |
| outputStream | java.io.OutputStream | Выходной файл Pdf Stream. |

**Возвращает:**
boolean - True для успеха или false.
### splitToEnd(InputStream inputStream, int location, HttpServletResponse response) {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitToEnd(InputStream inputStream, int location, HttpServletResponse response)
```


Разделяется из указанного места и сохраняет заднюю часть в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| location | int | Точка разделения. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse. |

**Возвращает:**
boolean - true, если расщепление прошло успешно.
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public boolean splitToEnd(String inputFile, int location, String outputFile)
```


Отделяется от местоположения и сохраняет заднюю часть как новый файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitToEnd("input.pdf", 5, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Исходный PDF-файл. |
| location | int | Позиция разделения. |
| outputFile | java.lang.String | Выходной путь к файлу Pdf. |

**Возвращает:**
boolean - True для успеха или false.
### splitToEnd(String inputFile, int location, HttpServletResponse response) {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitToEnd(String inputFile, int location, HttpServletResponse response)
```


Разделяется из указанного места и сохраняет заднюю часть в объекте HttpServletResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | имя исходного файла. |
| location | int | Точка разделения. |
| response | javax.servlet.http.HttpServletResponse | Объекты HttpServletResponse. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
public ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


Разбивает файл Pdf на одностраничные документы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Массив потоков памяти, содержащих страницы документа.
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public void splitToPages(InputStream inputStream, String fileNameTemplate)
```


Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. Путь задается полем имени поля шаблона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| fileNameTemplate | java.lang.String | Шаблон результирующего имени файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указано c:/dir/page%NUM%.pdf, результирующие файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т. д. |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
public ByteArrayInputStream[] splitToPages(String inputFile)
```


Разбивает файл PDF на одностраничные документы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите имя файла PDF. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Выходные потоки PDF, каждый поток буферизует одностраничный документ PDF.
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public void splitToPages(String inputFile, String fileNameTemplate)
```


Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. Путь задается полем имени поля шаблона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите имя файла. |
| fileNameTemplate | java.lang.String | Шаблон результирующего имени файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указано c:/dir/page%NUM%.pdf, результирующие файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т. д. |

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
