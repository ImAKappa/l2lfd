# Data Engineering

[Orchestration](https://dataguide.dev/deep-dives/orchestration)

## Terms

Idempotency - running the same task on the same data produces the same result

Backfilling - populating previous 

Directed Acyclic Graphs - a graph with no cycles and directed edges. A mathematical structure used to represent workflows

Assets

Dynamic Task Mapping - automatically scaling/parallelizing tasks for multiple inputs

Deferrable (Async) Operators - a non-blocking task which defines a trigger that can wake up the main task

Software-Defined Assets

XComs (Cross-Communication) between tasks

Failure handling:

- Retries

https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/index.html

Pipeline design patterns

- Fan-out
- Task groups
