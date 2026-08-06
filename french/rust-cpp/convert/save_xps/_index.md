---
title: "save_xps"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le document PDF précédemment ouvert en tant que document XPS."
type: docs
url: /fr/rust-cpp/convert/save_xps/
---

_Convertit et enregistre le document PDF précédemment ouvert en tant que document XPS._

```rust
pub fn save_xps(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir et enregistrer le document PDF précédemment ouvert en tant que document XPS
    pdf.save_xps("sample.xps")?;

    Ok(())
}

```