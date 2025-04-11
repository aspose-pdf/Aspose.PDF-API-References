---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationFlags enum. A set of flags specifying various characteristics of the annotation
type: docs
weight: 1440
url: /it/net/aspose.pdf.annotations/annotationflags/
---
## Enumerazione AnnotationFlags

Un insieme di flag che specificano varie caratteristiche dell'annotazione.

```csharp
[Flags]
public enum AnnotationFlags
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | `0` | Valore predefinito. |
| Invisible | `1` | Se impostato, non visualizzare l'annotazione se non appartiene a uno dei tipi di annotazione standard e non è disponibile alcun gestore di annotazioni. Se non impostato, visualizza tale annotazione sconosciuta utilizzando uno stream di apparizione specificato dal suo dizionario di apparizione, se presente. |
| Hidden | `2` | Se impostato, non visualizzare o stampare l'annotazione o consentire interazioni con l'utente, indipendentemente dal tipo di annotazione o dalla disponibilità di un gestore di annotazioni. Nei casi in cui lo spazio sullo schermo è limitato, la possibilità di nascondere e mostrare le annotazioni selettivamente può essere utilizzata in combinazione con gli stream di apparizione per visualizzare informazioni pop-up ausiliarie simili nella funzione ai sistemi di aiuto online. |
| Print | `4` | Se impostato, stampare l'annotazione quando la pagina viene stampata. Se non impostato, non stampare mai l'annotazione, indipendentemente dal fatto che venga visualizzata sullo schermo. Questo può essere utile, ad esempio, per annotazioni che rappresentano pulsanti interattivi, che non avrebbero alcuno scopo significativo sulla pagina stampata. |
| NoZoom | `8` | Se impostato, non scalare l'apparenza dell'annotazione per adattarla alla magnificazione della pagina. La posizione dell'annotazione sulla pagina (definita dall'angolo in alto a sinistra del suo rettangolo di annotazione) rimane fissa, indipendentemente dalla magnificazione della pagina. |
| NoRotate | `10` | Se impostato, non ruotare l'apparenza dell'annotazione per adattarla alla rotazione della pagina. L'angolo in alto a sinistra del rettangolo dell'annotazione rimane in una posizione fissa sulla pagina, indipendentemente dalla rotazione della pagina. |
| NoView | `20` | Se impostato, non visualizzare l'annotazione sullo schermo o consentire interazioni con l'utente. L'annotazione può essere stampata (a seconda dell'impostazione del flag Print) ma dovrebbe essere considerata nascosta ai fini della visualizzazione sullo schermo e dell'interazione con l'utente. |
| ReadOnly | `40` | Se impostato, non consentire all'annotazione di interagire con l'utente. L'annotazione può essere visualizzata o stampata (a seconda delle impostazioni dei flag NoView e Print) ma non dovrebbe rispondere ai clic del mouse o cambiare la sua apparizione in risposta ai movimenti del mouse. Questo flag viene ignorato per le annotazioni widget; la sua funzione è assorbita dal flag ReadOnly del campo modulo associato. |
| Locked | `80` | Se impostato, non consentire la cancellazione dell'annotazione o la modifica delle sue proprietà (inclusi posizione e dimensione) da parte dell'utente. Tuttavia, questo flag non limita le modifiche al contenuto dell'annotazione, come il valore di un campo modulo. |
| ToggleNoView | `100` | Se impostato, invertire l'interpretazione del flag NoView per determinati eventi. Un uso tipico è avere un'annotazione che appare solo quando il cursore del mouse è posizionato sopra di essa. |
| LockedContents | `200` | Se impostato, non consentire la modifica del contenuto dell'annotazione da parte dell'utente. Questo flag non limita la cancellazione dell'annotazione o le modifiche ad altre proprietà dell'annotazione, come posizione e dimensione. |

### Vedi Anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)