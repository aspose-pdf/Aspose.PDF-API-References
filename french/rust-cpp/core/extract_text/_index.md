---
title: "extract_text"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le contenu du PDF-document en texte brut."
type: docs
url: /fr/rust-cpp/core/extract_text/
---

_Renvoie le contenu du PDF-document en texte brut._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Renvoie le contenu du PDF-document en texte brut
    let txt = pdf.extract_text()?;

    // Imprimer le texte extrait
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```