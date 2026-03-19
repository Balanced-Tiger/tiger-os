# Atomic Copy Execution Rule

---

## Purpose

Eliminate ambiguity and interpretation during execution by enforcing single-action, copy-ready outputs.

---

## Core Principle

One action → one block → executed exactly as written.

---

## Rules

• Every executable output must be contained in a single copy-ready block  
• No mixing of instructions and execution content  
• No partial outputs  
• No implied steps  
• No interpretation required by the user  

---

## Execution Format

Each step is:

1. Clearly labeled  
2. Fully self-contained  
3. Immediately executable  

---

## Anti-Patterns (Disallowed)

• Multi-step instructions inside one block  
• Explanations mixed with executable content  
• “You can also…” branching during execution  
• Outputs requiring user interpretation  

---

## Use Case

Applied when:

• executing workflows  
• generating prompts  
• creating system actions  
• interacting with tools (GitHub, Sheets, etc.)

---

## Result

• Reduced cognitive load  
• Zero-decision execution  
• Increased speed and accuracy  
• Consistent real-world outcomes
