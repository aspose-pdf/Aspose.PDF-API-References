---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Metodo di licenza. Licenza il componente
type: docs
weight: 20
url: /it/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licenza il componente.

```csharp
public void SetLicense(string licenseName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | String | Può essere un nome di file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

## Osservazioni

Cerca di trovare la licenza nei seguenti luoghi:

1. Percorso esplicito.

2. La cartella che contiene l'assembly del componente Aspose.

3. La cartella che contiene l'assembly chiamante del cliente.

4. La cartella che contiene l'assembly di avvio (entry).

5. Una risorsa incorporata nell'assembly chiamante del cliente.

**Nota:** Sul .NET Compact Framework, cerca di trovare la licenza solo in questi luoghi:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del cliente.

[Java]

2. La cartella che contiene il file JAR del componente Aspose.

3. La cartella che contiene il file JAR chiamante del cliente.

### Vedi Anche

* classe [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenza il componente.

```csharp
public void SetLicense(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Uno stream che contiene la licenza. |

## Osservazioni

Usa questo metodo per caricare una licenza da uno stream.

### Vedi Anche

* classe [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)