---
title: "save_n_up"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le document PDF précédemment ouvert en tant que document PDF N-Up."
type: docs
url: /fr/rust-cpp/convert/save_n_up/
---

_Convertit et enregistre le document PDF précédemment ouvert en tant que document PDF N-Up._

```rust
pub fn save_n_up(&self, filename: &str, columns: i32, rows: i32) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file
  * **columns** - the number of columns
  * **rows** - the number of rows

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Convertir et enregistrer le document PDF précédemment ouvert en tant que document PDF N-Up
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```