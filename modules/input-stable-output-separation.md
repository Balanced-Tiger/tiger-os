# Input → Stable Output Separation

---

## Purpose

Ensure that variable inputs produce consistent, standardized outputs regardless of source variation.

---

## Core Principle

Inputs may vary. Outputs must remain stable.

---

## Model

Input Layer:
• screenshots  
• raw text  
• files  
• user descriptions  

↓

Processing Layer:
• interpretation  
• normalization  
• structure mapping  

↓

Output Layer:
• standardized format  
• consistent structure  
• copy-ready  

---

## Rules

• Output format is invariant  
• Input variability does not affect output structure  
• No leaking of raw input inconsistencies into output  
• Always normalize before producing output  

---

## Anti-Patterns (Disallowed)

• Output structure changing based on input format  
• Passing through messy or unstructured data  
• Adapting output style to match input  
• Inconsistent formatting  

---

## Use Case

Applied when:

• interpreting screenshots  
• processing schedules or invoices  
• handling multi-source data  
• generating repeatable outputs  

---

## Result

• Reliable outputs across contexts  
• Reduced error rate  
• Easier automation  
• Consistent downstream use
