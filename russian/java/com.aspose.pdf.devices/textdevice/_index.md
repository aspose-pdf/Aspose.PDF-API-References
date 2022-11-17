---
title: TextDevice
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для преобразования страниц документа PDF в текст.
type: docs
weight: 26
url: /ru/java/com.aspose.pdf.devices/textdevice/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice)
```
public final class TextDevice extends PageDevice
```

Представляет класс для преобразования страниц документа PDF в текст.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       try 
	       {
	           // создать текстовое устройство
	           TextDevice device = new TextDevice();
	           // преобразовать страницу и сохранить текст в поток
	           device.process(doc.getPages().get_Item(1), ms);
	           // использовать извлеченный текст
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           
		    ms.close();
		} catch (IOException e) {
		    e.printStackTrace();
		}
```

--------------------

Объект TextDevice в основном используется для извлечения текста из страницы PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextDevice(TextExtractionOptions extractionOptions)](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Инициализирует новый экземпляр TextDevice с параметрами извлечения текста. |
| [TextDevice()](#TextDevice--) | Инициализирует новый экземпляр TextDevice с режимом форматирования необработанного текста и кодировкой текста Unicode. |
| [TextDevice(TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Инициализирует новый экземпляр TextDevice для указанной кодировки. |
| [TextDevice(Charset encoding)](#TextDevice-java.nio.charset.Charset-) | Инициализирует новый экземпляр TextDevice для указанной кодировки. |
| [TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Инициализирует новый экземпляр TextDevice для указанной кодировки с параметрами извлечения текста. |
| [TextDevice(TextExtractionOptions extractionOptions, Charset encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Инициализирует новый экземпляр TextDevice для указанной кодировки с параметрами извлечения текста. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Получает кодировку извлеченного текста. |
| [getEncodingInternal()](#getEncodingInternal--) | Получает кодировку извлеченного текста. |
| [getExtractionOptions()](#getExtractionOptions--) | Получает параметры извлечения текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | Отрисовывает страницу на графике |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Конвертируйте страницу и сохраните ее как текстовый поток. |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | Выполняет некоторую операцию на данной странице и сохраняет результаты в файл. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Конвертируйте страницу и сохраните ее как текстовый поток. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку извлеченного текста. |
| [setEncodingInternal(TextEncodingInternal value)](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | Устанавливает кодировку извлеченного текста. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Задает параметры извлечения текста. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextDevice(TextExtractionOptions extractionOptions) {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
```
public TextDevice(TextExtractionOptions extractionOptions)
```


Инициализирует новый экземпляр TextDevice с параметрами извлечения текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Варианты извлечения текста. |

### TextDevice() {#TextDevice--}
```
public TextDevice()
```


Инициализирует новый экземпляр TextDevice с режимом форматирования необработанного текста и кодировкой текста Unicode.

### TextDevice(TextEncodingInternal encoding) {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
```
public TextDevice(TextEncodingInternal encoding)
```


Инициализирует новый экземпляр TextDevice для указанной кодировки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | Кодирование извлеченного текста |

### TextDevice(Charset encoding) {#TextDevice-java.nio.charset.Charset-}
```
public TextDevice(Charset encoding)
```


Инициализирует новый экземпляр TextDevice для указанной кодировки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | Кодирование извлеченного текста |

### TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding) {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
```
public TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)
```


Инициализирует новый экземпляр TextDevice для указанной кодировки с параметрами извлечения текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Варианты извлечения текста. |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | Кодирование извлеченного текста. |

### TextDevice(TextExtractionOptions extractionOptions, Charset encoding) {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
```
public TextDevice(TextExtractionOptions extractionOptions, Charset encoding)
```


Инициализирует новый экземпляр TextDevice для указанной кодировки с параметрами извлечения текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Варианты извлечения текста. |
| encoding | java.nio.charset.Charset | Кодирование извлеченного текста. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Получает кодировку извлеченного текста.

**Возвращает:**
java.nio.charset.Charset — элемент набора символов

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // создать текстовое устройство
	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
	       // преобразовать страницу и сохранить текст в поток
	       device.process(doc.getPages().get_Item(1), outFile);
```
### getEncodingInternal() {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```


Получает кодировку извлеченного текста.

**Возвращает:**
[TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) - Элемент TextEncodingInternal

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // создать текстовое устройство
	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
	       // преобразовать страницу и сохранить текст в поток
	       device.process(doc.getPages().get_Item(1), outFile);
```
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Получает параметры извлечения текста.

**Возвращает:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - Элемент TextExtractionOptions

--------------------

```
The example demonstrates how to extracted text in raw order.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // создать текстовое устройство
	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
	       // преобразовать страницу и сохранить текст в поток
	       device.process(doc.getPages().get_Item(1), outFile);
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


Отрисовывает страницу на графике

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| gr | com.aspose.ms.System.Drawing.Graphics | внутренний объект |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Конвертируйте страницу и сохраните ее как текстовый поток.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       
	           // создать текстовое устройство
	           TextDevice device = new TextDevice();
	           // преобразовать страницу и сохранить текст в поток
	           device.process(doc.getPages().get_Item(1), ms);
	           //использовать извлеченный текст
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           ms.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для конвертации. |
| output | java.io.OutputStream | Поток результатов. |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}
```
public void process(Page page, String outputFileName)
```


Выполняет некоторую операцию на данной странице и сохраняет результаты в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для обработки. |
| outputFileName | java.lang.String | Этот файл содержит результаты обработки. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Конвертируйте страницу и сохраните ее как текстовый поток.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       
	           // создать текстовое устройство
	           TextDevice device = new TextDevice();
	           // преобразовать страницу и сохранить текст в поток
	           device.process(doc.getPages().get_Item(1), ms);
	           //использовать извлеченный текст
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           ms.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для конвертации. |
| output | com.aspose.ms.System.IO.Stream | Поток результатов. |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Устанавливает кодировку извлеченного текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset | Элемент набора символов

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
		       Document doc = new Document(inFile);
		       String extractedText;
		       // создать текстовое устройство
		       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
		       // преобразовать страницу и сохранить текст в поток
		       device.process(doc.getPages().get_Item(1), outFile);
``` |

### setEncodingInternal(TextEncodingInternal value) {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void setEncodingInternal (значение TextEncodingInternal)
```


Sets encoding of extracted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | TextEncodingInternal element

--------------------

```
В примере показано, как представить извлеченный текст в кодировке UTF-8.
 
		       Document doc = new Document(inFile);
		       String extractedText;
		       // create text device
		       TextDevice device = new TextDevice(TextEncodingInternal.getUTF8());
		       // convert the page and save text to the stream
		       device.process(doc.getPages().get_Item(1), outFile);
``` |

### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions (значение TextExtractionOptions)
```


Sets text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions element

--------------------

```
В примере показано, как извлечь текст в необработанном порядке.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
``` |

### toString() {#toString--}
```
публичная строка toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
публичный окончательный недействительный ожидание ()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
