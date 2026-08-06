---
title: "page_character_count"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le nombre de caractères sur la page spécifiée du document PDF."
type: docs
url: /fr/rust-cpp/core/page_character_count/
---

_Renvoie le nombre de caractères sur la page spécifiée du document PDF._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
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

    // Renvoie le nombre de caractères sur la page spécifiée
    let count = pdf.page_character_count(page_number)?;

    // Afficher le nombre de caractères
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```