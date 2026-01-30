# ai-css-to-tailwind

[![npm version](https://img.shields.io/npm/v/ai-css-to-tailwind.svg)](https://www.npmjs.com/package/ai-css-to-tailwind)
[![npm downloads](https://img.shields.io/npm/dm/ai-css-to-tailwind.svg)](https://www.npmjs.com/package/ai-css-to-tailwind)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-css-to-tailwind)](https://github.com/lxgic-studios/ai-css-to-tailwind/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Convert any CSS file to Tailwind utility classes. Get a clean mapping of your existing styles to Tailwind equivalents.

## Install

```bash
npm install -g ai-css-to-tailwind
```

## Usage

```bash
npx ai-css-to-tailwind ./styles.css
# Prints Tailwind class mappings

npx ai-css-to-tailwind ./styles.css -o tailwind-mapping.md
# Saves mapping to a file
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-o, --output <path>` - Save output to a file

## License

MIT
