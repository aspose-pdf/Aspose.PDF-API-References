---
title: "export_xfdf"
second_title: "Aspose.PDF pour Rust via C++"
description: "Exportations du PDF-document précédemment ouvert avec AcroForm vers un document XFDF avec le nom de fichier."
type: docs
url: /fr/rust-cpp/convert/export_xfdf/
---

_Exportations du PDF-document précédemment ouvert avec AcroForm vers un document XFDF avec le nom de fichier._

```rust
pub fn export_xfdf(&self, filename: &str) -> Result<(), PdfError>
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

    // Exportation du PDF-document précédemment ouvert avec AcroForm vers un document XFDF
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```