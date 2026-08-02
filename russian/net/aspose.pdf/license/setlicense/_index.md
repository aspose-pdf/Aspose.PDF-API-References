---
title: "License.SetLicense"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод License. Лицензирует компонент"
type: docs
weight: 40
url: /ru/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Лицензирует компонент.

```csharp
public void SetLicense(string licenseName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |

## Примечания

Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка, содержащая сборку компонента Aspose.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (запускную) сборку.

5. Встроенный ресурс в вызывающей сборке клиента.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

[Java]

2. Папка, содержащая JAR‑файл компонента Aspose.

3. Папка, содержащая JAR‑файл вызывающего клиента.

### См. также

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```csharp
public void SetLicense(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, содержащий лицензию. |

## Примечания

Используйте этот метод для загрузки лицензии из потока.

### См. также

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


