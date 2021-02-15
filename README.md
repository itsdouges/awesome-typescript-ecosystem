# Awesome TypeScript Ecosystem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 😎 A list of awesome TypeScript transformers, plugins, handbooks, etc

> As always,
> use caution when trying out TypeScript transformers & plugins,
> especially those marked as 🔧 _experimental_ or 🔧🚧 _under construction_.

## Handbooks

- [typescript-book](https://github.com/basarat/typescript-book/) - 📚 The definitive guide to TypeScript and possibly the best TypeScript book 📖
- [ts-transformer-handbook](https://github.com/madou/ts-transformer-handbook) - 📘 A handbook on how to create transformers for Typescript with real code examples
- [TypeScript-Handbook](https://github.com/microsoft/TypeScript-Handbook) - The TypeScript Handbook is a comprehensive guide to the TypeScript language
- [TypeScript wiki](https://github.com/Microsoft/TypeScript/wiki) - The official wiki for TypeScript lang

## Transformers

Transformers are synonymous with Babel Plugins.
They enable transforming code from one to to another,
generally used for improving the developer experience,
doing performance optimizations,
and more.

### General transformers

- [typescript-is](https://github.com/woutervh-/typescript-is#readme) - generate run-time type-checks
- [ts-nameof](https://github.com/dsherret/ts-nameof) - nameof in TypeScript
- [ts-transform-json](https://github.com/longlho/ts-transform-json) - Inline specific values from a JSON file or the whole JSON blob
- [ts-transform-json-schema](https://github.com/marionebl/ts-transform-json-schema) - Generate inline JSON schema from TypeScript types
- [ts-transform-css-modules](https://github.com/longlho/ts-transform-css-modules) - Extract css class names from required css module files for TypeScript
- [ts-transform-img](https://github.com/longlho/ts-transform-img) - Allow `import * as img from 'foo.png'` in TS 
- [ts-transform-import-path-rewrite](https://github.com/dropbox/ts-transform-import-path-rewrite) - TS AST transformer to rewrite import path
- [ts-transform-graphql-tag](https://github.com/firede/ts-transform-graphql-tag) - Compiles GraphQL tagged template strings using graphql-tag in TypeScript files
- [ts-transform-define](https://github.com/compiled/ts-transform-define) - Allows you to create global constants which can be configured at compile time.
- [@ts-tools/robotrix](https://github.com/AviVahl/ts-tools/tree/master/packages/robotrix) - Useful TypeScript transpilation transformers.
- [ts-trim-declarations](https://github.com/cprecioso/ts-trim-declarations) - Remove declarations marked with `/** @internal */` from your exported files.

### Module resolution

- [ts-transformer-imports](https://www.npmjs.com/package/ts-transformer-imports) - A TypeScript transformer which enables compilation of absolute imports (using baseUrl or paths) so they can be required as modules from Javascript or TypeScript, without additional configuration or path mapping
- [ts-import-plugin](https://github.com/Brooooooklyn/ts-import-plugin) - Modular import plugin for TypeScript

### React

- [react-hot-ts](https://github.com/elsassph/react-hot-ts) - A lightweight, TypeScript-native, Babel-free, plugin-free, implementation of react-hot-loader
- [ts-transform-hoist-objects-in-props](https://github.com/avensia-oss/ts-transform-hoist-objects-in-props) - A TypeScript custom transformer that hoists object literals and functions that are passed to JSX props.
- [ts-transform-react-jsx-source](https://github.com/dropbox/ts-transform-react-jsx-source) - TypeScript AST Transformer that adds source file and line number to JSX elements 
- [ts-transform-react-constant-elements](https://github.com/dropbox/ts-transform-react-constant-elements) - A TypeScript AST Transformer that can speed up reconciliation and reduce garbage collection pressure by hoisting React elements to the highest possible scope
- [typescript-plugin-styled-components](https://github.com/Igorbek/typescript-plugin-styled-components) - TypeScript transformer for improving the debugging experience of styled-components 
- [emotion-ts-plugin](https://github.com/LeetCode-OpenSource/emotion-ts-plugin) - TypeScript transformer for improving the debugging experience and abilities of emotion
- [ts-transform-import-to-lazy-async-import](https://github.com/avensia-oss/ts-transform-import-to-lazy-async-import) - A TypeScript custom transformer that turns your synchronously imported components into lazy loaded through React.lazy() (or a factory of your choosing) 🔧
- [ts-transform-instrument-react-components](https://github.com/avensia-oss/ts-transform-instrument-react-components) - A TypeScript custom transformer that instruments React components to report which components exists in your bundle and which gets rendered 🔧

### i18n

- [@formatjs/ts-transformer](https://www.npmjs.com/package/@formatjs/ts-transformer) - Extracts string messages for translation from modules that use React Intl (similar to babel-plugin-react-intl)

### Types

- [ts-transformer-keys](https://www.npmjs.com/package/ts-transformer-keys) - A TypeScript custom transformer which enables to obtain keys of given type

### Testing

- [ts-auto-mock](https://www.npmjs.com/package/ts-auto-mock) - A TypeScript transformer that will allow you to create mock for any types (Interfaces, Classes, ...) without need to create manual fakes/mocks.
- [jest-ts-auto-mock](https://github.com/Typescript-TDD/jest-ts-auto-mock) - Jest test utility with automatic mock creation for interfaces and classes
- [ts-transformer-testing-library](https://github.com/marionebl/ts-transformer-testing-library) - Make testing custom TypeScript transformers a breeze

### Optimization

- [ts-transform-inferno](https://github.com/deamme/ts-transform-inferno) - TypeScript transformer for InfernoJS 
- [ts-transform-async-import](https://github.com/avensia-oss/ts-transform-async-import) - A TypeScript custom transformer that turns synchronous imports of async functions into asynchronous imports 🔧
- [ts-transform-export-const-folding](https://github.com/avensia-oss/ts-transform-export-const-folding) - This is a TypeScript custom transform that removes imported constants by inlining them.

## Language service plugins

Language service plugins enable rich developer experience warnings, errors, and even intellisense in your IDE.
Read [how to write your own langauge service plugin here](https://github.com/Microsoft/TypeScript/wiki/Writing-a-Language-Service-Plugin).

- [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - TypeScript Language Service Plugin for GraphQL developers 
- [typescript-styled-plugin](https://github.com/Microsoft/typescript-styled-plugin) - TypeScript server plugin that adds intellisense to styled component css strings
- [tslint-language-service](https://github.com/angelozerr/tslint-language-service/) - TypeScript 2.2.1 plugin for tslint 
- [ts-sql-plugin](https://github.com/xialvjun/ts-sql-plugin) -  TypeScript Language Service Plugin for SQL with a tagged template strings SQL builder
- [ts-mysql-plugin](https://github.com/segmentio/ts-mysql-plugin) - A TypeScript Language Service Plugin that gives superpowers to SQL tagged template literals. 

## Tools

- [ttypescript](https://github.com/cevek/ttypescript) - Over TypeScript tool to use custom transformers in the tsconfig.json
- [ts-morph](https://github.com/dsherret/ts-morph) -  TypeScript Compiler API wrapper for static analysis and programmatic code changes
- [ts-creator](https://github.com/HearTao/ts-creator) - A code generator to generate TypeScript code generator from TypeScript code
- [typescript-json-schema](https://github.com/YousefED/typescript-json-schema) - Generate json-schema from your TypeScript sources
- [ts-json-schema-generator](https://github.com/vega/ts-json-schema-generator) - Generate JSON schema from your TypeScript sources
- [ts-query](https://github.com/phenomnomnominal/tsquery) - TypeScript AST query library
