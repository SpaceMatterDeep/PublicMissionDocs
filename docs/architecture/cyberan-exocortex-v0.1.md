Input:
- user_state
- agent_model_of_user
- task_context

Exchange:
- user updates model of agent
- agent updates model of user

Output:
- aligned action
- delta in mutual model

Invariant:
- no coercion
- bidirectional interpretability

User intent:
"I want to design a satellite experiment for Casimir invariants"

Step 1 — User → Exocortex
- intent encoded into Cyberan representation

Step 2 — Exocortex → Agent
- structured prompt / symbolic state passed

Step 3 — Agent → World
- generates experiment design
- queries simulation / literature / tools

Step 4 — World → Exocortex
- results + constraints returned

Step 5 — Exocortex → User
- updated model of:
  - experiment
  - user intent
  - agent understanding

Invariant:
- user agency preserved
- mutual model updated
