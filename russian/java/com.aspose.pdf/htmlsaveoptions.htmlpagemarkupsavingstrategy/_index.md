---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Справочник API Aspose.PDF для Java"
description: "Результат конвертации может содержать одну или несколько HTML‑страниц (которые также могут ссылаться на внешние файлы, такие как изображения или шрифты). Вы можете назначить этому свойству делегат, созданный из."
type: docs
weight: 2110
url: /ru/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Результат конвертации может содержать одну или несколько HTML‑страниц (которые также могут ссылаться на внешние файлы, такие как изображения или шрифты). Вы можете назначить этому свойству делегат, созданный из пользовательского метода, реализующего обработку полученной HTML‑страницы (сам HTML), созданной во время конвертации. В таком случае обработка (например, сохранение в поток или на диск) может быть выполнена в этом пользовательском коде. При этом все необходимые действия по сохранению разметки HTML‑страницы должны быть выполнены в коде предоставленного метода, поскольку сохранение результата в коде конвертера использоваться не будет. Если обработка в том или ином случае по какой‑то причине должна быть выполнена кодом конвертера, а не пользовательским кодом, пожалуйста, установите в пользовательском коде флаг 'CustomProcessingCancelled' переменной параметра 'htmlSavingInfo': он сигнализирует конвертеру, что все необходимые шаги по обработке данного ресурса должны быть выполнены самим конвертером так же, как если бы не было внешнего пользовательского кода сохранения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Внутренний метод beginInvoke |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Внутренний метод endInvoke |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Вызванный метод |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Внутренний метод beginInvoke

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Внутренний метод endInvoke

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Вызванный метод
