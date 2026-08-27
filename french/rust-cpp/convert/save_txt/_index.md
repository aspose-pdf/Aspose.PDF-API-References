---
title: "save_txt"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le PDF-document précédemment ouvert en tant que document TXT."
type: docs
url: /fr/rust-cpp/convert/save_txt/
---

_Convertit et enregistre le PDF-document précédemment ouvert en tant que document TXT._

```rust
pub fn save_txt(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir et enregistrer le PDF-document précédemment ouvert en tant que document Txt
    pdf.save_txt("sample.txt")?;

    Ok(())
}

```