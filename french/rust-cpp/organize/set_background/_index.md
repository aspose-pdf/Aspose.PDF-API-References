---
title: "set_background"
second_title: "Aspose.PDF pour Rust via C++"
description: "Définit la couleur d'arrière-plan du PDF-document en utilisant les valeurs RGB."
type: docs
url: /fr/rust-cpp/organize/set_background/
---

_Définit la couleur d'arrière-plan du PDF-document en utilisant les valeurs RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Définir la couleur d'arrière-plan du PDF-document en utilisant les valeurs RGB
    pdf.set_background(200, 100, 101)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```