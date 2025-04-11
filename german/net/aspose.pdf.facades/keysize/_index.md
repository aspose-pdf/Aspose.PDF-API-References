---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.KeySize-Enum. Definiert verschiedene Schlüssellängen, die zur Verschlüsselung von PDF-Dokumenten verwendet werden können
type: docs
weight: 4390
url: /de/net/aspose.pdf.facades/keysize/
---
## KeySize-Enumeration

Definiert verschiedene Schlüssellängen, die zur Verschlüsselung von PDF-Dokumenten verwendet werden können.

```csharp
public enum KeySize
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| x40 | `0` | 40-Bit-Schlüssel. Eine solche Schlüssellänge wird mit dem RC4-Algorithmus verwendet und bietet ein niedriges Sicherheitsniveau. Dennoch können alte Versionen von PDF-Dokumenten nur mit solchen Schlüsseln (v. 1.3 und niedriger) verschlüsselt werden; |
| x128 | `1` | 128-Bit-Schlüssel. Sowohl RC4- als auch AES-Algorithmen können eine solche Schlüssellänge verwenden. |
| x256 | `2` | 256-Bit-Schlüssel. Eine solche Schlüssellänge kann nur mit AES verwendet werden und wird von den letzten Versionen des Adobe Readers (ab v.9) erkannt. |

### Siehe auch

* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)