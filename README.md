# 🥞 Piggybankone UIkit

[![Version](https://img.shields.io/npm/v/@piggybankone/uikit)](https://www.npmjs.com/package/@piggybankone/uikit) [![Size](https://img.shields.io/bundlephobia/min/@piggybankone/uikit)](https://www.npmjs.com/package/@piggybankone/uikit)

Piggybankone UIkit is a set of React components and hooks used to build pages on Piggybankone's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @piggybankone/uikit`

## Setup

### Theme

Before using Piggybankone UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@piggybankone/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@piggybankone/uikit'
...
<ResetCSS />
```
