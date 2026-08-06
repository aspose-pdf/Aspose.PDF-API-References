---
title: "save_docx_enhanced"
second_title: "Aspose.PDF pour Rust via C++"
description: "Convertit et enregistre le document PDF précédemment ouvert en tant que document DOCX avec le mode de reconnaissance améliorée (tables et paragraphes entièrement modifiables)."
type: docs
url: /fr/rust-cpp/convert/save_docx_enhanced/
---

_Convertit et enregistre le document PDF précédemment ouvert en tant que document DOCX avec le mode de reconnaissance améliorée (tables et paragraphes entièrement modifiables)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Convertir et enregistrer le document PDF précédemment ouvert en tant que document DocX avec le mode de reconnaissance améliorée (tables et paragraphes entièrement modifiables)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```