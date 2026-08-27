---
title: "set_license"
second_title: "Aspose.PDF pour Rust via C++"
description: "Définit la licence à l'aide du nom de fichier."
type: docs
url: /fr/rust-cpp/core/set_license/
---

_Définit la licence à l'aide du nom de fichier._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Définir la licence avec le nom de fichier
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Vous pouvez maintenant travailler avec le document PDF sous licence
    // ...

    Ok(())
}

```