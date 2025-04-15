# QA-Tests

## Overview
Tested:
- **React App**: TodoMVC(`https://todomvc.com/examples/react/dist/`) for UI functionality.
- **API**: JSONPlaceholder(`https://jsonplaceholder.typicode.com/`) for API requests.

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

### TC_002: Verify GET Request for Todos List
- **Preconditions**: Postman is open, URL: `https://jsonplaceholder.typicode.com/todos`.
- **Steps**:
1. Create a new GET request.
2. Enter URL.
3. Click "Send".
- **Expected Result**: Status 200 OK, JSON array of todos, response time <1000 ms.
- **Actual Result**: Received JSON, status 200, time 185 ms.
- **Status**: Pass
- **Screenshot**: [screenshots/tc_002.png](screenshots/tc_002.png)
- **Postman Collection**: [collection/tc_002_postman.json](collection/tc_002_postman.json)

## Tools Used
- Postman, Chrome DevTools
- Git, Markdown

## Contact
- Email: dbevziuk.tech@gmail.com
- GitHub: https://github.com/dburdin


