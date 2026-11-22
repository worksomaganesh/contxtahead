# AI-Assisted Production Architecture — CONTXT AHEAD

**Principle:** Google AI Pro is the preferred production infrastructure for research support and selected creative generation. The production system remains modular. No single model, subscription, or video generator should become a hard dependency.

**Primary editor:** DaVinci Resolve.  
**Visual identity:** Fully faceless editorial storytelling.  
**Primary narration:** Creator-recorded voice.  
**Research and planning:** Google AI tools + original sources + Creator-OS shared workflow.

## 1. Department tool map

| Department | Primary tool | Purpose | Adoption note |
|---|---|---|---|
| Research | Gemini Deep Research, Google Search, Google Trends | Topic discovery, source discovery, synthesis, research briefs | Verify every material claim against original sources |
| Knowledge | Gemini Notebook / NotebookLM, Google Drive, GitHub | Source-grounded notebooks, research archive, versioned editorial records | Keep claim IDs and source URLs in the content record |
| Scripting | Gemini + Google Docs | Editorial angle, hooks, outline, script drafts, critique | AI draft is not final editorial approval |
| Avatar / identity | No human presenter; brand graphic system | Maintain a distinctive faceless identity | No talking-head or realistic AI-human presenter |
| Video | Google Flow / Veo where useful | Select cinematic or illustrative clips | Use selectively; generated footage is supporting media, not the whole video |
| Images | Nano Banana Pro where available; Canva | Original illustrations, visual assets, thumbnails | Verify product/plan access and avoid generated fake data |
| Voice | Creator-recorded voice | Primary brand narration | Build a recognisable, natural international-English voice |
| Voice specialist | DaVinci Fairlight or Audacity; Gemini TTS as optional fallback | Cleanup, EQ, compression, de-essing, controlled synthetic alternatives | Check TTS terms, costs, usage rights, and disclosure requirements |
| Avatar specialist | Brand asset/continuity owner | Maintain approved logos, graphic motifs, visual references, and continuity | This is not a human-avatar production department |
| Screen recording | OBS Studio | Capture authentic reports, public interfaces, charts, and research walkthroughs | Respect privacy, platform rules, and third-party rights |
| Editing | DaVinci Resolve; Remotion/HTML-SVG motion where appropriate | Assembly, sound, colour, captions, animation, export | Resolve is the finishing environment; code rendering is modular |
| Thumbnails | Canva; original graphics and selected Nano Banana assets | Platform covers and long-form thumbnails | Typography and claims must remain accurate |
| Publishing | YouTube Studio, Meta Business Suite, LinkedIn native tools | Upload, schedule, metadata, analytics | Human approval before publishing |
| Distribution | Platform-native publishing; later newsletter | Adapt content to each platform and build owned audience | No engagement bots or unofficial scraping |

## 2. Google AI Pro usage

Use the subscription for the capabilities actually available to the account:
- Gemini app for analysis, drafting, and critique.
- Deep Research for structured research discovery.
- Gemini Notebook / NotebookLM for source-grounded research and synthesis.
- Google Flow for selected video/image generation and visual experiments.
- Nano Banana image generation where available.
- Google Drive, Docs, and Sheets for the operating system.
- Google Antigravity where the account's plan, age, and regional eligibility permit agent-assisted coding or workflow development.

As checked on 22 November 2026, Google's India AI Pro subscription page lists 1,000 monthly Google Flow credits and expanded access to Gemini, Flow, Gemini Notebook, AI Studio, and other features. Flow's own help documentation describes a daily free-credit allowance plus subscription credits; generation cost depends on the model and tool. Verify the live account UI and current terms before budgeting a production batch:
- https://gemini.google/in/subscriptions/?hl=en-IN
- https://support.google.com/flow/answer/16526234
- https://labs.google/fx/tools/flow

Do not hard-code plan pricing, credit consumption, model availability, or feature access into the production process. These can change by country, account, age eligibility, product, and date.

