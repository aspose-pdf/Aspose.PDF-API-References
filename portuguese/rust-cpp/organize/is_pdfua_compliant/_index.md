---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF para Rust via C++"
description: "Obtém se um documento PDF está em conformidade com PDF/UA."
type: docs
url: /pt/rust-cpp/organize/is_pdfua_compliant/
---

_Obtém se um documento PDF está em conformidade com PDF/UA._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // Obtenha o status de conformidade PDF/UA do documento PDF
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```