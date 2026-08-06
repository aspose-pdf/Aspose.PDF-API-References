---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF para Rust via C++"
description: "Remova a conformidade PDF/UA de um documento PDF."
type: docs
url: /pt/rust-cpp/organize/remove_pdfua_compliance/
---

_Remova a conformidade PDF/UA de um documento PDF._

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Remover a conformidade PDF/UA de um documento PDF
    pdf.remove_pdfua_compliance()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```