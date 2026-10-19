# Built-in features for cartograph-os

Purpose: geographic information systems, mapping, and field map research

1. **prepare a creative project** — run cartograph-os-workspace. It creates ~/Documents/cartograph-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run cartograph-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/cartograph-os-session-plans/.
3. **check project and export readiness** — run cartograph-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/cartograph-os-workspace features/cartograph-os-plan features/cartograph-os-check "$HOME/.local/bin/"
