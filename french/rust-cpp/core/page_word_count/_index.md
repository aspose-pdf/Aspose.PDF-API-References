---
title: "page_word_count"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le nombre de mots sur la page spécifiée dans le PDF-document."
type: docs
url: /fr/rust-cpp/core/page_word_count/
---

_Renvoie le nombre de mots sur la page spécifiée dans le PDF-document._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Spécifiez le numéro de page (indice à partir de 1)
    let page_number = 1;

    // Renvoie le nombre de mots sur la page spécifiée
    let count = pdf.page_word_count(page_number)?;

    // Afficher le nombre de mots
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```