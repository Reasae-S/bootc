# BootScript

BootScript is a high-level, transpiled programming language made to be compatible with old web browsers.  
BootScript is designed as a modded subset of ECMA-262 first edition (based on JavaScript 1.1) with two key additions:

1. **Macros for Code Generation**  
  BootScript allows developers to define macros that alter your code at transpile time.

2. **Automatic Polyfills**  
  BootScript automatically inserts polyfills for modern browser APIs when needed.

All BootScript programs are compiled to a version of JavaScript that can run in every standardized browser starting from Netscape 2.0 without runtime errors.

## Versioning

BootScript is currently in beta, meaning any code or language features are subject to change.  
The versioning system of BootScript is split into three categories:

- **Canto**  
  This is a major patch. It means the commit makes breaking changes to the language which aren't backward compatible.

- **Intervallo**  
  This is a minor patch. It means the commit makes additive changes to the language that don't break previous code.

- **Chapter**  
  This is a subpatch. It means the commit makes changes to the language that don't alter its current formal state.  
  Due to this, all commits before the first Canto are chapters, as they don't alter the formal state of the language.

- **Citation**
  This is a change in the language's design documents that entails what a correct implementation of the language should include.