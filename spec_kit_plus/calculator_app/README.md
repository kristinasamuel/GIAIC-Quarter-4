# Class Assignment 05: Simple Calculator using Gemini CLI

This project demonstrates a simple calculator application built with Python and managed using `uv`. The project was created and modified using the Gemini CLI.

## How to use the Calculator

1.  Navigate to the `calculator_app` directory:
    ```bash
    cd calculator_app
    ```
2.  Run the calculator:
    ```bash
    uv run main.py
    ```

## Gemini CLI Usage

The Gemini CLI is a powerful tool for interacting with the Gemini model. Here are some basic commands and concepts:

### Installation

To install the Gemini CLI

**Command:**  npm install -g @google/gemini-cli

### Checking Version

To check the installed version of the Gemini CLI:

**Command:** gemini -v

### Starting Gemini CLI

To start an interactive session with the Gemini CLI:

**Command:** gemini

# 🚀 Gemini CLI Quick Reference

A simple guide to using Gemini CLI commands effectively.

## 🔧 Basic Setup

```bash
gemini --m gemini-2.5-flash
```
👉 Change or select the Gemini model.

```bash
! 
```
👉 Use `!` to run shell commands directly inside Gemini CLI.

---
```bash
ls
```
👉 List all files and folders.

---

## ⚙️ Shell Mode & Tools

```bash
shell
```
👉 Open shell mode (type `escape` to disable it).

```bash
/tools
```
👉 View or manage available tools.

```bash
/stats
```
👉 Check model, token usage, request count, and cache info.

---

## 🧠 Model & Debugging

```bash
gemini --m gemini-2.5-flash --yolo
```
👉 Run in agent mode **without asking permission** for actions.

```bash
gemini --m gemini-2.5-flash --debug
```
👉 Enable **debug mode** to see how the backend processes your request.

---

## 💾 Project & File Management

```bash
cat <filename>
```
👉 View file contents.

```bash
/exit
```
👉 Exit the Gemini session.

