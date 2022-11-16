---
title: Stamp
second_title: Aspose.PDF для справки по Java API
description: Штамп, представляющий класс.
type: docs
weight: 59
url: /ru/java/com.aspose.pdf.facades/stamp/
---
**Наследование:**
java.lang.Object
```
public final class Stamp
```

Штамп, представляющий класс.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Stamp()](#Stamp--) | Конструктор объекта Stamp. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindImage(InputStream image)](#bindImage-java.io.InputStream-) | Устанавливает изображение, которое будет использоваться в качестве штампа. |
| [bindImage(String imageFile)](#bindImage-java.lang.String-) | Устанавливает изображение в качестве штампа. |
| [bindLogo(FormattedText formattedText)](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Устанавливает текст как штамп. |
| [bindPdf(InputStream pdfStream, int pageNumber)](#bindPdf-java.io.InputStream-int-) | Устанавливает файл PDF и количество страниц, которые будут использоваться в качестве штампа. |
| [bindPdf(String pdfFile, int pageNumber)](#bindPdf-java.lang.String-int-) | Устанавливает файл PDF и количество страниц, которые будут использоваться в качестве штампа. |
| [bindTextState(TextState textState)](#bindTextState-com.aspose.pdf.TextState-) | Устанавливает текстовое состояние текста штампа. |
| [close()](#close--) | Закрывает этот экземпляр |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingSpace()](#getBlendingSpace--) | Получает значение BlendingColorSpace, определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице. |
| [getClass()](#getClass--) |  |
| [getOpacity()](#getOpacity--) | Получает непрозрачность штампа. |
| [getPageNumber()](#getPageNumber--) | Получает номер страницы. |
| [getPages()](#getPages--) | Получает массив с номерами страниц, на которые повлияет штамп. |
| [getQuality()](#getQuality--) | Получает качество штампа изображения в процентах. |
| [getRotation()](#getRotation--) | Получает вращение штампа в градусах. |
| [getStampId()](#getStampId--) | Получает идентификатор штампа. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | Получает фоновый статус. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackground(boolean value)](#setBackground-boolean-) | Устанавливает фоновый статус. |
| [setBlendingSpace(int value)](#setBlendingSpace-int-) | Задает значение BlendingColorSpace, определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице. |
| [setImageSize(float width, float height)](#setImageSize-float-float-) | Устанавливает размер штампа изображения. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность штампа. |
| [setOrigin(float originX, float originY)](#setOrigin-float-float-) | Устанавливает положение на странице, где будет помещен штамп. |
| [setPageNumber(int value)](#setPageNumber-int-) | Устанавливает номер страницы. |
| [setPages(int[] value)](#setPages-int---) | Задает массив с номерами страниц, на которые будет распространяться штамп. |
| [setQuality(int value)](#setQuality-int-) | Устанавливает качество штампа изображения в процентах. |
| [setRotation(float value)](#setRotation-float-) | Получает или задает поворот штампа в градусах. |
| [setStampId(int value)](#setStampId-int-) | Устанавливает идентификатор штампа. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Stamp() {#Stamp--}
```
public Stamp()
```


Конструктор объекта Stamp.

### bindImage(InputStream image) {#bindImage-java.io.InputStream-}
```
public void bindImage(InputStream image)
```


Устанавливает изображение, которое будет использоваться в качестве штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Поток, содержащий данные изображения. |

### bindImage(String imageFile) {#bindImage-java.lang.String-}
```
public void bindImage(String imageFile)
```


Устанавливает изображение в качестве штампа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 stamp.bindImage("image.jpg");
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String | Имя файла изображения и путь. |

### bindLogo(FormattedText formattedText) {#bindLogo-com.aspose.pdf.facades.FormattedText-}
```
public void bindLogo(FormattedText formattedText)
```


Устанавливает текст как штамп.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект FormattedText, который определяет текст и свойства текста. |

### bindPdf(InputStream pdfStream, int pageNumber) {#bindPdf-java.io.InputStream-int-}
```
public void bindPdf(InputStream pdfStream, int pageNumber)
```


Устанавливает файл PDF и количество страниц, которые будут использоваться в качестве штампа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 //First page will be used as stamp.
 InputStream stream = new FileInputStream("stamp.pdf");
 stamp.bindPdf(stream, 1);
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Поток, содержащий PDF-документ. |
| pageNumber | int | Индекс страниц документа, который будет использоваться в качестве штампа. |

### bindPdf(String pdfFile, int pageNumber) {#bindPdf-java.lang.String-int-}
```
public void bindPdf(String pdfFile, int pageNumber)
```


Устанавливает файл PDF и количество страниц, которые будут использоваться в качестве штампа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 //First page will be used as stamp.
 stamp.bindPdf("stamp.pdf", 1);
 stamp.isBackground (true);
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfFile | java.lang.String | Путь к файлу PDF. |
| pageNumber | int | Количество страниц в файле PDF |

### bindTextState(TextState textState) {#bindTextState-com.aspose.pdf.TextState-}
```
public void bindTextState(TextState textState)
```


Устанавливает текстовое состояние текста штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Объект TextState, определяющий свойства текста. |

### close() {#close--}
```
public void close()
```


Закрывает этот экземпляр

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
### getBlendingSpace() {#getBlendingSpace--}
```
public int getBlendingSpace()
```


Получает значение BlendingColorSpace, определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице.

**Возвращает:**
интервал - целочисленное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность штампа.

**Возвращает:**
float - плавающее значение
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Получает номер страницы.

**Возвращает:**
интервал - целочисленное значение
### getPages() {#getPages--}
```
public int[] getPages()
```


Получает массив с номерами страниц, на которые повлияет штамп.

**Возвращает:**
инт[] - целочисленный массив
### getQuality() {#getQuality--}
```
public int getQuality()
```


Получает качество штампа изображения в процентах. Допустимые значения 0..100%.

**Возвращает:**
интервал - целочисленное значение
### getRotation() {#getRotation--}
```
public float getRotation()
```


Получает вращение штампа в градусах.

**Возвращает:**
float - плавающее значение
### getStampId() {#getStampId--}
```
public int getStampId()
```


Получает идентификатор штампа.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Получает фоновый статус. Если правда, штамп будет помещен в качестве фона заспамленной страницы. По умолчанию установлено значение false.

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




### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Устанавливает фоновый статус. Если правда, штамп будет помещен в качестве фона заспамленной страницы. По умолчанию установлено значение false.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBlendingSpace(int value) {#setBlendingSpace-int-}
```
public void setBlendingSpace(int value)
```


Задает значение BlendingColorSpace, определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setImageSize(float width, float height) {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```


Устанавливает размер штампа изображения. Изображение будет масштабировано в соответствии с указанными значениями.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Ширина изображения. |
| height | float | Высота изображения. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setOrigin(float originX, float originY) {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```


Устанавливает положение на странице, где будет помещен штамп.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| originX | float | X координата штампа. |
| originY | float | Координата Y штампа. |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Устанавливает номер страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Задает массив с номерами страниц, на которые будет распространяться штамп. Если Pages = null, затрагиваются все страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | массив целых чисел

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new com.aspose.pdf.facades.Stamp();
 stamp.bindLogo(new FormattedText(text));
 //put stamp only on 1st, 4th and 6th page.
 stamp.setPages(new int[] { 1, 4, 6 });
 fileStamp.addStamp(stamp);
 fileStamp.close();
``` |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality (значение int)
```


Sets quality of image stamp in percent. Valiued values 0..100%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRotation(float value) {#setRotation-float-}
```
public void setRotation (значение с плавающей запятой)
```


Gets or sets rotation of the stamp in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value

--------------------

```
PdfFileStamp fileStamp = новый PdfFileStamp ("input.pdf", "output.pdf");
 Штамп Штамп = новый Штамп();
 штамп.bindLogo(новый FormattedText("STAMP"));
 штамп.setRotation(90);
 fileStamp.addStamp(штамп);
 Штамп файла.close();
``` |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId (значение int)
```


Sets identifier of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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
