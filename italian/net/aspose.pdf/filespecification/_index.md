---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification class. Class representing embedded file
type: docs
weight: 4850
url: /it/net/aspose.pdf/filespecification/
---
## Classe FileSpecification

Classe che rappresenta un file incorporato.

```csharp
public sealed class FileSpecification : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Crea una nuova specifica di file vuota. |
| [FileSpecification](filespecification/#constructor_3)(string) | Costruttore per FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Costruttore per la specifica di file. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Costruttore per FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Costruttore per FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Costruttore per FileSpecification. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Relazione del file associato. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Ottiene un elemento della collezione della specifica di file. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Ottiene o imposta il file dei contenuti. Questa proprietà restituisce dati caricati in memoria che possono causare un'eccezione di memoria esaurita per dati di grandi dimensioni. Per ridurre l'uso della memoria, si prega di utilizzare StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Ottiene o imposta il testo associato alla specifica di file. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Ottiene o imposta il formato di codifica. Valori possibili: Zip - il file è compresso con ZIP, None - il file non è compresso. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Ottiene il payload crittografato. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Ottiene o imposta il nome del file system. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Se vero, i contenuti del file saranno inclusi nella specifica di file. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Ottiene il sottotipo del file incorporato |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Ottiene o imposta il nome della specifica di file. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Ottiene i parametri del file. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Ottiene i contenuti del file come stream. I contenuti non vengono caricati in memoria, il che consente di ridurre l'uso della memoria. Ma questo stream non supporta il posizionamento e la proprietà Length. Se hai bisogno di queste funzionalità, si prega di utilizzare la proprietà Contents invece. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Ottiene o imposta il nome unicode della specifica di file. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Dispone dei contenuti. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Ottiene un parametro specifico dell'applicazione. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Imposta un parametro specifico dell'applicazione. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)