---
title: Image
second_title: Aspose.PDF для справки по Java API
description: Представляет изображение.
type: docs
weight: 166
url: /ru/java/com.aspose.pdf/image/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Image extends BaseParagraph
```

Представляет изображение.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Image()](#Image--) | конструктор по умолчанию |
## Методы

| Метод | Описание |
| --- | --- |
| [convertToJpeg(InputStream value)](#convertToJpeg-java.io.InputStream-) | Попробуйте конвертировать в поток с изображением bmp/png/gif/tiff в поток с изображением в формате JPG. |
| [deepClone()](#deepClone--) | Клонируйте изображение. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferedImage()](#getBufferedImage--) | Получает образ java awt. |
| [getClass()](#getClass--) |  |
| [getFile()](#getFile--) | Получает файл изображения. |
| [getFileType()](#getFileType--) | Получает тип файла изображения. |
| [getFixHeight()](#getFixHeight--) | Получает высоту изображения. |
| [getFixWidth()](#getFixWidth--) | Получает ширину изображения. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getImageScale()](#getImageScale--) | Получает масштаб изображения. |
| [getImageStream()](#getImageStream--) | Получает поток изображения. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getMimeType(System.Drawing.Image i)](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Возвращает тип mime для изображения. |
| [getTitle()](#getTitle--) | Получает строковое значение, указывающее заголовок изображения. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isApplyResolution()](#isApplyResolution--) | Получает или задает логическое значение, указывающее, использует ли изображение разрешение во время создания. |
| [isBlackWhite()](#isBlackWhite--) | Получает логическое значение, указывающее, должно ли изображение быть черно-белым. |
| [isBlackWhiteForGrayScale()](#isBlackWhiteForGrayScale--) | Попробуйте обнаружить и использовать кодировку 1bpp для изображений в градациях серого. Значение по умолчанию == FALSE. |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyResolution(boolean value)](#setApplyResolution-boolean-) | Получает или задает логическое значение, указывающее, использует ли изображение разрешение во время создания. |
| [setBlackWhite(boolean value)](#setBlackWhite-boolean-) | Задает логическое значение, указывающее, должно ли изображение быть черно-белым. |
| [setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)](#setBlackWhiteForGrayScale-boolean-) | Попробуйте обнаружить и использовать кодировку 1bpp для изображений в градациях серого. |
| [setBufferedImage(BufferedImage value)](#setBufferedImage-java.awt.image.BufferedImage-) | Устанавливает образ java awt. |
| [setFile(String value)](#setFile-java.lang.String-) | Устанавливает файл изображения. |
| [setFileType(int value)](#setFileType-int-) | Устанавливает тип файла изображения. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setFixHeight(double value)](#setFixHeight-double-) | Устанавливает высоту изображения. |
| [setFixWidth(double value)](#setFixWidth-double-) | Устанавливает ширину изображения. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setImageScale(double value)](#setImageScale-double-) | Устанавливает масштаб изображения. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Устанавливает поток изображения. |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | Задает строковое значение, указывающее заголовок изображения. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Image() {#Image--}
```
public Image()
```


конструктор по умолчанию

### convertToJpeg(InputStream value) {#convertToJpeg-java.io.InputStream-}
```
public static InputStream convertToJpeg(InputStream value)
```


Попробуйте конвертировать в поток с изображением bmp/png/gif/tiff в поток с изображением в формате JPG.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Экземпляр InputStream |

**Возвращает:**
java.io.InputStream — экземпляр InputStream
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонируйте изображение.

**Возвращает:**
java.lang.Object — клонированный объект
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
### getBufferedImage() {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```


Получает образ java awt.

