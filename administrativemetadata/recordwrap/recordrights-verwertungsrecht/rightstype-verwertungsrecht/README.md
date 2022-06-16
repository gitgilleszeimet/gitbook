---
description: Rights Type
---

# rightsType \[License]

### Description

#### LIDO

The specific type of right being recorded.

For example: copyright, publication right, data protection right, trademark. Preferably taken from a published controlled value list.

#### MNHA

This element contains the following elements:

* `conceptID`
* `term`

### Attributes

_This element does not have attributes._

### Examples

```markup
<lido:rightsType>
    <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
         https://creativecommons.org/publicdomain/zero/1.0/
    </lido:conceptID>
    <lido:term>CC0</lido:term>
    <lido:term xml:lang="de">CC0</lido:term>
    <lido:term xml:lang="en">CC0</lido:term>
</lido:rightsType>
```

