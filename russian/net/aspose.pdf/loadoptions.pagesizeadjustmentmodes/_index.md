---
title: LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF для справочника API .NET
description: ВНИМАНИЕ Функция реализована но еще не размещена в общедоступном API поскольку для образца документа обнаружена проблема с блокировщиком в слое OSHARED. Представляет режим использования размера страницы во время преобразования.  так что это позволяет вписать размер страницы required . Но иногда в контенте указаны позиции по горизонтали или размер который не позволяет поместить контент в требуемый размер страницы. В этом случае мы можем определить что делать в этом случае т. итоговый PDF-документ.
type: docs
weight: 3970
url: /ru/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ВНИМАНИЕ! Функция реализована, но еще не размещена в общедоступном API, поскольку для образца документа обнаружена проблема с блокировщиком в слое OSHARED. Представляет режим использования размера страницы во время преобразования. , так что это позволяет вписать размер страницы required . Но иногда в контенте указаны позиции по горизонтали или размер, который не позволяет поместить контент в требуемый размер страницы. В этом случае мы можем определить, что делать в этом случае (т. итоговый PDF-документ).

```csharp
public enum PageSizeAdjustmentModes
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | В этом режиме страницы результатов будут иметь необходимый размер страницы, определенный в LoadOptions, независимо от того, выходит ли контент после преобразования за границы страницы или нет. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Этот режим определяет такое поведение: после получения результата конвертации, и обнаружения факта усечения некоторого контента, ширина окна просмотра увеличивается до размера содержимого и конвертация повторяется. Этот режим позволяет получить меньшее количество страниц в результате в такой случай, но требует повторного рендеринга (и, следовательно, большего времени обработки). |

### Смотрите также

* class [LoadOptions](../loadoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
