---
title: "Класс LoadOptions.ResourceLoadingResult"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.LoadOptionsResourceLoadingResult class. Результат пользовательской загрузки ресурса"
type: docs
weight: 6290
url: /ru/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Результат пользовательской загрузки ресурса

```csharp
public class ResourceLoadingResult
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Создаёт экземпляр результата загрузки |

## Свойства

| Имя | Описание |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Бинарные данные, загруженные с помощью пользовательского загрузчика, — их необходимо установить после загрузки |

## Поля

| Имя | Описание |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Иногда кодировка ресурса известна после или во время загрузки. В таком случае пользовательский код может передать конвертеру эту информацию через данный параметр. Вы можете оставить значение null в этом параметре, если кодировка неизвестна или не имеет значения. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Иногда по какой‑то причине невозможно загрузить запрашиваемый ресурс. Недоступность ресурса часто не приводит к сбою конвертации, и результирующий документ всё равно может быть создан (хотя, возможно, в несколько худшем качестве, без изображений и т.д.). Если во время загрузки возникло исключение, просто перехватите его и поместите в этот параметр — иногда эта информация полезна конвертеру для формирования результата. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Иногда по некоторым причинам загрузка не должна происходить пользовательским кодом. В таком случае установите этот флаг в значение True. Тогда конвертер попытается использовать внутренний загрузчик ресурсов по умолчанию, чтобы получить результат (как это происходит, когда пользовательская стратегия не задана). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Иногда информация о MIME‑типе загруженного ресурса полезна конвертеру. Вы можете указать MIME‑тип (если он известен после загрузки) в этом параметре. Пожалуйста, оставьте параметр равным null, когда MIME‑тип неизвестен или его не требуется указывать. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


