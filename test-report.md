# Manual Testing Report – ToDoMVC React App

**Test URL**: https://todomvc.com/examples/react  
**Test Type**: Manual Functional & UI Testing  
**Tester**: Chaimae Domschke
**Date**: 20.05.2025

---

## Test Scope
- Add/Edit/Delete Tasks
- Task Completion and Filters
- UI/UX Behavior

---

## Test Cases

| Test Case ID | Scenario             | Steps | Expected Result | Status |
|--------------|----------------------|-------|------------------|--------|
| TC001        | Add new task         | Type task + Enter | Task appears in list | ✅ Pass |
| TC002        | Mark task complete   | Click checkbox | Task shown as completed | ✅ Pass |
| TC003        | Filter completed     | Complete task → Click “Completed” | Only completed tasks visible | ✅ Pass |
| TC004        | Edit task            | Double click → Change → Enter | Task text updates | ✅ Pass |
| TC005        | Delete task          | Click "X" next to task | Task removed | ✅ Pass |

---

## Bug Reports

### Bug #001 – Blank Task Not Handled

- **Steps**: Press Enter without typing anything
- **Expected**: App should warn or block empty task
- **Actual**: Nothing happens, no feedback
- **Severity**: Low

---

## Summary

- **Total Test Cases**: 5  
- **Passed**: 5  
- **Bugs Found**: 1 (UX-level)  
- **Suggestions**:
  - Show a warning for blank task input
  - Add task persistence (saving tasks on refresh)

---

## End of Report
