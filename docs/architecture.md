# Sanitized Architecture

Configuration / validation inputs
        |
        v
Deterministic simulation & geometry core
        |
        +--------------------+
        |                    |
        v                    v
Native Unreal integration    GPU rendering path
        |                    |
        +---------+----------+
                  |
                  v
         Runtime presentation
                  |
                  v
    Tests + runtime evidence checks

Proprietary class names, source layout, exact parameters, private topology, task IDs and client assets are omitted.
