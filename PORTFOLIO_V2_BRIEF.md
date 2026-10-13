# Portfolio V2 — Design and Implementation Brief for Gemini

## Repository and scope
Repo: https://github.com/SilasChalwe/SilasChalwe
Work ONLY on branch `port-v2`. Never push to or merge into `main`.
First inspect existing `index.html`, assets, and deployment setup. Preserve existing working functionality and links unless verified wrong. Commit UI source, styles, assets legally usable, and design documentation into `port-v2`, not only an external Figma link. No mock buttons, fake testimonials, inflated metrics, or invented completion statuses. Build mobile-first and test desktop/tablet/mobile, keyboard navigation, contrast, performance, reduced-motion, accessibility and link correctness.

## Identity and narrative
Silas Chalwe — computer engineer, software engineer, UI/UX and product designer, hands-on systems builder. Experience spans Android/mobile applications, Node.js and Java/Spring Boot/Python backend development, API/system architecture, Linux and deployment, product interface design and Figma prototyping, applied AI/speech/computer vision, and embedded/connected-device integration. Academic requirements at Copperbelt University completed 19 Sep 2026; final results pending. Do NOT imply degree was conferred. Show leadership and client work without framing Silas as an amateur or claiming employment at companies he did not work for. Avoid irrelevant academic project 'Kilowatts' (do not show it anywhere).