### API and subscription distinction
A consumer AI subscription does not automatically mean unlimited API usage. Gemini API / AI Studio model usage, TTS, and paid API tiers are governed by their current developer pricing and billing terms. Verify those separately before using them at volume:
- https://ai.google.dev/gemini-api/docs/pricing

## 3. Department responsibilities

### Research
Input: an audience question, trend, development, or community signal.  
Output: a research brief with primary sources, corroboration, claims, limitations, and unanswered questions.

### Knowledge
Store source documents, URLs, access dates, summaries, claim mappings, and updates. Create topic-specific Gemini Notebook/NotebookLM collections, but preserve source metadata in Drive/GitHub so research is portable.

### Scripting
Turn the approved research brief into a story. The script must identify what is known, attributed, interpreted, and uncertain. The hook must not overstate the evidence.

### Avatar / identity
CONTXT AHEAD is faceless. Do not create a synthetic human presenter. A recurring abstract visual guide or geometric motif may be tested later, but it is optional and not a prerequisite for launch.

### Video and images
Generate only scenes that improve understanding. Prefer original charts, timelines, diagrams, screen captures, and motion graphics when factual specificity matters. Generated footage must not be presented as documentary evidence of a real event.

### Voice
Record the creator's own narration as the default. Use a quiet room, consistent microphone distance, controlled pace, and clean delivery. Synthetic TTS is a fallback or controlled experiment, not the assumed brand identity.

### Voice specialist
Maintain audio consistency: remove distracting noise, high-pass gently where needed, control dynamics, reduce harsh sibilance, keep narration intelligible, and check platform playback. Do not apply aggressive processing that makes the voice unnatural.

### Screen recording
Use OBS to capture authentic interfaces and evidence. Blur private account information and avoid showing personal data, credentials, private messages, or restricted material.

### Editing
Build the narrative first, then select visuals. Use Resolve for assembly and finishing; use Remotion or self-authored HTML/SVG/GSAP compositions for repeatable data-driven motion when it saves time.

### Publishing and distribution
Prepare platform-specific titles, descriptions, captions, source links, thumbnails, and aspect ratios. Publish manually or through permitted official tools, with human approval.

## 4. Standard production lifecycle

Signal → audience question → source research → competitor gap analysis → COS score → brand approval → research pack → claim/evidence matrix → editorial brief → script → fact-check → storyboard → narration → visual assets → editing → technical QA → editorial/rights QA → human approval → platform packages → publishing → analytics → corrections/updates.

Every stage must leave a usable artifact. The content ID is the join key.

## 5. Structured episode folder

For each CA-YYYY-NNN episode:
- brief.md
- research-notes.md
- sources.csv
- claims.csv
- timeline.md (when applicable)
- script.md
- storyboard.md
- asset-manifest.csv
- edit-notes.md
- qa-checklist.md
- publishing-pack.md
- analytics.csv or analytics.md
- corrections.md

Store documents and lightweight assets in Git. Store large generated clips, recordings, project caches, and final masters in local/cloud media storage, not Git history.

## 6. Google Flow credit discipline

Spend credits only after the script and storyboard are approved.
- Generate a visual pilot before producing a full set of scenes.
- Use reference assets for consistency where supported.
- Prefer Flow for scenes that are expensive or difficult to create manually.
- Use diagrams, data graphics, and typography for precise factual information.
- Avoid repeated prompts with no documented learning.
- Record model/tool, prompt, output filename, credits if visible, and keep/reject rationale.

## 7. Human checkpoints

Mandatory approvals:
1. Research angle and evidence.
2. Script and narration.
3. First visual pilot and storyboard fit.
4. Final export and rights/accuracy checks.

An AI-generated critique may identify issues, but it cannot approve the publication.

## 8. Tool stack should remain replaceable

Research, voice, image, and video providers must not be hard-coded into a single production format. Keep a provider-neutral asset manifest with the source/provider, model, prompt, generation date, rights notes, output path, and approved status. If Google Flow availability changes, the workflow should still function with original motion graphics and licensed assets.
