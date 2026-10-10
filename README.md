# Companion Resources
## Microsoft Copilot Studio: A Practical Guide to Building Enterprise-Ready AI Agents

This is the companion download for the book. It contains every sample document, data file, and asset used in the hands-on examples, organized into per-chapter folders.

**Referenced in the book as:** the **companion folder**.

---

### Download everything

- **All files at once:** select the green **Code** button above → **Download ZIP**, or download the zip from the latest **Release** (right-hand side of this page).
- **Single files:** open a chapter folder, open the file, and select the download button (↓).

---

### How to use

Each chapter that needs downloadable files points you to its folder here. Open the matching `Chapter-NN-...` folder and use the files as the chapter instructs.

All sample content is **illustrative** — created for learning, and not representing any real organization's policies. The fictional company used throughout is "Contoso."

Sample documents are provided in two formats:
- **`docx/`** — Word files, for uploading to SharePoint or editing.
- **`pdf/`** — PDF files, for direct upload to Copilot Studio as file knowledge.

---

### Chapter 09 — Knowledge Sources

`Chapter-09-Knowledge-Sources/`

Five single-topic, FAQ-structured IT documents used to give the IT Helpdesk Agent grounded knowledge to answer from. Each maps to one of the agent's five topics, so knowledge answers reinforce the same domains the topics handle.

| Document | Answers questions like | Maps to topic |
|---|---|---|
| Contoso_IT_VPN_Setup_Guide | *How do I set up VPN on my Mac?* | Network Troubleshooting |
| Contoso_IT_Password_Policy_and_Reset_FAQ | *What are the password requirements?* | Password Reset |
| Contoso_IT_Software_Installation_Guide | *How do I request new software?* | Software Installation |
| Contoso_IT_Hardware_Request_and_Catalog | *What laptops are available for new employees?* | Hardware Request |
| Contoso_Company_Travel_Policy_FAQ | *What is our company travel policy?* | (general knowledge) |

**Two ways to use them (see Chapter 9, Section 9.3):**
1. **SharePoint** — create a document library named **IT Knowledge Base**, upload the files from `docx/`, then add that library as a SharePoint knowledge source.
2. **Files** — upload the files from `pdf/` directly as file knowledge in your agent.

---

### Chapter 10 — Agent Instructions

`Chapter-10-Agent-Instructions/`

A ready-to-use agent instruction block for the IT Helpdesk Agent, assembling all five sections of the Instruction Template (Role, Scope, Tone, Constraints, Format) plus a grounding line.

| File | What it is |
|---|---|
| it-helpdesk-instructions.txt | Copy-paste instruction block for the agent's Instructions field (Overview → Instructions → Edit), with a mapping to the template and usage notes. |

**How to use (see Chapter 10, Section 10.2):** open the file, copy the instruction block, and paste it into your agent's Instructions field on the **Overview** page. Refine any line to fit your organization, then test as described in the chapter.

Note: in the book's Classic-orchestration agent, instructions shape the **tone, format, and wording** of generative answers — they do not drive decisions or actions (like escalating to a human). Those are built as authored topic flows. See the Architecture Insight in Section 10.1.

---

### License and updates

Sample code and text in this repository are released under the MIT License (see `LICENSE`). All sample content is illustrative and fictional.

Resources may be refreshed after publication; this repository always holds the latest version.

*Companion resources for the book. Download root: https://cloudarchstudio.com/copilot-studio-book/companion*
