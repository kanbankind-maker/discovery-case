---
description: Find 5 product hypotheses for a segment using subagent chain
---

# Find 5 Hypotheses

<!-- 
ЗАДАНИЕ: Заполни шаги ниже, описав что каждый агент должен сделать и какой результат сохранить.
Запусти командой /find-hypotheses в чате Cursor Agent.
-->

## Step 1 — Funnel Analysis
Agent: @agent_funnel_analyst  
Task: <!-- Что анализировать? Для какого сегмента? -->  
Output: <!-- Что сохранить в output/? -->

## Step 2 — Interview Synthesis
Agent: @agent_interview_synthesizer  
Input: <!-- Что берёт из предыдущего шага? -->  
Task: <!-- Что синтезировать? -->  
Output: <!-- Что сохранить в output/? -->

## Step 3 — Hypothesis Generation
Agent: @agent_hypothesis_generator  
Input: <!-- Что берёт из предыдущих шагов? -->  
Task: <!-- Сформулируй задачу агенту -->  
Output: output/hypotheses.md
