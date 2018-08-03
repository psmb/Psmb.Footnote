This package provides a footnote plugin for CKeditor5 integraion in Neos CMS.

## Installation

1. Switch to using CKeditor 5
2. `composer require '@psmb/footnote'`
3. Enable footnote button on node properties that should support it, e.g.:

```
'Neos.NodeTypes:TextMixin':
  properties:
    text:
      ui:
        inline:
          editorOptions:
            formatting:
              footnote: true
```
