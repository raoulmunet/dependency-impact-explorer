# Dependency Impact Explorer

Explore upstream and downstream impact from a simple dependency list.

## Input format

```text
REPORT_A -> VIEW_X
VIEW_X -> TABLE_CUSTOMER
PROC_P -> TABLE_CUSTOMER
```

## What it does

- Builds a directed dependency graph.
- Shows direct and transitive upstream/downstream impact.
- Highlights the selected object.
- Provides an impact summary.

## Privacy

Everything runs locally in the browser.

## License

MIT
