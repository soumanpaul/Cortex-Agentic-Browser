
# Understand it before abstracting it.
- don't immediately install an HTML parser.
Build tokenizer
       ↓
Build parser
       ↓
Understand DOM
       ↓
Then evaluate existing libraries

# Same for the agent.
- Don't start with:
LangChain
LangGraph
CrewAI

# Start with:
Rust
 ↓
Agent loop
 ↓
Tool interface
 ↓
State
 ↓
Planner
 ↓
Memory

