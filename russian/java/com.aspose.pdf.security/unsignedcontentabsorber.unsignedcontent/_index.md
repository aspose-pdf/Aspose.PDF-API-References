---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Справочник API Aspose.PDF для Java"
description: "Инкапсулирует элементы неподписанного содержимого, извлечённые из PDF‑документа. Этот класс предоставляет доступ к страницам, полям форм, XForms и аннотациям, которые являются частью неподписанного."
type: docs
weight: 50
url: /ru/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Инкапсулирует элементы неподписанного содержимого, извлечённые из PDF‑документа. Этот класс предоставляет доступ к страницам, полям формы, XForms и аннотациям, которые являются частью неподписанного содержимого в документе.

## Методы

| Метод | Описание |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Возвращает словарь изменённых аннотаций, которые могли быть изменены или добавлены. |
| [getForms](#getForms--) | Возвращает поля формы, которые были инкрементно изменены или добавлены. |
| [getPages](#getPages--) | Возвращает список страниц, содержимое которых неподписано или было инкрементно изменено. Страница считается изменённой, XForms не проверяются и не отображаются в списке XForms. |
| [getXForms](#getXForms--) | Возвращает словарь изменённых объектов XForm, которые могли измениться, хотя сама страница не изменилась (не в списке Pages). |
| [setXForms](#setXForms-java.util.HashMap-) | Словарь изменённых объектов XForm, которые могли измениться, хотя сама страница не изменилась (не в списке Pages). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Возвращает словарь изменённых аннотаций, которые могли быть изменены или добавлены.

**Returns:**
словарь изменённых аннотаций, которые могли быть изменены или добавлены.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Возвращает поля формы, которые были инкрементно изменены или добавлены.

**Returns:**
поля формы, которые были инкрементно изменены или добавлены.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Возвращает список страниц, содержимое которых неподписано или было инкрементно изменено. Страница считается изменённой, XForms не проверяются и не отображаются в списке XForms.

**Returns:**
список страниц, содержимое которых неподписано или было инкрементно изменено.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Возвращает словарь изменённых объектов XForm, которые могли измениться, хотя сама страница не изменилась (не в списке Pages).

**Returns:**
словарь изменённых объектов XForm, которые могли измениться, хотя сама страница не изменилась (не в списке Pages).

### setXForms {#setXForms-java.util.HashMap-}
Словарь изменённых объектов XForm, которые могли измениться, хотя сама страница не изменилась (не в списке Pages).
