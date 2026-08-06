---
title: "page_merge_layers"
second_title: "Aspose.PDF pour Rust via C++"
description: "Fusionne toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié."
type: docs
url: /fr/rust-cpp/organize/page_merge_layers/
---

_Fusionne toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié._

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
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Fusionner toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```