---
title: "export_xml"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이전에 열려 있던 PDF-document와 AcroForm을 사용하여 파일 이름이 있는 XML-document으로 내보냅니다."
type: docs
url: /ko/rust-cpp/convert/export_xml/
---

_이전에 열려 있던 PDF-document와 AcroForm을 사용하여 파일 이름이 있는 XML-document으로 내보냅니다._

```rust
pub fn export_xml(&self, filename: &str) -> Result<(), PdfError>
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
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 이전에 열려 있던 PDF-document와 AcroForm을 사용하여 XML-document로 내보냅니다
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```