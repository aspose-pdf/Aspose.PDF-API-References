---
title: "page_merge_layers"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Unisce tutti i livelli nella pagina in un unico livello con il nome del nuovo livello specificato."
type: docs
url: /it/rust-cpp/organize/page_merge_layers/
---

_Unisce tutti i livelli nella pagina in un unico livello con il nome del nuovo livello specificato._

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
    // Apri un PDF-document da file
    let pdf = Document::open("sample.pdf")?;

    // Unisci tutti i livelli nella pagina in un unico livello con il nome del nuovo livello specificato
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```