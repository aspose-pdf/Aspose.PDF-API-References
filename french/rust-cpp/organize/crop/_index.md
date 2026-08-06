---
title: "recadrer"
second_title: "Aspose.PDF pour Rust via C++"
description: "Recadre les pages d'un PDF-document."
type: docs
url: /fr/rust-cpp/organize/crop/
---

_Recadre les pages d'un PDF-document._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Recadrer les pages d'un PDF-document
    pdf.crop(10.5)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```