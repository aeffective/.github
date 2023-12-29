# Aeffective
## Code and Repositories Guidelines
The repository suffix indicates its function.
- `*_main` is a - generally big - **main** repository containing all the source code, documentation, experiments and unit tests for a specific area (e.g. urban traffic, motion recognition, etc..)
- *no suffix* a **production** repository - generally small - entirely focused to production code, often matching a specific deliverable. It may include libreries and packages created from a `*_main` repository. It **must not** include any code that is not supposed to be seen by a client.
- `*_dev` is a **development** repository, generally containing tests and - less often - experiments related to a production repository with the same name, minus the `*_dev` suffix
