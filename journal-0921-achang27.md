# Day 0921 Journal — Defensive Programming

## What does defensive programming mean?

Defensive programming means writing code that anticipates potential user errors and unexpected inputs before they happen, keeping the program running safely instead of crashing.

## Which Python tool is most important for security?

Input validation is the most critical security tool because it acts as a proactive gatekeeper. While try/except only catches errors after they happen, validating inputs stops bad or malicious data at the boundary before it can ever reach and exploit core program logic.

## Is a completely crash-proof program possible?

No, a completely crash-proof program is not possible. Even if a developer writes perfect code that catches every conceivable input error, software still relies on unpredictable external factors like hardware failures, lost network connections, memory limits, and operating system crashes. Defensive programming isn't about achieving absolute perfection; it's about shifting a system from "unsafe" to "less unsafe" by anticipating common failures and handling unexpected errors gracefully.
