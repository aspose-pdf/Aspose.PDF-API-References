---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove a conformidade PDF/A de um PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_pdfa_compliance/
---

_Remover a conformidade PDF/A de um documento PDF._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Remover a conformidade PDF/A de um documento PDF
    pdf.remove_pdfa_compliance()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```