**Возвращает:**
java.awt.image.BufferedImage — объект BufferedImage
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFile() {#getFile--}
```
public String getFile()
```


Получает файл изображения.

**Возвращает:**
java.lang.String — строковое значение
### getFileType() {#getFileType--}
```
public int getFileType()
```


Получает тип файла изображения.

**Возвращает:**
интервал - целочисленное значение
### getFixHeight() {#getFixHeight--}
```
public double getFixHeight()
```


Получает высоту изображения.

**Возвращает:**
двойное - двойное значение
### getFixWidth() {#getFixWidth--}
```
public double getFixWidth()
```


Получает ширину изображения.

**Возвращает:**
двойное - двойное значение
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание абзаца

**Возвращает:**
int - значение HorizontalAlignment
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает гиперссылку фрагмента (для генератора pdf).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - гиперссылка на фрагмент (для генератора pdf).
### getImageScale() {#getImageScale--}
```
public double getImageScale()
```


Получает масштаб изображения.

**Возвращает:**
двойное - двойное значение
### getImageStream() {#getImageStream--}
```
public InputStream getImageStream()
```


Получает поток изображения.

**Возвращает:**
java.io.InputStream — объект InputStream
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getMimeType(System.Drawing.Image i) {#getMimeType-com.aspose.ms.System.Drawing.Image-}
```
public static String getMimeType(System.Drawing.Image i)
```


Возвращает тип mime для изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | com.aspose.ms.System.Drawing.Image | Объект изображения/ |

**Возвращает:**
java.lang.String — тип Mime в виде строки, если он найден; в противном случае — значение «изображение/неизвестно».
### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


Получает строковое значение, указывающее заголовок изображения.

**Возвращает:**
[TextFragment](../../com.aspose.pdf/textfragment) - значение фрагмента текста
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание абзаца

**Возвращает:**
int - элемент вертикального выравнивания
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Получает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isApplyResolution() {#isApplyResolution--}
```
public boolean isApplyResolution()
```


Получает или задает логическое значение, указывающее, использует ли изображение разрешение во время создания.

**Возвращает:**
boolean - логическое значение
### isBlackWhite() {#isBlackWhite--}
```
public boolean isBlackWhite()
```


Получает логическое значение, указывающее, должно ли изображение быть черно-белым. Если используется изображение TIFF подформата CCITT, это свойство должно быть установлено в значение true.

**Возвращает:**
boolean - логическое значение
### isBlackWhiteForGrayScale() {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```


Попробуйте обнаружить и использовать кодировку 1bpp для изображений в градациях серого. Значение по умолчанию == FALSE.

**Возвращает:**
boolean - логическое значение
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Получает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. Значение по умолчанию — false. (для генерации pdf)

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




### setApplyResolution(boolean value) {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```


Получает или задает логическое значение, указывающее, использует ли изображение разрешение во время создания.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBlackWhite(boolean value) {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```


Задает логическое значение, указывающее, должно ли изображение быть черно-белым. Если используется изображение TIFF подформата CCITT, это свойство должно быть установлено в значение true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale) {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```


Попробуйте обнаружить и использовать кодировку 1bpp для изображений в градациях серого. Значение по умолчанию == ЛОЖЬ

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| blackWhiteForGrayScale | boolean | логическое значение |

### setBufferedImage(BufferedImage value) {#setBufferedImage-java.awt.image.BufferedImage-}
```
public void setBufferedImage(BufferedImage value)
```


Устанавливает образ java awt.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | Объект BufferedImage |

### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


Устанавливает файл изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setFileType(int value) {#setFileType-int-}
```
public void setFileType(int value)
```


Устанавливает тип файла изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFixHeight(double value) {#setFixHeight-double-}
```
public void setFixHeight(double value)
```


Устанавливает высоту изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setFixWidth(double value) {#setFixWidth-double-}
```
public void setFixWidth(double value)
```


Устанавливает ширину изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает горизонтальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Устанавливает гиперссылку (для генератора pdf).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | гиперссылка (для генератора pdf). |

### setImageScale(double value) {#setImageScale-double-}
```
public void setImageScale(double value)
```


Устанавливает масштаб изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public void setImageStream(InputStream value)
```


Устанавливает поток изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Значение InputStream |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Устанавливает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


Задает строковое значение, указывающее заголовок изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | Значение TextFragment |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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
