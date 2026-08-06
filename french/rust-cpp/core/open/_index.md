---
title: "ouvrir"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ouvre un PDF-document avec le nom de fichier."
type: docs
url: /fr/rust-cpp/core/open/
---

_Ouvre un PDF-document avec le nom de fichier._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document nommé "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```