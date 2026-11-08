# Validation

The original disconnected sample and local review controls were smoke-checked. Notion reads, status writes and agent-to-app handoff remain unverified. Connected changes can write to Notion; inspect the destination before use.

Extraction checks verify that the app HTML matches the source, the bundled instructions and examples are present, JavaScript parses, and repository-relative README links resolve. These checks do not establish live connector compatibility.
