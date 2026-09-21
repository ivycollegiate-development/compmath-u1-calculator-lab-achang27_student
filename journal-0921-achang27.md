# Day 0921 Journal — Defensive Programming

Input validation is the most important tool for security because it ensures that malicious or malformed data is rejected at the boundary before it can interact with internal application logic. While try/except handles errors after they occur, input validation proactively prevents invalid data from causing unexpected behaviors or exploitation in the first place.

A completely crash-proof program is not possible because developers cannot anticipate every infinite variation of input or unexpected system state. The class discussion reinforced that software engineering is not about making code perfect, but about writing defensive code to make programs "less unsafe" through sensible fallbacks.
