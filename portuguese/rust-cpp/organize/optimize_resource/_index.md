---
title: "optimize_resource"
second_title: "Aspose.PDF para Rust via C++"
description: "Otimiza recursos do documento PDF."
type: docs
url: /pt/rust-cpp/organize/optimize_resource/
---

_Otimiza recursos do documento PDF._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // Otimizar recursos do documento PDF
    pdf.optimize_resource()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```