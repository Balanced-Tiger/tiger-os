# Delta Check Comparison Protocol

---

## Purpose

Detect meaningful changes between states using minimal comparison logic.

---

## Core Principle

Only track what changed. Ignore everything else.

---

## Change Types

• Additions  
• Removals  
• Time shifts  

---

## Model

Previous State → Compare → Current State → Output Changes

---

## Rules

• Do not reprocess entire datasets  
• Only identify deltas  
• Maintain sequential comparison (state-to-state)  
• Ignore unchanged elements  

---

## Anti-Patterns (Disallowed)

• Full re-analysis of unchanged data  
• Over-complex comparison logic  
• Mixing interpretation with detection  
• Tracking irrelevant differences  

---

## Use Case

Applied when:

• comparing schedules  
• updating invoices  
• tracking workflow changes  
• monitoring system outputs  

---

## Result

• Faster processing  
• Reduced cognitive load  
• Clear change visibility  
• Efficient updates
