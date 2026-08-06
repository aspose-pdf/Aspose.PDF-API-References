---
title: "octets"
second_title: "Aspose.PDF pour Rust via C++"
description: "Renvoie le contenu du document PDF sous forme de vecteur d'octets."
type: docs
url: /fr/rust-cpp/core/bytes/
---

_Renvoie le contenu du document PDF sous forme de vecteur d'octets._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Créer un nouveau PDF-document
    let pdf = Document::new()?;

    // Renvoie le contenu du document PDF sous forme de vecteur d'octets
    let data = pdf.bytes()?;

    // Afficher la longueur du vecteur d'octets
    println!("Length: {}", data.len());

    Ok(())
}

```