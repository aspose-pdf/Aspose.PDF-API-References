---
title: "optimize_file_size"
second_title: "Aspose.PDF para Rust via C++"
description: "Otimiza o tamanho do documento PDF com qualidade de compressão de imagem."
type: docs
url: /pt/rust-cpp/organize/optimize_file_size/
---

_Otimiza o tamanho do documento PDF com qualidade de compressão de imagem._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Otimizar o tamanho do documento PDF com qualidade de compressão de imagem
    pdf.optimize_file_size(50)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```