---
title: "Form"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta l'oggetto modulo."
type: docs
weight: 110
url: /it/python-net/aspose.pdf.forms/form/
---

## Form class

Classe che rappresenta l'oggetto modulo.

Il tipo Form espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| is_synchronized | Restituisce true se l'oggetto è thread-safe. |
| sync_root | Restituisce l'oggetto di sincronizzazione. |
| auto_recalculate | Se impostato, tutti i campi del modulo verranno ricalcolati quando qualsiasi campo viene modificato. Il valore predefinito è true. Impostare a false per aumentare le prestazioni durante la compilazione del modulo con un gran numero di campi calcolati. |
| auto_restore_form | Se impostato, i campi del modulo assenti verranno creati automaticamente se presenti nelle annotazioni. |
| default_resources | Ottiene le risorse predefinite collocate su questo modulo. |
| default_appearance | Ottiene o imposta l'aspetto predefinito del modulo (oggetto che descrive il carattere predefinito, la dimensione del testo e il colore per i campi del modulo). |
| xfa | Ottiene i dati XFA del modulo (se presenti). |
| ignore_needs_rendering | Se questa proprietà è true, il valore della chiave NeedsRendering verrà ignorato durante la conversione <br/>            del modulo XFA a modulo Standard. È false per impostazione predefinita. |
| remove_permission | Se questa proprietà è true, il dizionario "Perms" verrà rimosso dal documento pdf dopo la conversione <br/>            dei documenti dinamici a standard. Il dizionario "Perms" può contenere regole che disturbano la visualizzazione della selezione di <br/>            campi obbligatori in Adobe Acrobat Reader.<br/>            È false per impostazione predefinita. |
| emulate_requierd_groups | Se questa proprietà è true, verranno disegnati rettangoli di contorno rossi aggiuntivi per i contenitori degli elementi Xfa exclGroup richiesti<br/>            Questa proprietà è stata introdotta a causa dell'assenza di analoghi per l'exclGroup durante la conversione della rappresentazione Xfa dei moduli <br/>            a standard.<br/>            È false per impostazione predefinita. |
| type | Ottiene il tipo del modulo. I valori possibili sono: Standard, Static, Dynamic. |
| fields | Ottiene l'elenco di tutti i campi al livello più basso del modulo gerarchico. |
| signatures_exist | Se impostato, il documento contiene almeno un campo firma. |
| signatures_append_only | Se impostato, il documento contiene firme che potrebbero essere invalidate se il file viene salvato (scritto) in modo da alterare il contenuto precedente, <br/>            contrariamente a un aggiornamento incrementale. |
| sign_dependent_elements_rendering_mode_when_converted | I moduli possono contenere informazioni di firma, cioè possono essere firmati o non firmati.<br/>              E la visualizzazione del modulo a volte deve dipendere dal fatto che il modulo sia firmato o meno.<br/>              Questa proprietà indica al convertitore del modulo (ad es. durante la conversione del modulo XFA a modulo Standard)<br/>              se il modulo risultante deve essere renderizzato come firmato o come non firmato. |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Ottiene il campo del modulo per indice del campo. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| delete(field) | Elimina il campo dal modulo. |
| delete(field_name) | Elimina il campo dal modulo per nome. |
| add(field, page_number) | Aggiunge un campo al modulo. |
| add(field) | Aggiunge un campo al modulo. |
| add(field, partial_name, page_number) | Aggiunge un nuovo campo al modulo; se questo campo è già posizionato su un altro o su questo modulo, viene creata una copia del campo. |
| has_field(field) | Verifica se il modulo ha già il campo specificato. |
| has_field(field_name) | Determina se il campo con il nome specificato è già stato aggiunto al modulo. |
| copy_to(array, index) | Copia i campi posizionati sul modulo in un array. |
| flatten() | Rimuove tutti i campi del modulo e posiziona i loro valori direttamente sulla pagina. |
| add_field_appearance(field, page_number, rect) | Aggiunge un'apparenza aggiuntiva del campo alla pagina specificata del documento nella posizione indicata. |
| get_fields_in_rect(rect) | Restituisce i campi all'interno del rettangolo specificato. |

### Vedi anche

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

