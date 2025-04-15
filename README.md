# QA-Tests

## Overview
Tested:
- **React App**: TodoMVC('https://todomvc.com/examples/react/dist/') for UI functionality.
- **API**: JSONPlaceholder('https://jsonplaceholder.typicode.com/') for API requests.

## Test Cases

### TC_001: Verify Adding a New Todo Item
- **Preconditions**: User is on TodoMVC page, Chrome browser.
- **Steps**:
  1. In the input field, type: "Buy milk".
  2. Press Enter.
- **Expected Result**: Todo "Buy milk" appears in the list, input clears, counter shows.
- **Actual result**: Todo added, counter updated.
- **Status**: Pass
- **Screenshot**: [screenshots/tc_001.png](screenshots/tc_001.png)

