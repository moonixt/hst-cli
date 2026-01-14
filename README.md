# hst-cli

[![License](https://img.shields.io/github/license/moonixt/hst-cli)](https://github.com/moonixt/hst-cli/blob/main/LICENSE)
[![npm version](https://img.shields.io/npm/v/@deimos24/hst-cli)](https://www.npmjs.com/package/@deimos24/hst-cli)

A CLI built to take care of your system, without any restrictive "advice" or "warning" from critical directories.

> **Note**: This is a fork of [Gemini CLI](https://github.com/google-gemini/gemini-cli) by Google DeepMind.

## 🚀 Features

- **🚫 No restrictions**: Full access to system directories without warnings
- **🧠 Powered by Gemini**: Access to Gemini's powerful AI capabilities
- **🔧 Built-in tools**: File operations, shell commands, web fetching
- **🔌 Extensible**: MCP (Model Context Protocol) support for custom integrations
- **💻 Terminal-first**: Designed for developers who live in the command line

## 📦 Installation

### Pre-requisites

- Node.js version 20 or higher
- macOS, Linux, or Windows

### Quick Install

```bash
npm install -g @deimos24/hst-cli
```

## 🚀 Usage

```bash
hst
```

## 🔐 Authentication

### Option 1: Login with Google (OAuth)

Start hst-cli and choose _Login with Google_:

```bash
hst
```

### Option 2: Gemini API Key

```bash
export GEMINI_API_KEY="YOUR_API_KEY"
hst
```

Get your API key from: https://aistudio.google.com/apikey

### Option 3: Vertex AI

```bash
export GOOGLE_API_KEY="YOUR_API_KEY"
export GOOGLE_GENAI_USE_VERTEXAI=true
hst
```

## 📄 License

Apache License 2.0 - See [LICENSE](LICENSE) for details.

This is a fork of [Gemini CLI](https://github.com/google-gemini/gemini-cli) by Google DeepMind.
