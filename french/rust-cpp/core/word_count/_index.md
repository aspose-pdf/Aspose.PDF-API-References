---
title: "word_count"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le nombre de mots dans le PDF-document."
type: docs
url: /fr/rust-cpp/core/word_count/
---

_Renvoie le nombre de mots dans le PDF-document._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // Renvoie le nombre de mots dans le PDF-document
    let count = pdf.word_count()?;

    // Afficher le nombre de mots
    println!("Word count: {}", count);

    Ok(())
}

```