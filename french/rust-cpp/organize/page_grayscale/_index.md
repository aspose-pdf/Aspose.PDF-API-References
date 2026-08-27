---
title: "page_grayscale"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit une page en noir et blanc."
type: docs
url: /fr/rust-cpp/organize/page_grayscale/
---

_Convertit une page en noir et blanc._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
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

    // Convertir la page en noir et blanc
    pdf.page_grayscale(1)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```