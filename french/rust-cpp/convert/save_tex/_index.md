---
title: "save_tex"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le document PDF précédemment ouvert en tant que document TeX."
type: docs
url: /fr/rust-cpp/convert/save_tex/
---

_Convertit et enregistre le document PDF précédemment ouvert en tant que document TeX._

```rust
pub fn save_tex(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir et enregistrer le document PDF précédemment ouvert en tant que document TeX
    pdf.save_tex("sample.tex")?;

    Ok(())
}

```