---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF para Rust via C++"
description: "Obtém se um documento PDF está em conformidade PDF/A."
type: docs
url: /pt/rust-cpp/organize/is_pdfa_compliant/
---

_Obtém se um documento PDF está em conformidade PDF/A._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Obter status de conformidade PDF/A do documento PDF
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```