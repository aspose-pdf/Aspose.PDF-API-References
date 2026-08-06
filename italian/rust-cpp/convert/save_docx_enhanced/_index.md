---
title: "save_docx_enhanced"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva il PDF-document precedentemente aperto come DOCX-document con Modalità di Riconoscimento Avanzata (tabelle e paragrafi completamente modificabili)."
type: docs
url: /it/rust-cpp/convert/save_docx_enhanced/
---

_Converte e salva il PDF-document precedentemente aperto come DOCX-document con Modalità di Riconoscimento Avanzata (tabelle e paragrafi completamente modificabili)._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva il PDF-document precedentemente aperto come DocX-document con Modalità di Riconoscimento Avanzata (tabelle e paragrafi completamente modificabili)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```