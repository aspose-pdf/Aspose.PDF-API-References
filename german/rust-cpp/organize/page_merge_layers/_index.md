---
title: "page_merge_layers"
second_title: "Aspose.PDF für Rust über C++"
description: "Führt alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammen."
type: docs
url: /de/rust-cpp/organize/page_merge_layers/
---

_Führt alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammen._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammenführen
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```