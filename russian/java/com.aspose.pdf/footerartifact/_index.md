---
title: FooterArtifact
second_title: Aspose.PDF для справки по Java API
description: Описывает артефакт нижнего колонтитула.
type: docs
weight: 138
url: /ru/java/com.aspose.pdf/footerartifact/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Artifact](../../com.aspose.pdf/artifact)
```
public class FooterArtifact extends Artifact
```

Описывает артефакт нижнего колонтитула. Это может быть использовано для установки нижнего колонтитула страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FooterArtifact()](#FooterArtifact--) | Создает экземпляр артефакта нижнего колонтитула. |
## Методы

| Метод | Описание |
| --- | --- |
| [beginUpdates()](#beginUpdates--) | Запустить удаленные обновления. |
| [close()](#close--) | Закрывает все ресурсы, используемые этим документом. |
| [dispose()](#dispose--) | Утилизируйте артефакт. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtifactHorizontalAlignment()](#getArtifactHorizontalAlignment--) | Получает горизонтальное выравнивание артефакта. |
| [getArtifactVerticalAlignment()](#getArtifactVerticalAlignment--) | Получает вертикальное выравнивание артефакта. |
| [getBottomMargin()](#getBottomMargin--) | Получает нижнее поле артефакта. |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | Получает коллекцию внутренних операторов артефакта. |
| [getCustomSubtype()](#getCustomSubtype--) | Получает имя подтипа артефакта. |
| [getCustomType()](#getCustomType--) | Получает имя типа артефакта. |
| [getForm()](#getForm--) | Получает XForm артефакта (если используется XForm). |
| [getImage()](#getImage--) | Получает изображение артефакта (если присутствует). |
| [getLeftMargin()](#getLeftMargin--) | Получает левое поле артефакта. |
| [getLines()](#getLines--) | Строки многострочного текстового артефакта. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность артефакта. |
| [getPosition()](#getPosition--) | Получает позицию артефакта. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник артефакта. |
| [getRightMargin()](#getRightMargin--) | Получает правый край артефакта. |
| [getRotation()](#getRotation--) | Получает угол поворота артефакта. |
| [getSubtype()](#getSubtype--) | Получает подтип артефакта. |
| [getText()](#getText--) | Получает текст артефакта. |
| [getTextState()](#getTextState--) | Текстовое состояние для текста артефакта. |
| [getTopMargin()](#getTopMargin--) | Получает верхнее поле артефакта. |
| [getType()](#getType--) | Получает тип артефакта. |
| [getValue(String name)](#getValue-java.lang.String-) | Получает пользовательское значение артефакта. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | Если правда Артефакт размещается за содержимым страницы. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeValue(String name)](#removeValue-java.lang.String-) | Удалить пользовательское значение из артефакта. |
| [saveUpdates()](#saveUpdates--) | Сохраняет в артефакте все обновления, сделанные после вызова BeginUpdates(). |
| [setArtifactHorizontalAlignment(int value)](#setArtifactHorizontalAlignment-int-) | Получает горизонтальное выравнивание артефакта. |
| [setArtifactVerticalAlignment(int value)](#setArtifactVerticalAlignment-int-) | Устанавливает вертикальное выравнивание артефакта. |
| [setBackground(boolean value)](#setBackground-boolean-) | Если правда Артефакт размещается за содержимым страницы. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Устанавливает нижнее поле артефакта. |
| [setCustomSubtype(String value)](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | Устанавливает имя типа артефакта. |
| [setImage(InputStream imageStream)](#setImage-java.io.InputStream-) | Задает изображение артефакта. |
| [setImage(String imageName)](#setImage-java.lang.String-) | Задает изображение артефакта. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Устанавливает левое поле артефакта. |
| [setLinesAndState(String[] text, TextState textState)](#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-) | Установите текст и текстовые свойства артефакта. |
| [setOpacity(double value)](#setOpacity-double-) | Устанавливает непрозрачность артефакта. |
| [setPdfPage(Page page)](#setPdfPage-com.aspose.pdf.Page-) | Устанавливает страницу PDF, которая помещается на страницу документа как артефакт. |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) | Устанавливает положение артефакта. |
| [setRightMargin(double value)](#setRightMargin-double-) | Устанавливает правое поле артефакта. |
| [setRotation(double value)](#setRotation-double-) | Устанавливает угол поворота артефакта. |
| [setSubtype(int value)](#setSubtype-int-) | Устанавливает подтип артефакта. |
| [setText(FormattedText formattedText)](#setText-com.aspose.pdf.facades.FormattedText-) | Задает текст артефакта. |
| [setText(String value)](#setText-java.lang.String-) | Задает текст артефакта. |
| [setTextAndState(String text, TextState textState)](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Установите текст и текстовые свойства артефакта. |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Текстовое состояние для текста артефакта. |
| [setTopMargin(double value)](#setTopMargin-double-) | Устанавливает верхнее поле артефакта. |
| [setType(int value)](#setType-int-) | Устанавливает тип артефакта. |
| [setValue(String name, String value)](#setValue-java.lang.String-java.lang.String-) | Устанавливает пользовательское значение артефакта. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FooterArtifact() {#FooterArtifact--}
```
public FooterArtifact()
```


Создает экземпляр артефакта нижнего колонтитула.

### beginUpdates() {#beginUpdates--}
```
public void beginUpdates()
```


Запустить удаленные обновления. Используйте эту функцию, если вам нужно внести несколько изменений в один и тот же артефакт для повышения производительности. Обычно операторы артефакта изменяются всякий раз, когда изменяется свойство артефакта. Это вызывает изменение содержимого страницы каждый раз, когда артефакт был изменен. Чтобы избежать этого эффекта, поместите все обновления артефактов между вызовами StartUpdates/SaveUpdates. Это позволяет изменить содержимое страницы только один раз.

```
Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1);
  art.beginUpdates();
  art.setOpacity ( 0.3f);
  art.setPosition ( new Point(10,10));
  art.setRotation (30);
  art.saveUpdates();
```

### close() {#close--}
```
public void close()
```


Закрывает все ресурсы, используемые этим документом.

### dispose() {#dispose--}
```
public void dispose()
```


Утилизируйте артефакт.

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
### getArtifactHorizontalAlignment() {#getArtifactHorizontalAlignment--}
```
public int getArtifactHorizontalAlignment()
```


Получает горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Возвращает:**
int - значение HorizontalAlignment
### getArtifactVerticalAlignment() {#getArtifactVerticalAlignment--}
```
public int getArtifactVerticalAlignment()
```


Получает вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Возвращает:**
int — значение вертикального выравнивания.
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Получает нижнее поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Возвращает:**
двойное нижнее поле.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContents() {#getContents--}
```
public List<Operator> getContents()
```


Получает коллекцию внутренних операторов артефакта.

**Возвращает:**
java.util.List<com.aspose.pdf.Operator> — список внутренних операторов артефакта.
### getCustomSubtype() {#getCustomSubtype--}
```
public String getCustomSubtype()
```


Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным подтипом.

**Возвращает:**
java.lang.String — строковое значение
### getCustomType() {#getCustomType--}
```
public String getCustomType()
```


Получает имя типа артефакта. Может использоваться, если тип артефакта нестандартный.

**Возвращает:**
java.lang.String — имя строкового артефакта
### getForm() {#getForm--}
```
public XForm getForm()
```


Получает XForm артефакта (если используется XForm).

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - XForm объект
### getImage() {#getImage--}
```
public XImage getImage()
```


Получает изображение артефакта (если присутствует).

**Возвращает:**
[XImage](../../com.aspose.pdf/ximage) - XImage объект
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Получает левое поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Возвращает:**
double - левое поле артефакта.
### getLines() {#getLines--}
```
public final List<String> getLines()
```


Строки многострочного текстового артефакта.

**Возвращает:**
java.util.List<java.lang.String> — список строк
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Получает непрозрачность артефакта. Возможные значения находятся в диапазоне 0..1.

**Возвращает:**
double - непрозрачность артефакта.
### getPosition() {#getPosition--}
```
public Point getPosition()
```


Получает позицию артефакта. Если это свойство указано, поля и выравнивание игнорируются.

**Возвращает:**
[Point](../../com.aspose.pdf/point) - положение артефакта.
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник артефакта.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Получает правый край артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Возвращает:**
double - правый край артефакта.
### getRotation() {#getRotation--}
```
public double getRotation()
```


Получает угол поворота артефакта.

**Возвращает:**
double - угол поворота артефакта.
### getSubtype() {#getSubtype--}
```
public int getSubtype()
```


Получает подтип артефакта. Если артефакт имеет нестандартный подтип, имя подтипа можно прочитать через CustomSubtype.

**Возвращает:**
int - подтип артефакта.
### getText() {#getText--}
```
public String getText()
```


Получает текст артефакта.

**Возвращает:**
java.lang.String — строковое значение
### getTextState() {#getTextState--}
```
public final TextState getTextState()
```


Текстовое состояние для текста артефакта.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Экземпляр TextState
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Получает верхнее поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Возвращает:**
двойное - верхнее поле артефакта.
### getType() {#getType--}
```
public int getType()
```


Получает тип артефакта.

**Возвращает:**
int - значение типа артефакта.
### getValue(String name) {#getValue-java.lang.String-}
```
public String getValue(String name)
```


Получает пользовательское значение артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя значения. |

**Возвращает:**
java.lang.String — значение или ноль, если значение не существует.
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


Если правда Артефакт размещается за содержимым страницы.

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




### removeValue(String name) {#removeValue-java.lang.String-}
```
public void removeValue(String name)
```


Удалить пользовательское значение из артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского значения, которое нужно удалить. |

### saveUpdates() {#saveUpdates--}
```
public void saveUpdates()
```


Сохраняет в артефакте все обновления, сделанные после вызова BeginUpdates().

### setArtifactHorizontalAlignment(int value) {#setArtifactHorizontalAlignment-int-}
```
public void setArtifactHorizontalAlignment(int value)
```


Получает горизонтальное выравнивание артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | горизонтальное выравнивание артефакта. |

### setArtifactVerticalAlignment(int value) {#setArtifactVerticalAlignment-int-}
```
public void setArtifactVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | вертикальное выравнивание артефакта. |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Если правда Артефакт размещается за содержимым страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Устанавливает нижнее поле артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | нижнее поле. |

### setCustomSubtype(String value) {#setCustomSubtype-java.lang.String-}
```
public void setCustomSubtype(String value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public void setCustomType(String value)
```


Устанавливает имя типа артефакта. Может использоваться, если тип артефакта нестандартный.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое имя артефакта |

### setImage(InputStream imageStream) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream imageStream)
```


Задает изображение артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Поток, содержащий данные изображения. |

### setImage(String imageName) {#setImage-java.lang.String-}
```
public void setImage(String imageName)
```


Задает изображение артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | java.lang.String | Имя файла изображения. |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Устанавливает левое поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | левое поле артефакта. |

### setLinesAndState(String[] text, TextState textState) {#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-}
```
public void setLinesAndState(String[] text, TextState textState)
```


Установите текст и текстовые свойства артефакта. Позволяет указать несколько строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String[] | Массив текстовой строки. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Свойства текста. |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Устанавливает непрозрачность артефакта. Возможные значения находятся в диапазоне 0..1.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | непрозрачность артефакта. |

### setPdfPage(Page page) {#setPdfPage-com.aspose.pdf.Page-}
```
public void setPdfPage(Page page)
```


Устанавливает страницу PDF, которая помещается на страницу документа как артефакт.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница, размещенная как Artifcact. |

### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```


Устанавливает положение артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | положение артефакта. |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Устанавливает правое поле артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | правый край артефакта. |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Устанавливает угол поворота артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | угол поворота артефакта. |

### setSubtype(int value) {#setSubtype-int-}
```
public void setSubtype(int value)
```


Устанавливает подтип артефакта. Если артефакт имеет нестандартный подтип, имя подтипа можно прочитать через CustomSubtype.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | подтип артефакта. |

### setText(FormattedText formattedText) {#setText-com.aspose.pdf.facades.FormattedText-}
```
public void setText(FormattedText formattedText)
```


Задает текст артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект FormattedText, содержащий артефактный текст. |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Задает текст артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTextAndState(String text, TextState textState) {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
```
public void setTextAndState(String text, TextState textState)
```


Установите текст и текстовые свойства артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовая строка. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовое состояние. |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public final void setTextState(TextState value)
```


Текстовое состояние для текста артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Экземпляр TextState |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Устанавливает верхнее поле артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | верхнее поле артефакта. |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Устанавливает тип артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | тип артефакта. |

### setValue(String name, String value) {#setValue-java.lang.String-java.lang.String-}
```
public void setValue(String name, String value)
```


Устанавливает пользовательское значение артефакта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского значения. |
| value | java.lang.String | Пользовательское значение в артефакте. |

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
