---
'@coinbase/onchainkit': patch
---

- **feat**: added `wrapper` prop to `<FrameMetadata />` component, that defaults to `React.Fragment` when not passed (original behavior). By @syntag #90 #91
- **feat**: exported `FrameMetadataResponse` type which can be useful when using `getFrameMetadata` in a TS project. By @syntag #90