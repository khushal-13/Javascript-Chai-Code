# 📘 [Topic Name]

## 📖 Concept
Briefly explain the concept in your own words.  
Example: "`useState` is a React Hook that allows functional components to have state."

---

## 🛠 Syntax
```javascript
// Example syntax here
const [state, setState] = useState(initialValue);

💻 Example

// Working example with explanation
import React, { useState } from "react";

export default function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </div>
  );
}



⚠ Common Mistakes
Forgetting to initialize state properly.

Updating state without using the setter function.

✅ Best Practices
Use descriptive state variable names.
Use functional updates when new state depends on old state.

📚 Extra Notes
Related documentation: React useState Docs
Alternative approaches: useReducer for complex state logic.