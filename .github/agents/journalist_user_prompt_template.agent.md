## User Prompt Template (for Journalist Agent)

Write a comprehensive technology journalism article on the following topic:

**TOPIC:** {{ $json.output.requered_agents[0].reasoning }}

**ARTICLE TYPE:** {{type}} (news analysis / investigative feature / explanatory piece / profile / think piece)

**TARGET LENGTH:** {{ $json.output.estimated_tokens }} words (default: 2500-3000)

**CONTEXT:**
- **Target Audience:**  general tech-interested readers, policy makers, tech workers
- **Angle/Focus:** labor impact, privacy concerns, environmental cost, ethical dimensions

**REQUIRED ELEMENTS:**
- Multiple perspectives (minimum 5 sources/viewpoints)
- Balance technical explanation with social impact
- Investigative depth: deep
- Critical analysis emphasis: strong

**POTENTIAL CHALLENGES**
- {{ $json.output.requered_agents[0].potencial_challenges.join(';') }}

**QUALITY CRITERIA**
- {{ $json.output.requered_agents[0].quality_criteria.join(';') }}

**DIMENSIONS TO EXPLORE:**
- [ ] Social impact (labor, equity, access)
- [ ] Economic implications (business models, value capture)
- [ ] Ethical considerations (privacy, autonomy, fairness)
- [ ] Environmental cost (energy, e-waste, sustainability)
- [ ] Policy/governance questions
- [ ] Philosophical/cultural dimensions

**TONE:** Serious, balanced, inquisitive journalism (not advocacy, not promotional)

**DELIVERABLES:**
1. Complete article with compelling lede and nut graf
2. Multiple section structure exploring different dimensions
3. Proper attribution for all claims
4. Balanced conclusion that synthesizes tensions
5. Suggested further reading (3-5 links)

---

## Example Request/Response

### Request:

Write a comprehensive technology journalism article on the following topic:

**TOPIC:** AI Coding Assistant Tools - Impact on Software Engineering Jobs and Skills

**ARTICLE TYPE:** Investigative Feature *(news analysis / investigative feature / explanatory piece / profile / think piece)*

**TARGET LENGTH:** 3200 words *(default: 2500-3000)*

**CONTEXT:**
- **Target Audience:** general tech-interested readers, policy makers, tech workers
- **Angle/Focus:** labor impact, skill evolution, educational disruption, workforce transformation

**REQUIRED ELEMENTS:**
- Multiple perspectives (minimum 7 sources/viewpoints)
- Balance technical explanation with social impact
- Investigative depth: deep
- Critical analysis emphasis: strong

**POTENTIAL CHALLENGES:**
- Avoiding technological determinism while acknowledging real disruption
- Balancing optimistic industry narratives with worker concerns
- Capturing rapidly evolving landscape of AI capabilities
- Distinguishing between hype and measurable impact on employment
- Addressing generational divides in adoption and perception

**QUALITY CRITERIA:**
- Evidence-based analysis with quantitative data on job market trends
- Diverse voices from entry-level to senior engineers across different company sizes
- Critical examination of training data ethics and intellectual property issues
- Forward-looking analysis of skill requirements evolution
- Balanced perspective that neither dismisses concerns nor amplifies panic

**DIMENSIONS TO EXPLORE:**
- [x] Social impact (labor, equity, access)
- [x] Economic implications (business models, value capture)
- [x] Ethical considerations (privacy, autonomy, fairness)
- [ ] Environmental cost (energy, e-waste, sustainability)
- [x] Policy/governance questions
- [x] Philosophical/cultural dimensions

**SPECIFIC INVESTIGATION AREAS:**
- Junior developer job market changes since AI coding tools mainstream adoption
- Bootcamp and CS education curriculum adaptations
- Open source code training data usage and attribution issues
- Productivity metrics vs. employment data in tech companies using AI tools
- Skill premium shifts in software engineering compensation

**SOURCES TO INCLUDE:**
- Recent computer science graduates seeking entry-level positions
- Senior engineers at companies with mandatory AI tool adoption
- Coding bootcamp instructors and career services staff
- Labor economists specializing in technology sector employment
- GitHub/Microsoft executives and product managers
- Open source maintainers whose code was used in training data
- Engineering managers tracking productivity and team composition changes
- Software engineering educators adapting curriculum

**KEY QUESTIONS TO INVESTIGATE:**
1. Are AI coding tools creating a "skill cliff" that makes entry-level programming jobs scarce?
2. How are companies measuring AI-assisted developer productivity, and what are the real numbers?
3. What happens to software craftsmanship and deep technical understanding in an AI-assisted world?
4. How should compensation work when AI tools trained on open source code generate commercial value?

**TONE:** Serious, balanced, inquisitive journalism *(not advocacy, not promotional)*

**DELIVERABLES:**
1. Complete article with compelling lede and nut graf
2. Multiple section structure exploring different dimensions
3. Proper attribution for all claims
4. Balanced conclusion that synthesizes tensions
5. Suggested further reading (3-5 links)

---

**RESEARCH DEPTH REQUIREMENTS:**
- Interview minimum 8 people across different roles and perspectives
- Include at least 3 quantitative data points (job postings, salary trends, productivity metrics)
- Analyze at least 2 specific case studies of companies or educational institutions
- Reference recent academic research on AI impact on software development work