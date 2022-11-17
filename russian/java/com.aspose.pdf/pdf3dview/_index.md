---
title: PDF3DView
second_title: Aspose.PDF для справки по Java API
description: Класс PDF3DView.
type: docs
weight: 252
url: /ru/java/com.aspose.pdf/pdf3dview/
---
**Наследование:**
java.lang.Object
```
public class PDF3DView
```

Класс PDF3DView.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName)](#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.Matrix3D-double-java.lang.String-) | Инициализирует новый экземпляр класса PDF3DView. |
| [PDF3DView(IDocument doc, PDF3DView view, String viewName)](#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.PDF3DView-java.lang.String-) | Инициализирует новый экземпляр класса PDF3DView. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackGroundColor()](#getBackGroundColor--) | Получает или задает цвет фона поля зрения. |
| [getCameraOrbit()](#getCameraOrbit--) | Получает или задает орбиту обзора камеры. |
| [getCameraPosition()](#getCameraPosition--) | Получает или задает положение камеры. |
| [getClass()](#getClass--) |  |
| [getCrossSectionsArray()](#getCrossSectionsArray--) | Получает массив поперечных сечений представления. |
| [getLightingScheme()](#getLightingScheme--) | Получает или задает схему освещения представления. |
| [getRenderMode()](#getRenderMode--) | Получает или задает режим рендеринга представления. |
| [getViewName()](#getViewName--) | Получает или задает имя представления. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackGroundColor(Color value)](#setBackGroundColor-com.aspose.pdf.Color-) | Получает или задает цвет фона поля зрения. |
| [setCameraOrbit(double value)](#setCameraOrbit-double-) | Получает или задает орбиту обзора камеры. |
| [setCameraPosition(Matrix3D value)](#setCameraPosition-com.aspose.pdf.Matrix3D-) | Получает или задает положение камеры. |
| [setLightingScheme(PDF3DLightingScheme value)](#setLightingScheme-com.aspose.pdf.PDF3DLightingScheme-) | Получает или задает схему освещения представления. |
| [setRenderMode(PDF3DRenderMode value)](#setRenderMode-com.aspose.pdf.PDF3DRenderMode-) | Получает или задает режим рендеринга представления. |
| [setViewName(String value)](#setViewName-java.lang.String-) | Получает или задает имя представления. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName) {#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.Matrix3D-double-java.lang.String-}
```
public PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName)
```


Инициализирует новый экземпляр класса PDF3DView.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Документ. |
| cameraPosition | [Matrix3D](../../com.aspose.pdf/matrix3d) | Положение камеры. |
| cameraOrbit | double | Орбита камеры. |
| viewName | java.lang.String | Имя представления. |

### PDF3DView(IDocument doc, PDF3DView view, String viewName) {#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.PDF3DView-java.lang.String-}
```
public PDF3DView(IDocument doc, PDF3DView view, String viewName)
```


Инициализирует новый экземпляр класса PDF3DView.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Документ. |
| view | [PDF3DView](../../com.aspose.pdf/pdf3dview) | Вид. |
| viewName | java.lang.String | Имя представления. |

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
### getBackGroundColor() {#getBackGroundColor--}
```
public Color getBackGroundColor()
```


Получает или задает цвет фона поля зрения.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Значение цвета: цвет заднего фона поля зрения.
### getCameraOrbit() {#getCameraOrbit--}
```
public double getCameraOrbit()
```


Получает или задает орбиту обзора камеры.

**Возвращает:**
double - двойное значение: орбита обзора камеры.
### getCameraPosition() {#getCameraPosition--}
```
public Matrix3D getCameraPosition()
```


Получает или задает положение камеры.

**Возвращает:**
[Matrix3D](../../com.aspose.pdf/matrix3d) - Объект Matrix3D: положение камеры.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCrossSectionsArray() {#getCrossSectionsArray--}
```
public PDF3DCrossSectionArray getCrossSectionsArray()
```


Получает массив поперечных сечений представления.

**Возвращает:**
[PDF3DCrossSectionArray](../../com.aspose.pdf/pdf3dcrosssectionarray) - Значение PDF3DCrossSectionArray: массив поперечных сечений вида.
### getLightingScheme() {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```


Получает или задает схему освещения представления.

**Возвращает:**
[PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) - Объект PDF3DLightingScheme: схема освещения вида.
### getRenderMode() {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```


Получает или задает режим рендеринга представления.

**Возвращает:**
[PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) - Значение PDF3DRenderMode: режим рендеринга просмотра.
### getViewName() {#getViewName--}
```
public String getViewName()
```


Получает или задает имя представления.

**Возвращает:**
java.lang.String — объект String — имя представления.
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




### setBackGroundColor(Color value) {#setBackGroundColor-com.aspose.pdf.Color-}
```
public void setBackGroundColor(Color value)
```


Получает или задает цвет фона поля зрения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | : Цвет фона поля зрения. |

### setCameraOrbit(double value) {#setCameraOrbit-double-}
```
public void setCameraOrbit(double value)
```


Получает или задает орбиту обзора камеры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Орбита обзора камеры. |

### setCameraPosition(Matrix3D value) {#setCameraPosition-com.aspose.pdf.Matrix3D-}
```
public void setCameraPosition(Matrix3D value)
```


Получает или задает положение камеры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix3D](../../com.aspose.pdf/matrix3d) | : Matrix3D - положение камеры в поле зрения. |

### setLightingScheme(PDF3DLightingScheme value) {#setLightingScheme-com.aspose.pdf.PDF3DLightingScheme-}
```
public void setLightingScheme(PDF3DLightingScheme value)
```


Получает или задает схему освещения представления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) | Объект PDF3DLightingScheme: схема освещения вида. |

### setRenderMode(PDF3DRenderMode value) {#setRenderMode-com.aspose.pdf.PDF3DRenderMode-}
```
public void setRenderMode(PDF3DRenderMode value)
```


Получает или задает режим рендеринга представления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) | : Объект PDF3DRenderMode, режим визуализации. |

### setViewName(String value) {#setViewName-java.lang.String-}
```
public void setViewName(String value)
```


Получает или задает имя представления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | : имя представления. |

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
