## Summary (Summarize the bug encountered concisely)

On the **Create new project** page, the option that should read **"Create blank project"** is incorrectly displayed as **"Create black project"** due to a typo introduced in recent code changes.

---

## Steps to reproduce

1. Log in to the application.
2. Navigate to the **Create new project** page.
3. Look at the text under the first project creation option.
4. Observe the incorrect label.

---

## What is the current bug behavior?

The UI displays **"Create black project"** instead of **"Create blank project"**.

---

## What is the expected correct behavior?

The UI should display the correct text: **"Create blank project"**.

---

## Relevant logs and/or screenshots

 ![Screenshot](../Image/Bug_Project_create_blank.png)

---

## Possible fixes

Correct the label text in the frontend component responsible for rendering project creation options. Replace `"Create black project"` with `"Create blank project"`.

---

## Whom do you report / Assign To / Tags

**Assigned to:** Frontend Team  
**Tags:** UI, Typo, Low-impact bug

---

## Priority

**Low** — visual/UI issue, does not affect functionality but impacts clarity and user experience.