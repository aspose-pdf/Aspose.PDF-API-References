---
title: "export_fdf"
second_title: "Aspose.PDF pour Rust via C++"
description: "Exporte le PDF-document précédemment ouvert avec AcroForm vers un FDF-document avec le nom de fichier."
type: docs
url: /fr/rust-cpp/convert/export_fdf/
---

_Exporte le PDF-document précédemment ouvert avec AcroForm vers un FDF-document avec le nom de fichier._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Exporter le PDF-document précédemment ouvert avec AcroForm vers un FDF-document
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```