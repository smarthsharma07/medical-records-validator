# medical-records-validator
# Medical Records Validator (FreeCodeCamp Project)

This is a small Python project that validates a collection of medical records.  
It was built while following the **Build a Medical Data Validator** project on FreeCodeCamp.

The script checks both:

1. **The overall data structure** (list / dictionaries / keys), and  
2. **The contents of each field** using type checks and regular expressions.

---

## Features

- Ensures the top-level data is a **list or tuple**.
- Ensures each element is a **dictionary**.
- Verifies that each dictionary has **exactly** these keys:

  ```python
  ['patient_id', 'age', 'gender', 'diagnosis', 'medications', 'last_visit_id']
