---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: Lo spazio dei nomi Aspose.Pdf.Forms contiene classi che descrivono moduli e vari tipi di campi come casella di testo, casella di selezione, pulsante radio, ecc.
type: docs
weight: 110
url: /it/net/aspose.pdf.forms/
---
Lo **spazio dei nomi Aspose.Pdf.Forms** contiene classi che descrivono moduli (standard, statici, dinamici) e vari tipi di campi come casella di testo, casella di selezione, pulsante radio, ecc.

## Classi

| Classe | Descrizione |
| --- | --- |
| [BarcodeField](./barcodefield/) | Classe che rappresenta il campo codice a barre. |
| [ButtonField](./buttonfield/) | Classe che rappresenta il campo pulsante. |
| [CheckboxField](./checkboxfield/) | Classe che rappresenta il campo checkbox. |
| [ChoiceField](./choicefield/) | Rappresenta la classe base per i campi di scelta. |
| [ComboBoxField](./comboboxfield/) | Classe che rappresenta il campo ComboBox del modulo. |
| [DateField](./datefield/) | Campo data con vista calendario. |
| [DocMDPSignature](./docmdpsignature/) | Rappresenta la classe del documento MDP (rilevamento e prevenzione delle modifiche) tipo di firma. |
| [ExternalSignature](./externalsignature/) | Crea una firma PKCS#7 staccata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili. |
| [Field](./field/) | Classe base per i campi del modulo acro. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo per l'elemento casella di selezione file. |
| [Form](./form/) | Classe che rappresenta l'oggetto modulo. |
| [IconFit](./iconfit/) | Descrive come l'icona dell'annotazione del widget deve essere visualizzata all'interno del suo rettangolo di annotazione. |
| [ListBoxField](./listboxfield/) | Classe che rappresenta il campo ListBox. |
| [NumberField](./numberfield/) | Campo di testo con caratteri validi specificati. |
| [Option](./option/) | Classe che rappresenta l'opzione del campo di scelta. |
| [OptionCollection](./optioncollection/) | Classe che rappresenta la collezione di opzioni del campo di scelta. |
| [PasswordBoxField](./passwordboxfield/) | Classe che descrive il campo di testo per l'inserimento della password. |
| [PKCS1](./pkcs1/) | Rappresenta l'oggetto firma riguardante lo standard PKCS#1. Viene utilizzato l'algoritmo di crittografia RSA e il metodo di digestione SHA-1 per la firma. |
| [PKCS7](./pkcs7/) | Rappresenta l'oggetto PKCS#7 che conforma alla specifica PKCS#7 nell'RFC Internet 2315, PKCS #7: Sintassi del messaggio crittografico, Versione 1.5. Il `digest SHA1` dell'intervallo di byte del documento è racchiuso nel campo PKCS#7 SignedData. |
| [PKCS7Detached](./pkcs7detached/) | Rappresenta l'oggetto PKCS#7 che conforma alla specifica PKCS#7 nell'RFC Internet 2315, PKCS #7: Sintassi del messaggio crittografico, Versione 1.5. Il digest del messaggio firmato originale sull'intervallo di byte del documento è incorporato come il normale campo PKCS#7 SignedData. Nessun dato è racchiuso nel campo PKCS#7 SignedData. |
| [RadioButtonField](./radiobuttonfield/) | Classe che rappresenta il campo pulsante radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe che rappresenta un elemento del campo RadioButton. |
| [RichTextBoxField](./richtextboxfield/) | Classe che descrive il componente editor di testo ricco. |
| [Signature](./signature/) | Una classe astratta che rappresenta l'oggetto firma nel documento pdf. Le firme sono campi con valori di oggetti firma, l'ultimo contiene dati utilizzati per verificare la validità del documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Una classe astratta che rappresenta l'oggetto di aspetto personalizzato della firma. |
| [SignatureField](./signaturefield/) | Rappresenta il campo firma del modulo. |
| [SignHash](./signhash/) | Delegato per firmare in modo personalizzato l'hash del documento. |
| [TextBoxField](./textboxfield/) | Classe che rappresenta il campo casella di testo. |
| [XFA](./xfa/) | Rappresenta il modulo XML riguardante l'Architettura dei Moduli XML (XFA). |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [BoxStyle](./boxstyle/) | Rappresenta gli stili per disegnare il segno nella casella di controllo. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Le autorizzazioni di accesso concesse per questo documento. I valori validi sono: 1 - Non sono consentite modifiche al documento; qualsiasi modifica al documento invalida la firma. 2 - Le modifiche consentite sono la compilazione di moduli, l'istanza di modelli di pagina e la firma; altre modifiche invalidano la firma. 3 - Le modifiche consentite sono le stesse di quelle per 2, così come la creazione, la cancellazione e la modifica delle annotazioni; altre modifiche invalidano la firma. |
| [FormType](./formtype/) | Enumerazione dei possibili tipi di Acro Form. |
| [IconCaptionPosition](./iconcaptionposition/) | Descrive la posizione dell'icona. |
| [ScalingMode](./scalingmode/) | Il tipo di scalatura che deve essere utilizzato. |
| [ScalingReason](./scalingreason/) | Le circostanze in cui l'icona deve essere scalata all'interno del rettangolo di annotazione. |
| [SubjectNameElements](./subjectnameelements/) | Enumerazione che descrive gli elementi nella stringa del soggetto della firma. |
| [Symbology](./symbology/) | Una (Barcode) Simbologia definisce i dettagli tecnici di un particolare tipo di codice a barre: la larghezza delle barre, il set di caratteri, il metodo di codifica, le specifiche del checksum, ecc. |