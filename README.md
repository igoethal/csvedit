# csvedit

A simple CSV editor that runs in a terminal.
Written in Python. Uses a Pandas dataframe to handle data imports and exports.

```
┌─────────────┬────────────┬──────────────┬────────────┬────────┐
│ Firstname   │ Lastname   │ Address      │ Postalcode │ City   │
├─────────────┼────────────┼──────────────┼────────────┼────────┤
│ Lorem       │ Ipsum      │ Dolor sit 17 │ 1005       │ Amet   │
│ Consectutur │ adipiscing │ Elit sed 8   │ 1008       │ Tempor │
└─────────────┴────────────┴──────────────┴────────────┴────────┘
Cell 1:1 (2) | Ctrl-(W/X): Insert (Above/Below) | Ctrl-D: Delete record | F4: Save | Ctrl-E: Exit (no save)
```

## Installation in linux

Edit the Shebang line at the start of the csvedit-file and ensure it points to your python3 interpreter
Default #!/usr/bin/python3

Ensure your python environment supports pandas and curses (use pip if needed to install it)

Make the file executable and run

## Installation in windows

Not tested yet, running "python3 csvedit <filename>" should work
