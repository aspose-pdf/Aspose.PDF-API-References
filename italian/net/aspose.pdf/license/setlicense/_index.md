---
title: "License.SetLicense"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo License. Concede la licenza al componente"
type: docs
weight: 40
url: /it/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licenzia il componente.

```csharp
public void SetLicense(string licenseName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

## Osservazioni

Cerca di trovare la licenza nei seguenti percorsi:

1. Percorso esplicito.

2. La cartella che contiene l'assembly del componente Aspose.

3. La cartella che contiene l'assembly chiamante del client.

4. La cartella che contiene l'assembly di ingresso (startup).

5. Una risorsa incorporata nell'assembly chiamante del client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del client.

[Java]

2. La cartella che contiene il file JAR del componente Aspose.

3. La cartella che contiene il file JAR chiamante del client.

### Vedi anche

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenzia il componente.

```csharp
public void SetLicense(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Uno stream che contiene la licenza. |

## Osservazioni

Usa questo metodo per caricare una licenza da uno stream.

### Vedi anche

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


