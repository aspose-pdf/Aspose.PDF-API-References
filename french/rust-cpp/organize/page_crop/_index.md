---
title: "page_recadrer"
second_title: "Aspose.PDF pour Rust via C++"
description: "Recadre une page."
type: docs
url: /fr/rust-cpp/organize/page_crop/
---

_Recadre une page._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Recadrer une page
    pdf.page_crop(1, 1.0)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```