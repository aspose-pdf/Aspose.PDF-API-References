---
title: Form
second_title: Aspose.PDF per .NET API Reference
description: Classe che rappresenta loggetto modulo.
type: docs
weight: 3020
url: /it/net/aspose.pdf.forms/form/
---
## Form class

Classe che rappresenta l'oggetto modulo.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Se impostato, tutti i campi del modulo verranno ricalcolati quando viene modificato un campo. Il valore predefinito è vero. Impostare su false per aumentare le prestazioni durante la compilazione di moduli con una grande quantità di campi calcolati. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Se impostato, i campi modulo assenti verranno creati automaticamente se presenti nelle annotazioni. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Consente di impostare l'ordine di calcolo del campo. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Ottiene il numero dei campi in questo modulo. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Ottiene o imposta l'aspetto predefinito del modulo (oggetto che descrive il carattere, la dimensione del testo e il colore predefiniti per i campi del modulo). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Ottiene le risorse predefinite inserite in questo modulo. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Se questa proprietà è true, verranno disegnati ulteriori rettangoli di confine rossi per gli elementi Xfa exclGroup containers Questa proprietà è stata introdotta a causa dell'assenza di analoghi per exclGroup durante la conversione della rappresentazione Xfa delle forme in standard. È falsa per impostazione predefinita. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Ottiene l'elenco di tutti i campi nel livello più basso della forma gerarchica. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Se questa proprietà è vera, il valore della chiave NeedsRendering verrà ignorato durante la conversione da modulo XFA in modulo standard. È falso per impostazione predefinita. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Restituisce vero se l'oggetto è thread-safe. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Ottiene il campo del modulo in base al nome del campo. Genera un'eccezione se il campo non è stato trovato. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Se questa proprietà è vera, il dizionario "Perms" verrà rimosso dal documento pdf dopo la conversione di documenti dinamici in standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione di campi obbligatori in Adobe Acrobat Reader. È false per impostazione predefinita. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Se impostato, il documento contiene firme che possono essere invalidate se il file viene salvato (scritto) in modo da alterarne il contenuto precedente, invece di un aggiornamento incrementale. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Se impostato, il documento contiene almeno un campo firma. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Restituisce l'oggetto di sincronizzazione. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Ottiene il tipo del modulo. I valori possibili sono: Standard, Statico, Dinamico. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Ottiene i dati XFA del modulo (se presente). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Aggiunge il campo al modulo. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Aggiunge il campo al modulo. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Aggiunge un nuovo campo al modulo; Se questo campo è già inserito in un altro o in questo modulo, viene creata la copia del campo. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Aggiunge un aspetto aggiuntivo del campo alla pagina specificata del documento nella posizione specificata. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Imposta XFA del modulo sul valore specificato. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Copia i campi inseriti nel modulo nell'array. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Elimina campo dal modulo. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Elimina il campo dal modulo in base al nome. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Rimuove tutti i campi del modulo e ne inserisce i valori direttamente nella pagina. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Ottiene l'enumerazione dei campi modulo. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Restituisce i campi all'interno del rettangolo specificato. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Verifica se il modulo ha già specificato il campo. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Determina se il campo con il nome specificato è già stato aggiunto al Form. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | I moduli possono contenere informazioni sulla firma, ovvero possono essere firmati o non firmati. E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno. Questa proprietà indica al convertitore del modulo (ad esempio durante la conversione da modulo XFA a modulo standard) se il modulo risultato deve essere reso come firmato o come non firmato. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Classe che descrive le impostazioni per la procedura di conversione dei moduli. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | I moduli possono contenere informazioni sulla firma e possono essere firmati o non firmati. A volte la visualizzazione dei moduli nel visualizzatore deve dipendere dal fatto che il modulo sia firmato o meno. Questo enum enumera le possibili modalità di rendering durante la conversione del tipo di modulo rispetto al segno. |

### Guarda anche

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* spazio dei nomi [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
