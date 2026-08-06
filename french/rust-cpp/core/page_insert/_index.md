---
title: "page_insert"
second_title: "Aspose.PDF pour Rust via C++"
description: "Insère une nouvelle page à la position spécifiée dans le PDF-document."
type: docs
url: /fr/rust-cpp/core/page_insert/
---

_Insère une nouvelle page à la position spécifiée dans le PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Insérer une nouvelle page à la position spécifiée dans le PDF-document
    pdf.page_insert(1)?;

    // Enregistrer le PDF-document précédemment ouvert
    pdf.save()?;

    Ok(())
}

```