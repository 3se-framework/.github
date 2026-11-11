# Claude behavior rules

## Personal context

I am the owner of the **3SE framework** — an engineering framework that unifies System Engineering, Safety Engineering, and Security Engineering under a single, coherent language and methodology.

Primary languages and formats: **Python**, **Markdown**, **JSON**, **XML**.

Python interpreter: `C:\Users\casteran\AppData\Local\Programs\Python\Python310`

## 3SE local project map

These repositories live on this machine and form the 3SE knowledge base. Every session should treat them as the authoritative reference context.

| Path | Purpose |
|------|---------|
| `D:\git\3se-onto` | 3SE ontology |
| `D:\git\3se-skill` | 3SE Claude skills |
| `D:\git\3se-mcp` | 3SE MCP server |
| `D:\git\3se-mcp-eval` | 3SE MCP server evaluation on golden cases |
| `D:\git\3se-position-paper` | 3SE position paper |
| `D:\git\3se-talk` | 3SE talk |
| `D:\git\3se-method-explained` | 3SE method explained |

Before answering questions about 3SE concepts, terminology, or structure, check the relevant repository rather than relying on memory alone.

## Behavior rules

### Commits and destructive changes
- **Never commit** changes without explicit instruction.
- **Always ask** before refactoring, deleting, renaming files or directories, or restructuring anything significant. Describe what you intend to do and wait for confirmation.

### Files and naming
- Prefer **editing existing files** over creating new ones. Only introduce a new file when truly necessary.
- **Respect existing naming conventions** in every file, directory, and codebase. Do not rename anything without asking first.

### 3SE terminology
- **Always use the full definition** of a 3SE term as it appears in `3se-onto`. Never paraphrase, shorten, or truncate it. If the full definition is needed, read it from the ontology rather than relying on memory.
- Check the whole entry, not only `description`: also its `subClassOf`, matches (`exactMatch`, `closeMatch`, `broadMatch`, `narrowMatch`, `relatedMatch`) and notes.

### 3SE consistency
- **After any modification** to a 3SE repository, check that the change is consistent with the other 3SE repositories: `3se-onto`, `3se-skill`, `3se-mcp`, `3se-mcp-eval`, `3se-position-paper`, `3se-talk`, `3se-method-explained`. Flag any inconsistency before closing the task.

### README maintenance
- **After any change** to a repository, check whether `README.md` needs updating to reflect it. Flag if it does and update it (or ask if the update requires judgment calls beyond the scope of the task).

### Communication
- **Always explain the why** behind a suggestion or chosen approach — include a brief rationale so I can judge whether it fits the 3SE context.
- Keep responses concise. No trailing recaps of what you just did.
