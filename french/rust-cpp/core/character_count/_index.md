---
title: "character_count"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le nombre de caractères dans le document PDF."
type: docs
url: /fr/rust-cpp/core/character_count/
---

_Renvoie le nombre de caractères dans le document PDF._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Renvoie le nombre de caractères dans le document PDF
    let count = pdf.character_count()?;

    // Afficher le nombre de caractères
    println!("Character count: {}", count);

    Ok(())
}

```