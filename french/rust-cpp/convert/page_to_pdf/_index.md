---
title: "page_to_pdf"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre la page spécifiée en tant que document PDF."
type: docs
url: /fr/rust-cpp/convert/page_to_pdf/
---

_Convertit et enregistre la page spécifiée en tant que document PDF._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Convertir et enregistrer la page spécifiée en tant que document PDF
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```