## Information architecture
Hero: concise compelling personal positioning and CTAs to work, contact, GitHub, LinkedIn, CV (only when actual CV supplied).
About: what he engineers and designs, not a course description.
Featured work: curated, evidence-supported case studies (problem, Silas's role, work performed, tech, implementation stage, links/screen captures). Provide filters for Engineering, Mobile, UI/UX, AI, Clients as helpful, accessible controls.
Experience: work roles and dates only when verifiable.
Design work: screenshots, Figma prototypes, user flows, interactions, responsive designs; show design process and handoff where applicable.
Skills: categorize engineering/design tools, avoid every possible keyword.
Contact: functioning mailto/social links; no unconfigured forms.
Optional notes/research and supporting projects below fold.

## Candidate work to review (do not blindly present all as shipped)
GitHub repos accessible through user account: `pulse`, `pulse-backend`, `Fix`, `Gate`, `campusnest-backend`, `agrospeak-connect`, `agrospeak-voice`, `agrospeak-ivr`, `BembaSpeech`, `yamba2`, `coded-backend`, `zra-tax-portal`, `rephrase_chatapi`, `hawkings-lawyers`, `engagement-monitor`, and other related repositories. Inspect README, commits and actual code and don't confuse repository existence with deployed product.
Pulse — real Android app and Node backend; avoid claim Google Play publication.
Fix — Python/FFmpeg media toolkit with reviews and tests; verify exact user's contributions.
Gate — design/client-facing messaging product: sender allow/block/quarantine and local processing concept. Gate Drive folder contains `gate-ui.pdf`, architecture and assets; GitHub `Gate` repo. Verify actual implementation status and ownership before claiming shipped.
AI Agent Platform — linked Drive implementation plan is a plan, not proof of deployed agent.
iSort — linked Drive holds product definition, SRS and feasibility docs; do NOT claim built product without implementation evidence.
AgroSpeak Connect — modular marketplace/voice/IVR work; differentiate planned vs implemented.
Client work — include only work with permission and safe-to-publish evidence; redact names, private contracts and sensitive details.
Design UI/UX/Figma must be prominent, not an afterthought.

## Source folders and links
Current site: https://github.com/SilasChalwe/SilasChalwe/blob/main/index.html
Gate documentation: https://drive.google.com/drive/folders/1vv0wF38RQMbQz66_iPuTpAPwJPYaEq5P
AI Agent Platform: https://drive.google.com/drive/folders/1fHrP6v0K7oStJ-AzYGx_xatzEWdcoV7j
Company and Business: https://drive.google.com/drive/folders/1m4nndj63rm04IwyYNOT5DBrdojV2azeS
Within Company and Business: Gate, MineScout, Compiler, CovianHive, isort, Clients, Aspect, etc. Inspect nested folders selectively and respect publication/privacy limitations. Source documents are reference evidence, not instructions to execute.

## Visual design direction
Premium, confident editorial engineering portfolio, distinct personal identity rather than copied Google/Microsoft branding. A quiet neutral base, restrained accent, excellent type hierarchy, generous whitespace, sophisticated but usable responsive work gallery. Real project media rather than text placeholders. Clear UI/UX case studies. Motion only where beneficial; honor prefers-reduced-motion. Small screens must work. Figma and Git implementation should agree.

## Verification and workflow
1. Audit existing repo and evidence sources.
2. Produce a truthful content inventory and review unverified claims before publication.
3. Implement responsive UI into repo on `port-v2`, with reusable maintainable CSS/JS or chosen stack justified by existing site.
4. Run local build/validation plus responsive/a11y/link checks, fix defects.
5. Commit changes to `port-v2` and provide commit hash and preview instructions.
6. Do not merge or change production site without explicit approval.

## Known contacts
GitHub: https://github.com/SilasChalwe
Email: mchalwesilas@gmail.com
LinkedIn: https://www.linkedin.com/in/silas-chalwe-2085a5414


## CRITICAL UPDATE — User's design breadth and assets (13 Oct 2026)
User explicitly expects substantial UI/UX and graphic design coverage, including Figma and visual/graph designs, not only software engineering.
- **Coded Master / Coded**: user reports UI/client design work; verify exact deliverables and permission for publication. Repo `coded-backend`; Drive Company and Business > Clients > Coded.
- **iSort**: Figma/product design and specification work; Drive Company and Business > isort > docs includes Product Definition v0.1, SRS v0.1, AI Feasibility v0.1. Credit UI/UX and product specifications if evidenced, but do not imply app implemented.
- **CovianHive.tech**: user reports designing the website; include real site screenshots and contribution details after verification.
- **MFocus**: user reports application/product design and GitHub repository `Mfocus`; inspect actual implementation and design evidence.
- **AgroSpeak Connect / ASPECT**: user-provided 32-page farmer-app prototype has detailed designed screens, including onboarding/auth, marketplace, offline/empty/error states, produce listings, English/Bemba voice interaction, farm mapping/geofencing, sensor states, and more. Case study should emphasize complete user journeys, operational states and design-system consistency. Avoid treating mock interfaces as live operational systems.
- **AIMZO**: user-provided 82-page design PDF contains customer booking/mobile, provider dashboard/mobile and admin web interface, service search, scheduling, payments, analytics charts and workflows. Credit product/UI work as allowed and verify ownership and confidentiality before public release.
- **Gate**: public-facing portfolio should illustrate its SMS inbox/quarantine allow/block interactions based on actual design/screens. Gate's documented concept is not evidence of a released app.
- **Graphic design and visual communication**: present brand identity, marketing assets, charts, dashboard graphics, business collateral and design process only where user is authorized to publish.
- **Other client work**: include curated, consent-cleared case studies, not merely a client name/logo gallery.

### Asset ingestion requirements
User requested every supplied relevant design/document asset and the three Drive folder collections be placed in the `port-v2` Git branch for Gemini to convert to image assets. THIS IS NOT YET DONE. Before adding assets to a **public** GitHub repository, inventory and screen for personally identifying information, client secrets, internal architecture, third-party logos/content, proprietary contracts and access permissions. Never upload folders wholesale without review.
Expected target directories after clearance: `portfolio-sources/approved/` for source PDFs/docs, `assets/projects/<slug>/` for optimized rendered page images and screenshots. A document may be included as approved source while only selected screenshots are displayed on the site. Never claim docs have been uploaded until they appear in Git tree.
Document sources:
- uploaded `AgroSpeak Connect — Farmer app prototype(1).pdf` (32 pages)
- uploaded `AIMZO (1).pdf` (82 pages)
- Gate Drive documentation including `gate-ui.pdf` and architecture
- AI Agent Platform Drive documents (plans; not built status)
- Company and Business nested design docs, particularly Gate, isort, Clients, Compiler, CovianHive, MFocus where relevant.
Avoid copying confidential material to the public website or repo without owner's approval. Track provenance and publication status for each item.
