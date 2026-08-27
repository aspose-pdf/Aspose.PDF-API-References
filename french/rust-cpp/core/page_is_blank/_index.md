---
title: "page_is_blank"
second_title: "Aspose.PDF pour Rust via C++"
description: "Retourner si la page est blanche dans le PDF-document."
type: docs
url: /fr/rust-cpp/core/page_is_blank/
---

_Retourne la page vide dans le PDF-document._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document depuis un fichier
    let pdf = Document::open("sample.pdf")?;

    // Spécifiez le numéro de page (indice à partir de 1)
    let page_number = 1;

    // Retourne la page vide dans le PDF-document
    let is_blank = pdf.page_is_blank(page_number)?;

    // Imprimer si la page spécifiée est vide
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```