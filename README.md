# 15_LangGraph_101

run command :-
uv run python -m 15_langgraph_101.app.main

User enters an order
        |
     Validate
        |
    Check stocks
        |
       Router 
  |                 |
  In stock       Out of stock
  |                 |
  Confirmed       Rejected
          |
          END


State:
1. Information that is provided by user: product (str), qty(int)
2. Information updated by validation and stock: is_valid(bool), router(bool)
3. Status of the order: str



prep:-
1. state.py
2. nodes.py
3. edges.py
4. graph.py
