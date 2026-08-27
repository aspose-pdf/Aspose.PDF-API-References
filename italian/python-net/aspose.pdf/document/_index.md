---
title: "Documento"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta il documento PDF"
type: docs
weight: 230
url: /it/python-net/aspose.pdf/document/
---

## Document class

Classe che rappresenta il documento PDF

Il tipo Documento espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Document(input) | Inizializza una nuova istanza della classe Documento |
| Document(input, password, is_managed_stream) | Inizializza una nuova istanza della classe Documento |
| Document(input, is_managed_stream) | Inizializza una nuova istanza della classe Documento |
| Document(filename) | Inizializza una nuova istanza della classe Documento |
| Document(input, password) | Inizializza una nuova istanza della classe Documento |
| Document() | Inizializza un documento vuoto. |
| Document(filename, options) | Inizializza una nuova istanza della classe Documento |
| Document(input, options) | Inizializza una nuova istanza della classe Documento |
| Document(filename, password) | Inizializza una nuova istanza della classe Documento |
| Document(filename, password, is_managed_stream) | Inizializza una nuova istanza della classe Documento |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| java_script | Collezione di JavaScript a livello di documento. |
| is_licensed | Ottiene lo stato di licenza del sistema. Restituisce true se il sistema funziona in modalità licenziata e false altrimenti. |
| page_info | Ottiene o imposta le informazioni della pagina (solo per il generatore, non compilato durante la lettura del documento). |
| enable_signature_sanitization | Ottiene o imposta il flag per gestire la sanificazione dei campi firma. Abilitato per impostazione predefinita. |
| is_pdfa_compliant | Ottiene se il documento è conforme a PDF/A. |
| is_pdf_ua_compliant | Ottiene se il documento è conforme a PDF/UA. |
| is_xref_gaps_allowed | Ottiene o imposta se il documento è conforme a PDF/A. |
| named_destinations | Raccolta di destinazioni nominate nel documento. |
| destinations | Ottiene la raccolta di destinazioni.<br/>            Obsoleta. Si prega di utilizzare NamedDestinations. |
| pdf_format | Ottiene il formato PDF |
| embed_standard_fonts | Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard <br/>            che hanno il flag IsEmbedded impostato su true. Tutti i font PDF possono essere incorporati <br/>            nel documento semplicemente impostando il flag IsEmbedded su true, ma i font PDF standard Type1 sono un'eccezione a questa regola.<br/>            L'incorporamento dei font Type1 standard richiede molto tempo, quindi per incorporare questi font è necessario<br/>            non solo impostare il flag IsEmbedded su true per il font specificato, ma anche impostare <br/>            un flag aggiuntivo a livello di documento - EmbedStandardFonts = true;<br/>            Questa proprietà può essere impostata una sola volta per tutti i font.<br/>            Per impostazione predefinita false. |
| disable_font_license_verifications | Molte operazioni con i font non possono essere eseguite se queste operazioni sono proibite dalla licenza di tale font. <br/>            Ad esempio, alcuni font non possono essere incorporati in un documento PDF se le regole di licenza disabilitano l'incorporamento per quel font. <br/>            Questo flag è usato per disabilitare qualsiasi restrizione di licenza per tutti i font nel documento PDF corrente.<br/>            Prestare attenzione quando si utilizza questo flag. Quando è impostato, significa che la persona che lo imposta, <br/>            si assume tutta la responsabilità di possibili violazioni di licenza/legge. <br/>            Quindi lo fa a proprio rischio. <br/>            È fortemente consigliato usare questo flag solo quando si è pienamente certi di non violare <br/>            la legge sul diritto d'autore. <br/>            Per impostazione predefinita false. |
| font_utilities | istanza di IDocumentFontUtilities |
| collezione | Ottiene la collezione del documento. |
| version | Ottiene una versione di PDF dall'intestazione del file PDF. |
| open_action | Ottiene o imposta l'azione eseguita all'apertura del documento. |
| hide_tool_bar | Ottiene o imposta il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| hide_menubar | Ottiene o imposta il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| hide_window_ui | Ottiene o imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| fit_window | Ottiene o imposta il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| center_window | Ottiene o imposta il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| display_doc_title | Ottiene o imposta il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| pagine | Ottiene o imposta la collezione di pagine del documento.<br/>            Nota che le pagine sono numerate a partire da 1 nella collezione. |
| outlines | Ottiene gli outline del documento. |
| actions | Ottiene le azioni del documento. Questa proprietà è un'istanza della classe DocumentActions che consente di ottenere/impostare le azioni BeforClosing, BeforSaving, ecc. |
| modulo | Ottiene il modulo Acro del documento. |
| embedded_files | Ottiene la collezione di file incorporati nel documento. |
| direction | Ottiene o imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| page_mode | Ottiene o imposta la modalità di pagina, specificando come il documento dovrebbe essere visualizzato all'apertura. |
| non_full_screen_page_mode | Ottiene o imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
| page_layout | Ottiene o imposta il layout della pagina da utilizzare quando il documento viene aperto. |
| duplex | Ottiene o imposta l'opzione di gestione della modalità duplex di stampa da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| file_name | Nome del file PDF che ha generato questo documento |
| info | Ottiene le informazioni del documento. |
| metadata | Metadati del documento.<br/>            (Un documento PDF può includere informazioni generali,<br/>             come il titolo del documento, l'autore e le date di creazione e modifica.<br/>             Tali informazioni globali sul documento (in opposizione al suo contenuto o alla sua struttura) sono chiamate metadati<br/>             e sono destinate ad assistere nella catalogazione e nella ricerca di documenti in database esterni.) |
| logical_structure | Ottiene la struttura logica del documento. |
| handle_signature_change | Genera un'eccezione se il documento viene salvato con modifiche e contiene una firma |
| crypto_algorithm | Ottiene le impostazioni di sicurezza se il documento è crittografato. <br/>            Se il documento non è crittografato, verrà sollevata l'eccezione corrispondente in .net 1.1<br/>            o CryptoAlgorithm sarà null per le altre versioni .net. |
| is_linearized | Ottiene o imposta un valore che indica se il documento è linearizzato. |
| permissions | Ottiene le autorizzazioni del documento. |
| is_encrypted | Ottiene lo stato di crittografia del documento. True se il documento è crittografato. |
| id | Ottiene l'ID. |
| background | Ottiene o imposta il colore di sfondo del documento. |
| optimize_size | Ottiene o imposta il flag di ottimizzazione. Quando le pagine vengono aggiunte al documento, i flussi di risorse uguali nel file risultante sono<br/>            uniti in un unico oggetto PDF se questo flag è impostato. <br/>            Questo consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e requisiti di memoria maggiori.<br/>            Valore predefinito: false. |
| allow_reuse_page_content | Consente di unire i contenuti delle pagine per ottimizzare le dimensioni del documento. Se utilizzato, pagine diverse ma duplicate possono fare riferimento al <br/>            stesso oggetto contenuto. Si noti che questa modalità può causare effetti collaterali, come la modifica del contenuto di una pagina quando un'altra pagina viene modificata. |
| ignore_corrupted_objects | Ottiene o imposta il flag per ignorare gli errori nei file di origine. <br/>            Quando le pagine del documento di origine vengono copiate nel documento di destinazione, il processo di copia viene interrotto con un'eccezione <br/>            se alcuni oggetti nei file di origine sono corrotti quando questo flag è false. <br/>            esempio: dest.Pages.Add(src.Pages);<br/>            Se questo flag è impostato su true, gli oggetti corrotti verranno sostituiti con valori vuoti.<br/>            Per impostazione predefinita: true. |
| page_labels | Ottiene le etichette delle pagine nel documento. |
| enable_object_unload | Ottiene o imposta il flag che consente al documento di essere parzialmente scaricato dalla memoria. <br/>            Questo permette di ridurre l'uso della memoria ma può avere un effetto negativo sulle prestazioni. |
| tagged_content | Ottiene l'accesso al contenuto TaggedPdf. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| save(output) | Memorizza il documento in uno stream. |
| save(output_file_name) | Salva il documento nel file specificato. |
| save() | Memorizza il documento in uno stream. |
| save(options) | Salva il documento con le opzioni di salvataggio. |
| save(output_file_name, format) | Salva il documento con un nuovo nome insieme a un formato di file. |
| save(output_stream, format) | Salva il documento con un nuovo nome insieme a un formato di file. |
| save(output_file_name, options) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| save(output_stream, options) | Salva il documento in uno stream con le opzioni di salvataggio. |
| export_annotations_to_xfdf(file_name) | Esporta tutte le annotazioni del documento in un file XFDF |
| export_annotations_to_xfdf(stream) | Esporta tutte le annotazioni del documento nello stream. |
| send_to(device, output) | Invia l'intero documento al dispositivo di documento per l'elaborazione. |
| send_to(device, from_page, to_page, output) | Invia le pagine specifiche del documento al dispositivo di documento per l'elaborazione. |
| send_to(device, output_file_name) | Invia l'intero documento al dispositivo di documento per l'elaborazione. |
| send_to(device, from_page, to_page, output_file_name) | Invia l'intero documento al dispositivo di documento per l'elaborazione. |
| import_annotations_from_xfdf(file_name) | Importa le annotazioni dal file XFDF al documento. |
| import_annotations_from_xfdf(stream) | Importa le annotazioni dallo stream al documento. |
| validate(output_log_file_name, format) | Convalida il documento nel file specificato. |
| validate(output_log_stream, format) | Convalida il documento nel file specificato. |
| validate(options) | Convalida il documento nel file specificato. |
| convert(output_log_file_name, format, action, transparency_action) | Converti il documento e salva gli errori nel file specificato. |
| convert(output_log_stream, format, action, transparency_action) | Converti il documento e salva gli errori nel file specificato. |
| convert(output_log_file_name, format, action) | Converti il documento e salva gli errori nel file specificato. |
| convert(options) | Converti il documento utilizzando le opzioni di conversione specificate |
| convert(output_log_stream, format, action) | Converti il documento e salva gli errori nel file specificato. |
| convert(fixup, output_log, only_validation, parameters) | Converti il documento applicando il Fixup. |
| convert(fixup, output_log, only_validation, parameters) | Converti il documento applicando il Fixup. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Converte il file di origine nel formato di origine in un file di destinazione nel formato di destinazione. |
| convert(src_stream, load_options, dst_file_name, save_options) | Converte lo stream nel formato di origine in un file di destinazione nel formato di destinazione. |
| convert(src_file_name, load_options, dst_stream, save_options) | Converte lo stream nel formato di origine in un file di destinazione nel formato di destinazione. |
| convert(src_stream, load_options, dst_stream, save_options) | Converte lo stream nel formato di origine in un file di destinazione nel formato di destinazione. |
| flatten() | Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto. |
| flatten(flatten_settings) | Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Cifra il documento. Quindi chiama Save per ottenere la versione cifrata del documento. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Cifra il documento. Quindi chiama Save per ottenere la versione cifrata del documento. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Cifra il documento. Quindi chiama Save per ottenere la versione cifrata del documento. |
| optimize_resources() | Ottimizza le risorse nel documento:<br/>            1. Le risorse che non sono utilizzate nelle pagine del documento vengono rimosse;<br/>            2. Le risorse uguali vengono unite in un unico oggetto; <br/>            3. Gli oggetti non utilizzati vengono eliminati. |
| optimize_resources(strategy) | Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita. |
| bind_xml(file) | Associa xml al documento |
| bind_xml(xml_file, xsl_file) | Associa xml al documento |
| bind_xml(xml_stream, xsl_stream) | Associa xml/xsl al documento |
| bind_xml(stream) | Associa xml/xsl al documento |
| remove_pdfa_compliance() | Rimuove la conformità pdfa dal documento |
| remove_pdf_ua_compliance() | Rimuove la conformità pdfUa dal documento |
| set_title(title) | Imposta titolo per il documento PDF |
| process_paragraphs() | Elabora paragrafi per il generatore. |
| remove_metadata() | Rimuove i metadati dal documento. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Modifica le password del documento. Questa operazione può essere eseguita solo utilizzando la password del proprietario. |
| decrypt() | Decripta il documento. Chiama poi Save per ottenere la versione decriptata del documento. |
| optimize() | Linearizza il documento in modo da<br/>            - aprire la prima pagina il più rapidamente possibile;<br/>            - visualizzare la pagina successiva o seguirne il collegamento il più rapidamente possibile;<br/>            - visualizzare la pagina in modo incrementale man mano che arriva, quando i dati per una pagina vengono trasmessi su un canale lento (visualizzare prima i dati più utili);<br/>            - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata.<br/>            L'invocazione di questo metodo non salva effettivamente il documento. Al contrario, il documento viene solo preparato per avere una struttura ottimizzata,<br/>            chiama poi Save per ottenere il documento ottimizzato. |
| get_catalog_value(key) | Restituisce il valore dell'elemento dal dizionario del catalogo. |
| free_memory() | Libera la memoria |
| save_xml(file) | Salva il documento in XML. |
| get_object_by_id(id) | Ottiene un oggetto con ID specificato nel documento. |
| repair() | Ripara il documento danneggiato. |
| get_xmp_metadata(stream) | Ottieni i metadati XMP dal documento. |
| set_xmp_metadata(stream) | Imposta i metadati XMP del documento. |
| check(do_repair) | Convalida il documento. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Organizza i nodi dell'albero della pagina in un documento in un albero bilanciato.<br/>            Solo se il documento ha più di nodesNumInSubtrees oggetti pagina, altrimenti non fa nulla. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

