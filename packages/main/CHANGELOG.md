# @google/generative-ai

## 0.9.0

### Minor Changes

- ca62400: Allow text-only systemInstruction as well as Part and Content.
- 111e970: Export error classes and add more properties to fetch errors.

## 0.8.0

### Minor Changes

- a89d427: Add GoogleAIFileManager for file uploads.

## 0.7.1

### Patch Changes

- 6ef8cee: Fixed bugs where `RequestOptions`, `generationConfig`, and `safetySettings` were not passed from the model down to some methods.

## 0.7.0

### Minor Changes

- 79b7651: Set default API version to "v1beta" to match Go and Python.

## 0.6.0

### Minor Changes

- 2a1f97c: Add `systemInstruction` feature and forced function calling feature (using `toolConfig`).

### Patch Changes

- 0931d2c: Refactor makeRequest to make fetch mockable.

## 0.5.0

### Minor Changes

- 658a0da: Add `apiClient` configuration option to `RequestOptions`.

## 0.4.0

### Minor Changes

- 790a943: Deprecate functionCall() and add functionCalls().
- e636823: Loosen role field typing on Content.
- 7a45f01: Add option in RequestOptions to change baseUrl.

### Patch Changes

- 3f95168: Fix requestOptions not being passed through countTokens, embedContent, and batchEmbedContents

## 0.3.1

### Patch Changes

- ccd9951: validateChatHistory is now checking that 'parts' property is an array

## 0.3.0

### Minor Changes

- 932e1be: Add `apiVersion` property to `RequestOptions` to allow user to choose API endpoint version.
- 9887465: Added support for function calling

## 0.2.1

### Patch Changes

- 2b0c955: Handle different model prefixes (such as tunedModels/).

## 0.2.0

### Minor Changes

- c64fca1: add request timeout configuration

## 0.1.3

### Patch Changes

- 54839f2: Send API key in header instead of query param.
- 6a4c9c2: Fixed stream hanging

## 0.1.2

### Patch Changes

- 73c2ff9: Fixed UTF-8 handling and chunking for stream output
- fb52d34: Obscure API key in error messages
- 5b5fc7d: Catch unhandled rejections in `sendMessageStream`.

## 0.1.1

### Patch Changes

- Update README to released version and bump to publish new README to npm.
