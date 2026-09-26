# Example (Prefetch)

## Purpose

Windows artifact used to track application execution.


## Location

```text
C:\Windows\Prefetch
```

## Investigative Value

- Application execution evidence
- Last execution timestamp
- Execution count

## Contents

- Executable name
- Run count
- Last run time
- Referenced files and directories

## Tools

- PECmd
- WinPrefetchView
- Arsenal Image Mounter

## Correlation Opportunities

- Amcache
- Shimcache
- Event Logs
- SRUM
- Jump Lists
- LNK Files

## Limitations

- Can be disabled
- Limited number of entries
- May be deleted by an attacker

## Common Investigation Questions

- Was the application executed?
- When was it last executed?
- How many times was it executed?

## My Notes

-