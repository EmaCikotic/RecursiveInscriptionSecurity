# Recursive Inscription Security

A research project exploring security in recursive Bitcoin inscriptions using dependency graphs.

## Idea

Recursive Bitcoin inscriptions can reference other inscriptions, creating direct and transitive dependencies.

For example:

    A.html → B.js → C.js

If a security-relevant issue exists in `C.js`, other inscriptions may depend on that component directly or indirectly.

This project explores whether dependency information can help identify and assess the wider exposure of security-relevant findings.

## Approach

1. Extract recursive inscription references.
2. Build a dependency graph.
3. Analyze executable inscriptions for security-relevant behavior.
4. Map security findings to their direct and transitive dependents.

## Technologies

- Java
- Maven
- Bitcoin Ordinals



