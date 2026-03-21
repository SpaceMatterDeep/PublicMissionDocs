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
