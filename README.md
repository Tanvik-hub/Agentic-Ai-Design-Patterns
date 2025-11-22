# 🧩 Agentic AI Design Patterns

A structured reference of modern Agentic AI workflows, architectures, and orchestration patterns.

---

## 👤 Single-Agent System
A single model completes the entire task using tools and a system prompt.  
Best for simple workflows, prototypes, and low-complexity automation.
<img width="675" height="170" alt="image" src="https://github.com/user-attachments/assets/d8f162b9-3935-4dba-8993-d1b03f1e9d79" />


## 🤝 Multi-Agent System
Multiple specialized agents cooperate by splitting a larger goal.  
Useful for tasks requiring diverse skill sets, tools, or contexts.


---

# ⚙️ Deterministic Workflows

## ➡️ Sequential Pattern
Agents execute in a strict, linear order.  
Ideal for predictable, step-by-step pipelines.
<img width="968" height="175" alt="image" src="https://github.com/user-attachments/assets/ee6f6247-199d-4c02-b6a5-c9cfadb29687" />


## 🔀 Parallel Pattern
Multiple agents run simultaneously on the same input.  
Speeds up processing but requires result resolution.
<img width="755" height="429" alt="image" src="https://github.com/user-attachments/assets/84d2b164-bd5e-4516-9cb8-14858f26ff73" />


## 🔄 Loop Pattern
An agent repeats actions until a condition is met.  
Great for monitoring, retries, and state-based workflows.
<img width="1075" height="381" alt="image" src="https://github.com/user-attachments/assets/297d7c2d-c716-456b-9804-d0be1bd9f6db" />


---

# 🔁 Iterative & Quality Patterns

## 🧠 ReAct Pattern
The agent alternates between reasoning (“thought”) and tools (“action”).  
Enables multi-step navigation, planning, and adaptive behavior.
<img width="1139" height="366" alt="image" src="https://github.com/user-attachments/assets/71df0590-8830-4e53-ab9b-db79ae481ca8" />


## 🧐 Review & Critique Pattern
One agent generates outputs while another critiques them.  
Ensures quality control for code, legal text, and risk-sensitive work.

## 💎 Iterative Refinement Pattern
Content is improved across multiple feedback cycles.  
Works well for creative, complex, or polishing-heavy tasks.

---

# 🧭 Dynamic Orchestration Patterns

## 🧭 Coordinator Pattern
A central manager decides which specialist agent should handle the task.  
Flexible and adaptive for routing-based workflows.
<img width="575" height="466" alt="image" src="https://github.com/user-attachments/assets/b60ad8f3-cfc1-4057-b5b4-df4cde697c6a" />


## 🌳 Hierarchical Task Decomposition
A root agent breaks a large goal into subgoals handled by lower agents.  
Strong for big, ambiguous, multi-stage objectives.

## 🐝 Swarm Pattern
Agents collaborate as peers without a central controller.  
Useful for brainstorming and divergent thinking, though costlier.

---

# ✋ Safety Pattern

## Human-In-The-Loop (HITL)
Execution pauses until a human approves the next step.  
Critical for sensitive operations like deployments, refunds, or deletions.
<img width="1148" height="352" alt="image" src="https://github.com/user-attachments/assets/4f0bbc59-87a0-4e7b-bded-4ad1ffaa44b7" />

