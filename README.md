AI Internet Source Verification
Search the internet. Verify the facts. Cite the original sources. Never fabricate information.

An evidence-first AI skill for ChatGPT, Claude, and other AI assistants that perform internet searches and online research.

This project establishes strict rules for how AI assistants search, collect, evaluate, verify, and present information obtained from the internet.

Every externally sourced factual claim must be traceable to a genuine source.

Why This Project Exists

AI assistants frequently produce information that sounds convincing but is not necessarily accurate.

Common problems include:

Invented facts and statistics.
Fabricated research papers and citations.
Fake or incorrect URLs.
Information taken from unreliable websites.
Repeating claims without checking their original sources.
Presenting outdated information as current.
Using search result snippets without inspecting the actual pages.
Misrepresenting secondary reporting as original research.
Failing to identify where datasets and statistics originated.

Searching the internet does not automatically make an answer accurate.

An AI assistant must investigate the information, inspect its sources, evaluate its reliability, and establish its origin before presenting it as verified.

This project aims to make internet research more transparent, accountable, and independently verifiable.

Core Objectives
1. Mandatory Source Attribution

Whenever an AI retrieves factual information from the internet, it must provide the source.

For important externally sourced factual claims, it must identify:

What information is being presented.
Where the information was found.
Who published or maintains the source.
The direct URL.
The specific page, section, or document supporting the claim.
The publication or update date, when available.
Whether the source is original or secondary.
How the information was verified.
2. Original Source Verification

The AI must trace information back to its original source whenever possible.

For example:

If a news article reports a scientific finding, the AI should locate and inspect the original research paper rather than treating the news article as the original evidence.

If a website publishes statistics, the AI should investigate the original dataset or institution responsible for those statistics.

A website mentioning information does not automatically make it the original source.

3. Search Result Verification

Search engine results are discovery tools, not proof.

The AI must:

Open the actual source.
Inspect the relevant content.
Verify that the source supports the claim.
Check publication dates.
Identify the original publisher.
Investigate conflicting information.
Avoid relying exclusively on search snippets or AI-generated summaries.
4. Data Origin and Provenance

Whenever the AI uses online datasets, statistics, or research findings, it must investigate:

Who originally collected the data?
Who published it?
Where did it originate?
What methodology was used?
When was it collected?
Has it been processed or transformed?
Is it original, derived, estimated, or synthetic?
Can the original data be accessed?

Unknown origins must be explicitly identified as unknown.

5. Source Reliability Assessment

Sources must be evaluated rather than blindly trusted.

Preferred source hierarchy:

Original datasets and primary evidence.
Official documentation and publications.
Original research papers.
Government and institutional records.
Official technical specifications.
Independent authoritative research.
Reputable secondary publications.
General reference websites.

The AI must distinguish primary, secondary, and tertiary sources.

6. Independent Cross-Verification

For important, disputed, scientific, statistical, technical, or financial claims:

Seek at least two genuinely independent authoritative sources when available.
Prioritize original evidence.
Check whether sources repeat the same underlying publication.
Identify contradictions.
Explain disagreements.
Never manufacture supporting sources.
7. Anti-Hallucination Requirements

The AI must NEVER:

Invent facts or statistics.
Fabricate URLs or citations.
Invent authors or publications.
Claim to have inspected sources it never accessed.
Present search snippets as verified evidence.
Invent research findings.
Misrepresent estimated information as actual data.
Present outdated information as current.
Hide uncertainty.
Fill missing information with assumptions.

If a claim cannot be verified, the AI must explicitly say so.

Mandatory Source Disclosure Format

For internet research, important factual claims should be accompanied by:

Field	Description
Claim	The information being stated
Source	Website, document, paper, or dataset
Publisher	Original author or organization
URL	Direct source link
Source type	Primary, secondary, or tertiary
Source location	Specific section or relevant evidence
Publication date	Original publication or update date
Data origin	Where the underlying information originated
Verification	How the claim was checked
Limitations	Missing or unverified information
Required Verification Labels

The AI must use clear labels when necessary:

VERIFIED — Supported by inspected evidence.
INFERENCE — Reasoned interpretation, not directly established.
UNVERIFIED — Supporting evidence is insufficient.
UNKNOWN ORIGIN — Original provenance could not be established.
SOURCE INACCESSIBLE — The original source could not be inspected.
CONTRADICTORY EVIDENCE — Sources disagree.
Repository Structure
text
ai-internet-source-verification/
│
├── SKILL.md
│
└── README.md

File	Purpose
SKILL.md	Mandatory internet research, source verification, and attribution instructions for AI assistants.
README.md	Project overview, objectives, and usage instructions.
Installation and Usage
Download or clone this repository.
Provide SKILL.md to your AI assistant.
Configure it through the assistant's supported skills or project-instruction mechanism.
Ask the AI to perform internet research.
Verify that it provides genuine sources, direct links, and supporting evidence.

Compatible AI assistants may include:

ChatGPT
Claude
Other AI agents supporting custom instructions or skills.

Loading the file through a supported integration is necessary; simply storing it in a repository does not automatically activate it.

Expected Behavior
AI activity	Expected behavior
Searches the internet	Inspects actual source pages.
Retrieves statistics	Identifies the original data source.
Uses research papers	Links to the original publication.
Uses technical information	References official documentation where available.
Finds conflicting information	Reports the disagreement.
Cannot verify a claim	Clearly identifies it as unverified.
Cannot find original provenance	Discloses unknown origin.
Provides factual conclusions	Supplies supporting source links.
Important Limitations

This skill establishes operating instructions and verification standards. It cannot guarantee that every AI assistant will follow them perfectly.

Source availability, browsing capabilities, and model behavior can affect verification quality.

Users should independently check important findings and citations.

Contributing

Contributions are welcome.

Suggestions and improvements are encouraged, especially around:

Internet source verification.
Original source discovery.
Citation accuracy.
Dataset provenance.
Research reliability.
Detection of fabricated references.
AI hallucination prevention.
Independent fact-checking workflows.
Project Philosophy

Internet search should be about discovering what is true, not finding websites that make an answer sound convincing.

An AI must not confuse a search result with evidence, a repeated claim with independent verification, or a secondary article with an original source.

Every important externally sourced factual claim must be traceable to genuine evidence.

No fabricated facts. No fake citations. No unsupported claims.

Search carefully. Verify independently. Cite transparently.
