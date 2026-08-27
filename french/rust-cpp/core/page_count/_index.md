---
title: "page_count"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le nombre de pages du document PDF."
type: docs
url: /fr/rust-cpp/core/page_count/
---

_Renvoie le nombre de pages du document PDF._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
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

    // Renvoie le nombre de pages du document PDF
    let count = pdf.page_count()?;

    // Imprime le nombre de pages
    println!("Count: {}", count);

    Ok(())
}

```