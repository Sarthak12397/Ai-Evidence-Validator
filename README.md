# AI Internet Source Verification

**Search the internet. Verify the facts. Cite the original sources. Never fabricate information.**

An evidence-first AI skill for ChatGPT, Claude, and other AI assistants that perform internet searches, research, and information retrieval.

This project establishes strict standards for how AI assistants search, collect, evaluate, verify, and present information obtained from the internet.

The central principle is simple:

> **Every important externally sourced factual claim must be traceable to genuine, inspectable evidence.**

---

## Why This Project Exists

AI assistants can generate convincing answers that are not necessarily accurate.

Common problems include:

- Invented facts, statistics, and research findings.
- Fabricated academic papers and citations.
- Fake, incorrect, or inaccessible URLs.
- Information obtained from unreliable websites.
- Repeating claims without checking their original sources.
- Presenting outdated information as current.
- Relying on search result snippets without inspecting actual pages.
- Misrepresenting secondary reporting as original research.
- Failing to identify the origin of datasets and statistics.
- Treating multiple websites repeating the same claim as independent verification.

Searching the internet does not automatically make an answer accurate.

An AI assistant must investigate the information, inspect its sources, evaluate their reliability, and establish the origin of important claims before presenting them as verified.

**AI Internet Source Verification** aims to make internet research more transparent, accountable, reproducible, and independently verifiable.

---

## Core Objectives

### 1. Mandatory Source Attribution

Whenever an AI retrieves factual information from the internet, it must provide appropriate source attribution.

For important externally sourced factual claims, the assistant should identify:

- **Claim:** What information is being presented.
- **Source:** The website, publication, paper, document, or dataset.
- **Publisher:** The original author or responsible organization.
- **URL:** A direct link to the relevant source.
- **Source type:** Primary, secondary, or tertiary.
- **Source location:** The specific page, section, table, or document supporting the claim.
- **Publication date:** The original publication or update date, when available.
- **Data origin:** Where the underlying information originated.
- **Verification:** How the claim was checked.
- **Limitations:** Any missing, inaccessible, or unverified information.

### 2. Original Source Verification

AI assistants should trace information back to its original source whenever possible.

Examples:

- If a news article reports a scientific finding, locate and inspect the original research paper.
- If a website publishes statistics, investigate the original dataset or institution responsible for collecting the data.
- If an article discusses a government policy, locate the official legislation, regulation, or government publication.
- If technical information is presented, prioritize official documentation and specifications.

A website mentioning information does not automatically make it the original source.

Secondary reporting must not be misrepresented as primary evidence.

### 3. Search Result Verification

Search engine results are discovery tools, not proof.

AI assistants must:

1. Open the actual source whenever accessible.
2. Inspect the relevant content.
3. Confirm that the source supports the claim.
4. Check publication and update dates.
5. Identify the original publisher.
6. Investigate conflicting information.
7. Avoid relying exclusively on search snippets or AI-generated summaries.

If a source cannot be inspected, the assistant must disclose that limitation.

### 4. Data Origin and Provenance

Whenever online datasets, statistics, or research findings are used, investigate:

- Who originally collected the data?
- Who published or maintains it?
- Where did it originate?
- What methodology was used?
- When was the data collected?
- Has it been processed, transformed, or estimated?
- Is it original, derived, estimated, or synthetic?
- Can the original data be accessed?

Unknown origins must be explicitly identified as unknown.

AI assistants must not invent missing provenance information.

### 5. Source Reliability Assessment

Sources must be evaluated rather than blindly trusted.

The preferred source hierarchy is:

| Priority | Source Type |
|---|---|
| 1 | Original datasets and primary evidence |
| 2 | Official documentation and publications |
| 3 | Original research papers |
| 4 | Government and institutional records |
| 5 | Official technical specifications |
| 6 | Independent authoritative research |
| 7 | Reputable secondary publications |
| 8 | General reference websites |

This hierarchy is a guideline, not an absolute guarantee of reliability. Sources must still be evaluated according to relevance, methodology, transparency, and evidence quality.

The assistant must distinguish primary, secondary, and tertiary sources.

### 6. Independent Cross-Verification

For important, disputed, scientific, statistical, technical, or financial claims:

- Seek at least two genuinely independent authoritative sources when available.
- Prioritize original evidence.
- Check whether sources rely on the same underlying publication or dataset.
- Identify contradictions between sources.
- Explain relevant disagreements.
- Distinguish independent corroboration from repeated reporting.
- Never manufacture supporting sources.

If independent verification is unavailable, disclose that limitation.

### 7. Anti-Hallucination Requirements

The AI assistant must NEVER:

- Invent facts or statistics.
- Fabricate URLs or citations.
- Invent authors, publications, or research papers.
- Claim to have inspected sources it never accessed.
- Present search snippets as verified evidence.
- Invent research findings.
- Misrepresent estimates as actual measurements.
- Present outdated information as current.
- Hide uncertainty.
- Fill missing information with assumptions.
- Claim independent verification when sources share the same underlying evidence.

**If a claim cannot be verified, explicitly say so.**

---

## Mandatory Source Disclosure Format

For significant internet research, important factual claims should use the following evidence structure.

