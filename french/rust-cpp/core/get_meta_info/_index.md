---
title: "get_meta_info"
second_title: "Aspose.PDF pour Rust via C++"
description: "Obtient la valeur des métadonnées du PDF-document."
type: docs
url: /fr/rust-cpp/core/get_meta_info/
---

_Obtient la valeur des métadonnées du PDF-document._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Obtenir la valeur des métadonnées du PDF-document
    let author = pdf.get_meta_info("Author")?;

    // Imprimer le résultat
    println!("Author: {}", author);

    Ok(())
}

```