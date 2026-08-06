---
title: "flatten"
second_title: "Aspose.PDF pour Rust via C++"
description: "Aplati le document PDF."
type: docs
url: /fr/rust-cpp/organize/flatten/
---

_Aplati le document PDF._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
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