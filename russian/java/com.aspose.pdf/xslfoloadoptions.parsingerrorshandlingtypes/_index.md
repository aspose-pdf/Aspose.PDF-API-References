---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Справочник API Aspose.PDF для Java"
description: "Исходный документ XSLFO может содержать ошибки форматирования. Этот enum перечисляет возможные стратегии обработки таких ошибок форматирования."
type: docs
weight: 5790
url: /ru/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Исходный документ XSLFO может содержать ошибки форматирования. Этот enum перечисляет возможные стратегии обработки таких ошибок форматирования.

## Поля

| Поле | Описание |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Это самый гибкий метод — пользовательский код должен предоставить (в свойстве WarningCallback) специальный обработчик, который будет вызываться при обнаружении ошибки форматирования. Этот обработчик может, например, вести журнал или подсчитывать ошибки и будет принимать решение, можно ли продолжать обработку для той или иной ошибки. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | В этом случае конверсия будет остановлена немедленно, и исключение будет выброшено сразу после обнаружения первой ошибки форматирования. |
| [TryIgnore](#TryIgnore) | В этом случае конвертер будет настроен попытаться продолжить конверсию и игнорировать найденные ошибки форматирования. При этом успех не гарантируется, позже в конвертере могут возникнуть серьёзные проблемы, и в таком случае будет выброшено исключение со списком найденных ошибок форматирования. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Это самый гибкий метод — пользовательский код должен предоставить (в свойстве WarningCallback) специальный обработчик, который будет вызываться при обнаружении ошибки форматирования. Этот обработчик может, например, вести журнал или подсчитывать ошибки и будет принимать решение, можно ли продолжать обработку для той или иной ошибки.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

В этом случае конверсия будет остановлена немедленно, и исключение будет выброшено сразу после обнаружения первой ошибки форматирования.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

В этом случае конвертер будет настроен попытаться продолжить конверсию и игнорировать найденные ошибки форматирования. При этом успех не гарантируется, позже в конвертере могут возникнуть серьёзные проблемы, и в таком случае будет выброшено исключение со списком найденных ошибок форматирования.
