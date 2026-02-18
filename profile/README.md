# F-O-T

Production-ready TypeScript libraries for the Brazilian ecosystem — digital signatures, financial calculations, document processing, and more. Zero external dependencies. Built with [Bun](https://bun.sh/).

## Libraries

### Crypto & Signatures

| Package | Description |
|---------|-------------|
| [`@f-o-t/asn1`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/asn1) | ASN.1 DER encoding, decoding, and builder helpers |
| [`@f-o-t/crypto`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/crypto) | PKCS#12 parsing, CMS/PKCS#7 SignedData, hashing, and PEM utilities |
| [`@f-o-t/digital-certificate`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/digital-certificate) | Brazilian A1 digital certificate handling (.pfx/.p12), XML-DSig, and mTLS |
| [`@f-o-t/e-signature`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/e-signature) | PAdES PDF signing with ICP-Brasil compliance and RFC 3161 timestamps |

### Documents & Content

| Package | Description |
|---------|-------------|
| [`@f-o-t/pdf`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/pdf) | PDF generation, parsing, and editing |
| [`@f-o-t/xml`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/xml) | XML parsing, manipulation, canonicalization, and XPath |
| [`@f-o-t/csv`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/csv) | CSV parsing and generation |
| [`@f-o-t/markdown`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/markdown) | Markdown parsing and processing |
| [`@f-o-t/ofx`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/ofx) | OFX (Open Financial Exchange) parser and generator |
| [`@f-o-t/qrcode`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/qrcode) | QR code generation to PNG buffer |

### Business Logic

| Package | Description |
|---------|-------------|
| [`@f-o-t/condition-evaluator`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/condition-evaluator) | Typesafe condition evaluator for building rule engines |
| [`@f-o-t/rules-engine`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/rules-engine) | Business rules engine with condition evaluation |
| [`@f-o-t/money`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/money) | Type-safe money handling with BigInt precision and ISO 4217 currency support |
| [`@f-o-t/bigint`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/bigint) | BigInt utilities for precision arithmetic |
| [`@f-o-t/tax-calculator`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/tax-calculator) | Brazilian tax calculation |

### Utilities

| Package | Description |
|---------|-------------|
| [`@f-o-t/brasil-api`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/brasil-api) | Brazilian government API integrations |
| [`@f-o-t/content-analysis`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/content-analysis) | Content analysis and processing utilities |
| [`@f-o-t/datetime`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/datetime) | Date and time utilities |
| [`@f-o-t/spelling`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/spelling) | Spelling correction and validation |
| [`@f-o-t/uom`](https://github.com/F-O-T/fot-libraries/tree/master/libraries/uom) | Unit of measure conversions |

---

## Sponsors

This work is made possible by the generous support of our sponsors.

<table>
  <tr>
    <td align="center" width="300">
      <a href="https://www.somahub.net.br/" target="_blank">
        <strong>Somahub</strong>
      </a>
    </td>
    <td align="center" width="300">
      <a href="https://licitei.com.br" target="_blank">
        <strong>Licitei</strong>
      </a>
    </td>
  </tr>
</table>

---

Licensed under [MIT](https://github.com/F-O-T/fot-libraries/blob/master/LICENSE.md)
