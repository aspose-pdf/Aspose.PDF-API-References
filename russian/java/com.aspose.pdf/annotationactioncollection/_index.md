---
title: AnnotationActionCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет коллекцию действий аннотации.
type: docs
weight: 16
url: /ru/java/com.aspose.pdf/annotationactioncollection/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseActionCollection](../../com.aspose.pdf/baseactioncollection)
```
public final class AnnotationActionCollection extends BaseActionCollection
```

Представляет коллекцию действий аннотации.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOnCalculate()](#getOnCalculate--) | Получает действие для вычисления значения поля. |
| [getOnClosePage()](#getOnClosePage--) | Получает действие, которое должно быть выполнено при закрытии страницы, содержащей аннотацию. |
| [getOnEnter()](#getOnEnter--) | Получает действие, которое должно быть выполнено, когда курсор входит в активную область аннотации. |
| [getOnExit()](#getOnExit--) | Получает действие, которое должно быть выполнено, когда курсор покидает активную область аннотации. |
| [getOnFormat()](#getOnFormat--) | Получает действие, которое необходимо выполнить для форматирования значения поля. |
| [getOnHidePage()](#getOnHidePage--) | Получает действие, которое должно быть выполнено, когда страница, содержащая аннотацию, больше не отображается в пользовательском интерфейсе приложения просмотра. |
| [getOnLostFocus()](#getOnLostFocus--) | Получает действие, которое должно быть выполнено, когда аннотация теряет фокус ввода. |
| [getOnModifyCharacter()](#getOnModifyCharacter--) | Получает действие, которое должно быть выполнено, когда пользователь изменяет символ поля. |
| [getOnOpenPage()](#getOnOpenPage--) | Получает действие, которое должно быть выполнено при открытии страницы, содержащей аннотацию. |
| [getOnPressMouseBtn()](#getOnPressMouseBtn--) | Получает действие, которое будет выполняться при нажатии кнопки мыши внутри активной области аннотации. |
| [getOnReceiveFocus()](#getOnReceiveFocus--) | Получает действие, которое должно быть выполнено, когда аннотация получает фокус ввода. |
| [getOnReleaseMouseBtn()](#getOnReleaseMouseBtn--) | Получает действие, которое будет выполняться при отпускании кнопки мыши внутри активной области аннотации. |
| [getOnShowPage()](#getOnShowPage--) | Получите действие, которое будет выполнено, когда страница, содержащая аннотацию, станет видимой в пользовательском интерфейсе приложения просмотра. |
| [getOnValidate()](#getOnValidate--) | Получает действие, которое должно быть выполнено, когда пользователь изменяет содержимое поля. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeActions()](#removeActions--) | Удаляет все действия аннотации. |
| [setOnCalculate(PdfAction value)](#setOnCalculate-com.aspose.pdf.PdfAction-) | Задает действие для вычисления значения поля. |
| [setOnClosePage(PdfAction value)](#setOnClosePage-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться при закрытии страницы, содержащей аннотацию. |
| [setOnEnter(PdfAction value)](#setOnEnter-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться, когда курсор входит в активную область аннотации. |
| [setOnExit(PdfAction value)](#setOnExit-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться, когда курсор покидает активную область аннотации. |
| [setOnFormat(PdfAction value)](#setOnFormat-com.aspose.pdf.PdfAction-) | Задает действие, которое необходимо выполнить для форматирования значения поля. |
| [setOnHidePage(PdfAction value)](#setOnHidePage-com.aspose.pdf.PdfAction-) | Задает действие, выполняемое, когда страница, содержащая аннотацию, больше не отображается в пользовательском интерфейсе приложения просмотра. |
| [setOnLostFocus(PdfAction value)](#setOnLostFocus-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться, когда аннотация теряет фокус ввода. |
| [setOnModifyCharacter(PdfAction value)](#setOnModifyCharacter-com.aspose.pdf.PdfAction-) | Устанавливает действие, которое будет выполняться, когда пользователь изменяет символ поля. |
| [setOnOpenPage(PdfAction value)](#setOnOpenPage-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться при открытии страницы, содержащей аннотацию. |
| [setOnPressMouseBtn(PdfAction value)](#setOnPressMouseBtn-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться при нажатии кнопки мыши внутри активной области аннотации. |
| [setOnReceiveFocus(PdfAction value)](#setOnReceiveFocus-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться, когда аннотация получит фокус ввода. |
| [setOnReleaseMouseBtn(PdfAction value)](#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться при отпускании кнопки мыши внутри активной области аннотации. |
| [setOnShowPage(PdfAction value)](#setOnShowPage-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться, когда страница, содержащая аннотацию, станет видимой в пользовательском интерфейсе приложения просмотра. |
| [setOnValidate(PdfAction value)](#setOnValidate-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться, когда пользователь изменяет содержимое поля. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getOnCalculate() {#getOnCalculate--}
```
public PdfAction getOnCalculate()
```


Получает действие для вычисления значения поля.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - действие для вычисления значения поля.
### getOnClosePage() {#getOnClosePage--}
```
public PdfAction getOnClosePage()
```


Получает действие, которое должно быть выполнено при закрытии страницы, содержащей аннотацию.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnEnter() {#getOnEnter--}
```
public PdfAction getOnEnter()
```


Получает действие, которое должно быть выполнено, когда курсор входит в активную область аннотации.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnExit() {#getOnExit--}
```
public PdfAction getOnExit()
```


Получает действие, которое должно быть выполнено, когда курсор покидает активную область аннотации.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnFormat() {#getOnFormat--}
```
public PdfAction getOnFormat()
```


Получает действие, которое необходимо выполнить для форматирования значения поля.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - действие, которое необходимо выполнить для форматирования значения поля.
### getOnHidePage() {#getOnHidePage--}
```
public PdfAction getOnHidePage()
```


Получает действие, которое должно быть выполнено, когда страница, содержащая аннотацию, больше не отображается в пользовательском интерфейсе приложения просмотра.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnLostFocus() {#getOnLostFocus--}
```
public PdfAction getOnLostFocus()
```


Получает действие, которое должно быть выполнено, когда аннотация теряет фокус ввода.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnModifyCharacter() {#getOnModifyCharacter--}
```
public PdfAction getOnModifyCharacter()
```


Получает действие, которое должно быть выполнено, когда пользователь изменяет символ поля.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - действие, выполняемое при изменении пользователем символа поля.
### getOnOpenPage() {#getOnOpenPage--}
```
public PdfAction getOnOpenPage()
```


Получает действие, которое должно быть выполнено при открытии страницы, содержащей аннотацию.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnPressMouseBtn() {#getOnPressMouseBtn--}
```
public PdfAction getOnPressMouseBtn()
```


Получает действие, которое будет выполняться при нажатии кнопки мыши внутри активной области аннотации.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnReceiveFocus() {#getOnReceiveFocus--}
```
public PdfAction getOnReceiveFocus()
```


Получает действие, которое должно быть выполнено, когда аннотация получает фокус ввода.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnReleaseMouseBtn() {#getOnReleaseMouseBtn--}
```
public PdfAction getOnReleaseMouseBtn()
```


Получает действие, которое будет выполняться при отпускании кнопки мыши внутри активной области аннотации.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnShowPage() {#getOnShowPage--}
```
public PdfAction getOnShowPage()
```


Получите действие, которое будет выполнено, когда страница, содержащая аннотацию, станет видимой в пользовательском интерфейсе приложения просмотра.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnValidate() {#getOnValidate--}
```
public PdfAction getOnValidate()
```


Получает действие, которое должно быть выполнено, когда пользователь изменяет содержимое поля.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - действие, выполняемое при изменении пользователем содержимого поля.
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




### removeActions() {#removeActions--}
```
public void removeActions()
```


Удаляет все действия аннотации.

### setOnCalculate(PdfAction value) {#setOnCalculate-com.aspose.pdf.PdfAction-}
```
public void setOnCalculate(PdfAction value)
```


Задает действие для вычисления значения поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | действие для вычисления значения поля. |

### setOnClosePage(PdfAction value) {#setOnClosePage-com.aspose.pdf.PdfAction-}
```
public void setOnClosePage(PdfAction value)
```


Задает действие, которое будет выполняться при закрытии страницы, содержащей аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnEnter(PdfAction value) {#setOnEnter-com.aspose.pdf.PdfAction-}
```
public void setOnEnter(PdfAction value)
```


Задает действие, которое будет выполняться, когда курсор входит в активную область аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnExit(PdfAction value) {#setOnExit-com.aspose.pdf.PdfAction-}
```
public void setOnExit(PdfAction value)
```


Задает действие, которое будет выполняться, когда курсор покидает активную область аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnFormat(PdfAction value) {#setOnFormat-com.aspose.pdf.PdfAction-}
```
public void setOnFormat(PdfAction value)
```


Задает действие, которое необходимо выполнить для форматирования значения поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | действие, которое необходимо выполнить для форматирования значения поля. |

### setOnHidePage(PdfAction value) {#setOnHidePage-com.aspose.pdf.PdfAction-}
```
public void setOnHidePage(PdfAction value)
```


Задает действие, выполняемое, когда страница, содержащая аннотацию, больше не отображается в пользовательском интерфейсе приложения просмотра.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnLostFocus(PdfAction value) {#setOnLostFocus-com.aspose.pdf.PdfAction-}
```
public void setOnLostFocus(PdfAction value)
```


Задает действие, которое будет выполняться, когда аннотация теряет фокус ввода.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnModifyCharacter(PdfAction value) {#setOnModifyCharacter-com.aspose.pdf.PdfAction-}
```
public void setOnModifyCharacter(PdfAction value)
```


Устанавливает действие, которое будет выполняться, когда пользователь изменяет символ поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | действие, которое должно быть выполнено, когда пользователь изменяет символ поля. |

### setOnOpenPage(PdfAction value) {#setOnOpenPage-com.aspose.pdf.PdfAction-}
```
public void setOnOpenPage(PdfAction value)
```


Задает действие, которое будет выполняться при открытии страницы, содержащей аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnPressMouseBtn(PdfAction value) {#setOnPressMouseBtn-com.aspose.pdf.PdfAction-}
```
public void setOnPressMouseBtn(PdfAction value)
```


Задает действие, которое будет выполняться при нажатии кнопки мыши внутри активной области аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnReceiveFocus(PdfAction value) {#setOnReceiveFocus-com.aspose.pdf.PdfAction-}
```
public void setOnReceiveFocus(PdfAction value)
```


Задает действие, которое будет выполняться, когда аннотация получит фокус ввода.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnReleaseMouseBtn(PdfAction value) {#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-}
```
public void setOnReleaseMouseBtn(PdfAction value)
```


Задает действие, которое будет выполняться при отпускании кнопки мыши внутри активной области аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnShowPage(PdfAction value) {#setOnShowPage-com.aspose.pdf.PdfAction-}
```
public void setOnShowPage(PdfAction value)
```


Задает действие, которое будет выполняться, когда страница, содержащая аннотацию, станет видимой в пользовательском интерфейсе приложения просмотра.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setOnValidate(PdfAction value) {#setOnValidate-com.aspose.pdf.PdfAction-}
```
public void setOnValidate(PdfAction value)
```


Задает действие, которое будет выполняться, когда пользователь изменяет содержимое поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | действие, выполняемое при изменении пользователем содержимого поля. |

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
