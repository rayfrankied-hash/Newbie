# Newbie

A beginner-friendly repository for learning coding best practices.

## Descriptive Variable and Function Naming

Using clear, descriptive names makes code easier to read, understand, and maintain.

### Variables

| ❌ Poor name | ✅ Descriptive name | Why it's better |
|---|---|---|
| `x` | `userAge` | Clearly describes what the value represents |
| `n` | `itemCount` | Communicates the unit and purpose |
| `d` | `elapsedDays` | Removes ambiguity about what is being counted |
| `tmp` | `temporaryFilePath` | States the type and purpose |
| `flag` | `isUserLoggedIn` | Boolean names should read as a yes/no question |
| `data` | `customerOrderList` | Describes the domain and structure |

### Functions / Methods

| ❌ Poor name | ✅ Descriptive name | Why it's better |
|---|---|---|
| `doStuff()` | `calculateMonthlyInterest()` | Describes exactly what the function does |
| `process()` | `validateUserInput()` | Explains the action and the subject |
| `handle()` | `sendPasswordResetEmail()` | Unambiguous about the operation |
| `get()` | `fetchActiveCustomers()` | Verb + subject pattern communicates intent |
| `check()` | `isEmailAddressValid()` | Returns a boolean; name reads as a question |
| `update()` | `updateShippingAddress()` | Specific about what is being updated |

### General Rules

1. **Use full words** – avoid single letters or cryptic abbreviations (`idx` → `index`, `usr` → `user`).
2. **Use a verb for functions** – function names should describe an action (`calculate`, `fetch`, `validate`, `send`).
3. **Use nouns for variables** – variable names should describe a thing or concept.
4. **Booleans read as questions** – prefix with `is`, `has`, `can`, or `should` (e.g., `isAuthenticated`, `hasPermission`).
5. **Be consistent** – pick a naming convention (`camelCase`, `snake_case`, `PascalCase`) and stick with it throughout the project.
6. **Avoid generic names** – `data`, `info`, `value`, `result`, and `temp` are too vague; always qualify them.
