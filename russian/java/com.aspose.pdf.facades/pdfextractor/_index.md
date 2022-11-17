---
title: PdfExtractor
second_title: Aspose.PDF для справки по Java API
description: Класс для извлечения изображений и текста из документа PDF.
type: docs
weight: 38
url: /ru/java/com.aspose.pdf.facades/pdfextractor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade)
```
public final class PdfExtractor extends Facade
```

Класс для извлечения изображений и текста из документа PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfExtractor()](#PdfExtractor--) | Инициализирует новый объект PdfExtractor. |
| [PdfExtractor(IDocument document)](#PdfExtractor-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfExtractor на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Связывает PDF-документ из потока. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Привязать входной PDF-файл. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Удаляет документ, связанный с фасадом. |
| [dispose()](#dispose--) | Располагает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachment()](#extractAttachment--) | Извлекает вложения из документа Pdf. |
| [extractAttachment(String attachmentFileName)](#extractAttachment-java.lang.String-) | Извлекает вложение в файл PDF по имени вложения. |
| [extractImage()](#extractImage--) | Извлечение изображений из файла PDF. |
| [extractMarkedContentAsImages(Page page, String path)](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | Получает все контейнеры с отмеченным содержимым в виде отдельных изображений. |
| [extractText()](#extractText--) | Извлекает текст из документа Pdf. |
| [extractText(Charset encoding)](#extractText-java.nio.charset.Charset-) | Извлекает текст из документа Pdf, используя указанную кодировку. |
| [extractTextInternal(TextEncodingInternal encoding)](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Только для внутреннего использования |
| [getAttachNames()](#getAttachNames--) | Возвращает список вложений в файле PDF. |
| [getAttachment()](#getAttachment--) | Сохраняет все вложенные файлы в потоки. |
| [getAttachment(String outputPath)](#getAttachment-java.lang.String-) | Сохраняет вложение в файл. |
| [getAttachmentInfo()](#getAttachmentInfo--) | Получает список вложений. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getEndPage()](#getEndPage--) | Получает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [getExtractImageMode()](#getExtractImageMode--) | Устанавливает режим для процесса извлечения изображений. |
| [getExtractTextMode()](#getExtractTextMode--) | Получает режим для извлечения результата текста. |
| [getNextImage(OutputStream outputStream)](#getNextImage-java.io.OutputStream-) | Получите следующее изображение из файла PDF и сохраните его в потоке. |
| [getNextImage(OutputStream outputStream, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Получить следующее изображение из файла PDF и сохранить его в поток с заданным форматом изображения. |
| [getNextImage(String outputFile)](#getNextImage-java.lang.String-) | Извлекает следующее изображение из документа PDF. |
| [getNextImage(String outputFile, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Извлекает следующее изображение из документа PDF с заданным форматом изображения. |
| [getNextPageText(OutputStream outputStream)](#getNextPageText-java.io.OutputStream-) | Сохраняет текст одной страницы в поток. |
| [getNextPageText(String outputFile)](#getNextPageText-java.lang.String-) | Сохраняет текст одной страницы в файл. |
| [getPassword()](#getPassword--) | Получает пароль входного файла. |
| [getResolution()](#getResolution--) | Получает разрешение для извлеченных изображений. |
| [getStartPage()](#getStartPage--) | Получает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [getText(OutputStream outputStream)](#getText-java.io.OutputStream-) | Сохраняет текст в поток. см. также: Извлечь текст  |
| [getText(OutputStream outputStream, boolean filterNotAscii)](#getText-java.io.OutputStream-boolean-) | Сохраняет текст в поток. см. также: Извлечь текст  |
| [getText(String outputFile)](#getText-java.lang.String-) | Сохраняет текст в файл. см. также: Извлечь текст  |
| [getTextSearchOptions()](#getTextSearchOptions--) | Получает параметры поиска текста. |
| [hasNextImage()](#hasNextImage--) | Проверяет, доступны ли дополнительные изображения в документе PDF. |
| [hasNextPageText()](#hasNextPageText--) | Указывает, может ли получить больше текстов или нет. |
| [hashCode()](#hashCode--) |  |
| [isBidi()](#isBidi--) | Верно, если в тексте есть еврейские или арабские символы. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndPage(int value)](#setEndPage-int-) | Устанавливает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [setExtractImageMode(int value)](#setExtractImageMode-int-) | Устанавливает режим для процесса извлечения изображений. |
| [setExtractTextMode(int value)](#setExtractTextMode-int-) | Устанавливает режим извлечения результата текста. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Устанавливает пароль входного файла. |
| [setResolution(int value)](#setResolution-int-) | Установите разрешение для извлеченных изображений. |
| [setStartPage(int value)](#setStartPage-int-) | Устанавливает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Задает параметры поиска текста. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfExtractor() {#PdfExtractor--}
```
public PdfExtractor()
```


Инициализирует новый объект PdfExtractor.

### PdfExtractor(IDocument document) {#PdfExtractor-com.aspose.pdf.IDocument-}
```
public PdfExtractor(IDocument document)
```


Инициализирует новый объект PdfExtractor на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Связывает PDF-документ из потока.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 InputStream stream = new FileInputStream("sample.pdf");
 ext.bindPdf(stream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток, содержащий данные документа PDF |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Привязать входной PDF-файл.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindPdf("sample.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | PDF-файл для привязки |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### close() {#close--}
```
public void close()
```


Удаляет документ, связанный с фасадом.

### dispose() {#dispose--}
```
public void dispose()
```


Располагает фасад.

Этот метод устарел, вместо него используйте close().

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
### extractAttachment() {#extractAttachment--}
```
public void extractAttachment()
```


Извлекает вложения из документа Pdf.

### extractAttachment(String attachmentFileName) {#extractAttachment-java.lang.String-}
```
public void extractAttachment(String attachmentFileName)
```


Извлекает вложение в файл PDF по имени вложения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| attachmentFileName | java.lang.String | Название вложения для извлечения |

### extractImage() {#extractImage--}
```
public void extractImage()
```


Извлечение изображений из файла PDF.

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.HasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

### extractMarkedContentAsImages(Page page, String path) {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
```
public void extractMarkedContentAsImages(Page page, String path)
```


Получает все контейнеры с отмеченным содержимым в виде отдельных изображений.

Каждое отмеченное содержимое будет сохранено как изображение в формате png с именем MCID.\_.png 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для процесса. |
| path | java.lang.String | Путь, по которому будут сохраняться изображения. |

### extractText() {#extractText--}
```
public void extractText()
```


Извлекает текст из документа Pdf.

--------------------

```
First example demonstratres how to extract all the text from PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("D:\Text\text.pdf");
 	extractor.extractText();
 	extractor.getText("D:\Text\text.txt");
```

Второй пример демонстрирует, как извлечь текст каждой страницы в один текстовый файл.

```
PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText();
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

### extractText(Charset encoding) {#extractText-java.nio.charset.Charset-}
```
public void extractText(Charset encoding)
```


Извлекает текст из документа Pdf, используя указанную кодировку.

--------------------

```
First example demonstrates how to extract all the text from PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("D:\\Text\\text.pdf");
 	extractor.extractText(Encoding.Unicode);
 	extractor.getText("D:\\Text\\text.txt");
```

Второй пример демонстрирует, как извлечь текст каждой страницы в один текстовый файл.

```
PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText(java.nio.charset.Charset.forName("UTF-8"));
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | Кодировка извлеченного текста. |

### extractTextInternal(TextEncodingInternal encoding) {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void extractTextInternal(TextEncodingInternal encoding)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | Кодировка извлеченного текста. |

### getAttachNames() {#getAttachNames--}
```
public List<String> getAttachNames()
```


Возвращает список вложений в файле PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractAttachments.

--------------------

```
Example demonstrates how to extract attachment names form PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(TestSettings.GetInputFile("sample.pdf"));
 	extractor.ExtractAttachment();
 	List attachments = extractor.getAttachNames();
 	for (String name : ```
(Iterable)
```attachments)
 		System.out.println(name);
```

**Возвращает:**
java.util.List<java.lang.String> — Список вложений
### getAttachment() {#getAttachment--}
```
public ByteArrayOutputStream[] getAttachment()
```


Сохраняет все вложенные файлы в потоки.

--------------------

```
PdfExtractor extractor = new PdfExtractor();     
 	extractor.bindPdf(path + "Attach.pdf");
 	extractor.extractAttachment();
 	IList names = extractor.getAttachNames();
 	ByteArrayOutputStream[] tempStreams =  extractor.getAttachment();
 	for (int i=0; i<tempStreams.Length; i++)
 	{
 		string name = (string)names[i];
 		OutputStream fs = new FileOutputStream(path + name);
 		fs.write(tempStreams[i].toByteArray()); 
 		fs.close();
 	}
```

**Возвращает:**
java.io.ByteArrayOutputStream[- Потоковый массив вложенного файла в pdf-документе.
### getAttachment(String outputPath) {#getAttachment-java.lang.String-}
```
public void getAttachment(String outputPath)
```


Сохраняет вложение в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputPath | java.lang.String | Путь к каталогу, в котором будут храниться вложения. Нулевая или пустая строка означает, что вложения будут помещены в каталог приложения. |

### getAttachmentInfo() {#getAttachmentInfo--}
```
public List<FileSpecification> getAttachmentInfo()
```


Получает список вложений.

**Возвращает:**
java.util.List<com.aspose.pdf.FileSpecification> — возвращает список<FileSpecificatio>.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getEndPage() {#getEndPage--}
```
public int getEndPage()
```


Получает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(3);
 ext.extractText();
```

**Возвращает:**
int - конечная страница.
### getExtractImageMode() {#getExtractImageMode--}
```
public int getExtractImageMode()
```


Устанавливает режим для процесса извлечения изображений.

--------------------

Значение по умолчанию — ExtractImageMode.DefinedInResources, которое извлекает все изображения, определенные в ресурсах. Для извлечения реально показанных изображений следует использовать режим ExtractImageMode.ActuallyUsed.

**Возвращает:**
int — значение ExtractImageMode
### getExtractTextMode() {#getExtractTextMode--}
```
public int getExtractTextMode()
```


Получает режим для извлечения результата текста.

--------------------

```
The example demonstratres the ```
ExtractTextMode
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(@"D:\Text\text.pdf");
  extractor.setExtractTextMode(1);
 	extractor.extractText();
 	extractor.getText(@"D:\Text\text.txt");
```

Значение: 0 — чисто текстовый режим, 1 — режим необработанного упорядочения. По умолчанию 0.

**Возвращает:**
int - извлечь текстовый результат.
### getNextImage(OutputStream outputStream) {#getNextImage-java.io.OutputStream-}
```
public boolean getNextImage(OutputStream outputStream)
```


Получите следующее изображение из файла PDF и сохраните его в потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток, в котором будут сохранены данные изображения |

**Возвращает:**
boolean — Истинно, если изображение успешно извлечено.
### getNextImage(OutputStream outputStream, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public boolean getNextImage(OutputStream outputStream, ImageType format)
```


Получить следующее изображение из файла PDF и сохранить его в поток с заданным форматом изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток, в котором будут сохранены данные изображения |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |

**Возвращает:**
boolean — Истинно, если изображение успешно извлечено.
### getNextImage(String outputFile) {#getNextImage-java.lang.String-}
```
public boolean getNextImage(String outputFile)
```


Извлекает следующее изображение из документа PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.hasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Файл, в котором будет храниться изображение |

**Возвращает:**
boolean - True означает, что изображение успешно извлечено
### getNextImage(String outputFile, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
```
public boolean getNextImage(String outputFile, ImageType format)
```


Извлекает следующее изображение из документа PDF с заданным форматом изображения. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Файл, в котором будет храниться изображение |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Элемент ImageType |

**Возвращает:**
boolean - True означает, что изображение успешно извлечено
### getNextPageText(OutputStream outputStream) {#getNextPageText-java.io.OutputStream-}
```
public void getNextPageText(OutputStream outputStream)
```


Сохраняет текст одной страницы в поток.

--------------------

```
The example demonstratres the ```
GetNextPageText
``` method usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create);
      extractor.getNextPageText(fs);
      fs.close();
      pageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения текста. |

### getNextPageText(String outputFile) {#getNextPageText-java.lang.String-}
```
public void getNextPageText(String outputFile)
```


Сохраняет текст одной страницы в файл.

--------------------

```
The example demonstratres the GetNextPageText method usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + @"Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения текста. |

### getPassword() {#getPassword--}
```
public String getPassword()
```


Получает пароль входного файла.

**Возвращает:**
java.lang.String — строковое значение
### getResolution() {#getResolution--}
```
public int getResolution()
```


Получает разрешение для извлеченных изображений. Значение по умолчанию — 150. Изображения с большим значением разрешения более четкие. Однако увеличение значения разрешения приводит к увеличению времени и памяти, необходимых для извлечения изображений. Обычно для получения четкого изображения достаточно установить разрешение 150 или 300.

**Возвращает:**
интервал - целочисленное значение
### getStartPage() {#getStartPage--}
```
public int getStartPage()
```


Получает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(5);
 ext.extractText();
```

**Возвращает:**
int - начальная страница в диапазоне страниц.
### getText(OutputStream outputStream) {#getText-java.io.OutputStream-}
```
public void getText(OutputStream outputStream)
```


Сохраняет текст в поток. см. также: Извлечь текст 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения текста. |

### getText(OutputStream outputStream, boolean filterNotAscii) {#getText-java.io.OutputStream-boolean-}
```
public void getText(OutputStream outputStream, boolean filterNotAscii)
```


Сохраняет текст в поток. см. также: Извлечь текст 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения текста. |
| filterNotAscii | boolean | Если этот параметр имеет значение true, все символы, отличные от ASCII, будут удалены. |

### getText(String outputFile) {#getText-java.lang.String-}
```
public void getText(String outputFile)
```


Сохраняет текст в файл. см. также: Извлечь текст 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения текста. |

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Получает параметры поиска текста.

**Возвращает:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - параметры текстового поиска.
### hasNextImage() {#hasNextImage--}
```
public boolean hasNextImage()
```


Проверяет, доступны ли дополнительные изображения в документе PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.hasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

**Возвращает:**
boolean - Истинно, если доступно больше изображений
### hasNextPageText() {#hasNextPageText--}
```
public boolean hasNextPageText()
```


Указывает, может ли получить больше текстов или нет.

--------------------

```
The example demonstratres the ```
HasNextPageText
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**Возвращает:**
boolean - Может получить больше текстов или нет, true может или false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isBidi() {#isBidi--}
```
public boolean isBidi()
```


Верно, если в тексте есть еврейские или арабские символы. Этот случай следует рассмотреть особо, поскольку строковые функции меняют свое поведение и начинают обрабатывать текст справа налево (кроме чисел и других нетекстовых символов).

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




### setEndPage(int value) {#setEndPage-int-}
```
public void setEndPage(int value)
```


Устанавливает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(3);
 ext.extractText();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | конечная страница. |

### setExtractImageMode(int value) {#setExtractImageMode-int-}
```
public void setExtractImageMode(int value)
```


Устанавливает режим для процесса извлечения изображений.

--------------------

Значение по умолчанию — ExtractImageMode.DefinedInResources, которое извлекает все изображения, определенные в ресурсах. Для извлечения реально показанных изображений следует использовать режим ExtractImageMode.ActuallyUsed.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение Экстрактимажемоде |

### setExtractTextMode(int value) {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```


Устанавливает режим извлечения результата текста.

--------------------

```
The example demonstratres the ```
ExtractTextMode
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(@"D:\Text\text.pdf");
  extractor.setExtractTextMode(1);
 	extractor.extractText();
 	extractor.getText(@"D:\Text\text.txt");
```

Значение: 0 — чисто текстовый режим, 1 — режим необработанного упорядочения. По умолчанию 0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | извлечь результат текста. |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Устанавливает пароль входного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Установите разрешение для извлеченных изображений. Значение по умолчанию — 150. Изображения с большим значением разрешения более четкие. Однако увеличение значения разрешения приводит к увеличению времени и памяти, необходимых для извлечения изображений. Обычно для получения четкого изображения достаточно установить разрешение 150 или 300.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setStartPage(int value) {#setStartPage-int-}
```
public void setStartPage(int value)
```


Устанавливает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(5);
 ext.extractText();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | начальная страница в диапазоне страниц. |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Задает параметры поиска текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | параметры текстового поиска. |

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
