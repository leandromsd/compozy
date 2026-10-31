## 0.4.8 - 2026-10-31

### Bug Fixes

- Keep the accent ink on the menubar Updating pill (#1089)
- Restore the usage tray before the bell and hold its slot while loading (#1090)
- Ellipsize long session titles in session message card headers (#1099)
- Remove the Skip to content link that appeared on window reactivation (#1096)
- Hide empty projects in project grouping behind a Show empty projects option (#1091)
- Authorize explicit cross-workspace session replies (#1103)
- Let operators resume and take over spawned sessions after the parent stops (#1098)
- Decode each Later reason character reference once and only when complete

### Features

- Rich-text reason and date picker in the Move to Later dialog (#1093)
- Group session processes into trees (#1106)

### Refactoring

- Replace the in-repo prototype gallery with @compozy/proto (#1092)

### Testing

- Cover captured-only AfterStop cleanup and lead-only Stop all for process trees
