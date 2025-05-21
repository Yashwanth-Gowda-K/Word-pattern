# Word-pattern

## Problem Statement
Given a `pattern` and a string `s`, determine if `s` follows the same pattern.

**Examples:**
- ✅ `pattern = "abba"`, `s = "dog cat cat dog"` → `True`
- ❌ `pattern = "abba"`, `s = "dog cat cat fish"` → `False`

## Solution Approach
- **Two-Way Mapping:** Uses dual dictionaries to enforce bijective relationships
- **Early Termination:** Returns immediately on mismatches
- **O(n) Complexity:** Efficient linear time and space

## Key Features
- Handles all edge cases (empty inputs, length mismatches)
- Clear, commented code
- Includes test cases