| Field | Description |
|---|---|
| Claim | The information being stated |
| Source | Website, document, paper, or dataset |
| Publisher | Original author or organization |
| URL | Direct source link |
| Source Type | Primary, secondary, or tertiary |
| Source Location | Specific section or supporting evidence |
| Publication Date | Original publication or update date |
| Data Origin | Where the underlying information originated |
| Verification | How the claim was checked |
| Limitations | Missing or unverified information |

Not every field will be available for every source. Missing information must be disclosed rather than fabricated.

## Required Verification Labels

AI assistants should use clear verification labels when appropriate.

| Label | Meaning |
|---|---|
| **VERIFIED** | Supported by inspected evidence. |
| **INFERENCE** | Reasoned interpretation, not directly established by the source. |
| **UNVERIFIED** | Supporting evidence is insufficient. |
| **UNKNOWN ORIGIN** | Original provenance could not be established. |
| **SOURCE INACCESSIBLE** | The original source could not be inspected. |
| **CONTRADICTORY EVIDENCE** | Available sources disagree. |

These labels help readers distinguish established facts from interpretations, uncertainty, and missing evidence.

---

## Repository Structure

```text
ai-internet-source-verification/
│
├── SKILL.md
│
└── README.md
```

| File | Purpose |
|---|---|
| `SKILL.md` | Mandatory internet research, source verification, provenance, and attribution instructions for AI assistants. |
| `README.md` | Project overview, objectives, installation, usage, and documentation. |

---

## Installation and Usage

### Step 1: Download the Repository

Clone the repository:

```bash
git clone https://github.com/USERNAME/ai-internet-source-verification.git
```

Or download the repository as a ZIP file from GitHub.

### Step 2: Provide the Skill to Your AI Assistant

Locate the `SKILL.md` file.

Provide it to your AI assistant through a supported skills, custom instructions, or project-instruction mechanism.

### Step 3: Configure the Skill

Follow the installation requirements of your chosen AI platform.

Simply storing the file in a repository does not automatically activate it.

### Step 4: Perform Internet Research

Ask your AI assistant to conduct internet research using the verification requirements defined in `SKILL.md`.

Example:

```text
Research this topic using the AI Internet Source Verification skill.

Requirements:
- Search the internet.
- Inspect original sources.
- Verify important factual claims.
- Trace statistics to their original datasets.
- Cross-check important findings independently.
- Provide direct source URLs.
- Identify source types and publication dates.
- Disclose uncertainty and inaccessible sources.
- Never fabricate facts or citations.
```

### Step 5: Review the Evidence

Independently inspect important sources and verify that the cited documents actually support the presented claims.

---

## Compatible AI Assistants

The project is intended for AI assistants that support internet search, external research, and custom instructions or skills.

Potential compatible platforms include:

- ChatGPT
- Claude
- Other AI agents supporting custom instructions, project instructions, or skills.

Actual compatibility depends on each platform's browsing capabilities and skill-loading mechanisms.

---

## Expected AI Behavior

| AI Activity | Expected Behavior |
|---|---|
| Searches the internet | Inspects actual source pages. |
| Retrieves statistics | Identifies the original data source. |
| Uses research papers | Links to the original publication. |
| Uses technical information | References official documentation where available. |
| Encounters conflicting information | Reports the disagreement. |
| Cannot verify a claim | Clearly identifies it as unverified. |
| Cannot establish original provenance | Discloses unknown origin. |
| Encounters inaccessible sources | Identifies the source as inaccessible. |
| Provides factual conclusions | Supplies supporting source links. |
| Uses secondary reporting | Identifies it as secondary evidence. |
| Uses multiple sources | Checks whether they are genuinely independent. |

---

## Important Limitations

This project establishes operating instructions and verification standards. It cannot guarantee that every AI assistant will follow them perfectly.

Verification quality depends on several factors:

- Availability of internet browsing.
- Accessibility of original sources.
- Accuracy and completeness of published information.
- Quality of available datasets.
- AI model capabilities and behavior.
- Platform support for custom skills and instructions.

Some original sources may be unavailable, paywalled, deleted, incomplete, or restricted.

Some claims may not have independently verifiable evidence.

In these situations, the AI must disclose the limitations instead of pretending verification was successful.

Users should independently check important findings, evidence, and citations.

---

## Contributing

Contributions, suggestions, and improvements are welcome.

Areas where contributions are especially valuable include:

- Internet source verification.
- Original source discovery.
- Citation accuracy.
- Dataset provenance.
- Research reliability.
- Detection of fabricated references.
- Independent fact-checking workflows.
- AI hallucination prevention.
- Evidence traceability.
- Transparent uncertainty reporting.

Contributors are encouraged to suggest improvements that strengthen research quality, accountability, and reproducibility.

---

## Project Philosophy

Internet search should be about discovering what is true, not finding websites that make an answer sound convincing.

An AI assistant must not confuse:

- A search result with evidence.
- A repeated claim with independent verification.
- A secondary article with original research.
- An estimate with an actual measurement.
- A citation with proof.
- An accessible URL with a verified source.
- A plausible answer with an established fact.

Every important externally sourced factual claim must be traceable to genuine evidence.

**No fabricated facts. No fake citations. No unsupported claims.**

**Search carefully. Verify independently. Cite transparently.**

---

## License

Add a `LICENSE` file to the repository to specify the terms under which others may use, modify, and distribute this project.

---

**AI Internet Source Verification**

*An evidence-first approach to reliable AI-powered internet research.*
