# finalpool

This directory collects all **implemented** tasks from the BenchTasksCollv3 project.

A task is considered implemented when it follows the structure shown in
`tasks/examples/example-task`, i.e. it contains:

- `docs/` with `agent_system_prompt.md`, `task.md`, `user_system_prompt.md`
- `evaluation/main.py`
- `groundtruth_workspace/`
- `initial_workspace/`
- `preprocess/main.py`
- `readme.txt`
- `task_config.json` with a non-empty `needed_mcp_servers` field and a non-empty
  `needed_local_tools` field that includes `claim_done`

Each implemented task is placed here as its own subfolder (e.g. `tasks/finalpool/<task-name>/`).

## Current status

As of the latest review of all developer branches (fan-dev, gyy, haoze, jl_dev,
junteng_dev, junxian_dev, lueyang-dev, lv, ruige, wenshuo-dev, xiaochen_dev,
yuxuan-dev, yuzhen-dev, zhaochen), none of the 116 new tasks satisfy the
requirements (in particular, no task provides `task_config.json` with the
required fields, nor a `readme.txt` at the task root). All tasks are therefore
tracked as "implementing" in the Notion Task Tracker, and **the finalpool is
currently empty**. Implemented tasks will be added here as they qualify.
