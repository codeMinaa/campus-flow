# AI Learning Log — Engineer A

## Interaction #1 — Python Unit Testing

**Problem:** I needed to verify that my ticket creation and priority calculation worked correctly.

**My initial understanding:** I knew that tests could check whether my code produced the expected results, but I was not yet confident about writing automated tests.

**Prompt to AI:** Help me run my Python unittest tests and understand the results.

**Useful AI guidance:** I learned how to run tests using `python3 -m unittest discover -s tests -v`.

**My independent experiment/test:** I ran the command in my terminal.

**Verification result:** All 8 tests passed.

**Decision:** I accepted the guidance because the terminal output confirmed that the tests passed.

**Related files:** `tests/test_tickets.py`, `campusflow/tickets.py`

**What I can now explain without AI:** Python's unittest framework checks whether my code behaves as expected. The terminal reports which tests pass and which fail.