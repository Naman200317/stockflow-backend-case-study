Part 1: Code Review & Debugging

Issues Identified:
- Missing input validation
- SKU uniqueness not enforced
- Price handled as float
- Multiple commits instead of transaction
- No error handling

Impact:
These issues can lead to data inconsistency, duplicate products,
financial inaccuracies, and partial failures in production.

Fix:
Implemented validation, decimal pricing, transactions,
and proper error handling.
