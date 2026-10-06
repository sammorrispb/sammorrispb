# Sam Morris

**Coach, community builder, and product builder turning the friction around pickleball into practical software.**

I build tools that help people find their place in the game—and help the people behind the scenes deliver a better experience.

My perspective comes from 12 years as a PE teacher, a master's in coaching, and hands-on work leading pickleball programs, developing young players, and organizing local communities. I understand the questions families ask, the coordination players need, and the operational decisions that keep programs running.

That experience shapes how I build: understand the people, find the friction, turn it into a clear workflow, and test whether the next step actually works.

[Youth programs](https://nextgenpbacademy.com/) · [Link & Dink](https://www.linkanddink.com/paddle) · [Work with me](https://www.sammorrispb.com/contact)

## The problem space

Getting someone onto a court involves more than finding an open time.

A family needs an appropriate starting point. A player needs people whose skill, schedule, and goals fit. A coach needs a repeatable way to teach and assess progress. An organizer needs registration, communication, and reliable information. A facility needs programming that brings people back.

My projects address different parts of that experience: **discover → join → play → improve → return.** They share a problem space; each has its own purpose and stage of development.

## What I bring to a problem

- **Domain knowledge:** I can connect a feature request to what happens on the court, at the front desk, or in a parent's inbox.
- **Product thinking:** I translate broad requests into specific users, decisions, workflows, and manageable releases.
- **Systems thinking:** I look at how discovery, scheduling, communication, payments, and follow-up affect one another.
- **Practical implementation:** I build web interfaces, connect APIs, structure data, and automate repetitive work.
- **Verification:** I use typed code, browser tests, and scenario-based checks to examine the paths people depend on.

## Featured work

### Next Gen Pickleball Academy — Help families find their starting point

**Problem:** Parents need to understand whether a program fits their child and what to do next.

**My approach:** Bring youth program and schedule discovery together with evaluation, lesson, registration, contact, and waitlist entrypoints.

**What it demonstrates:** Translating coaching knowledge into a clear family-facing experience, with reusable session components and Playwright tests.

[Visit the site](https://nextgenpbacademy.com/) · [Public code](https://github.com/sammorrispb/nextgen-academy)

### Link & Dink / Community OS — Connect participation with the work behind it

**Problem:** Players experience a community through games and relationships; organizers have to coordinate the systems that make those experiences possible.

**My approach:** Build Community OS as the platform behind Link & Dink, with shared foundations for identity, payments, and attendance. The broader direction connects player discovery and organization with community and facility operations.

The public paddle finder addresses one concrete decision: helping players connect equipment choices with their preferences and game, alongside links to local groups and play.

**What it demonstrates:** Thinking across player experience, operational workflows, and shared platform architecture.

[Explore the paddle finder](https://www.linkanddink.com/paddle) · Core repository: `community-os` — private

### Rally — Turn “I want to play” into a session plan

**Problem:** Organizing a game means translating preferences into a plan, choosing whom to invite, and tracking responses.

**My approach:** Build a conversational session-planning agent that prepares a plan and player shortlist for approval, then manages invitations and RSVPs.

The current development milestone includes authenticated mobile web chat, saved conversations, reviewable proposals, and in-app updates. Learning recurring groups and external notifications remain future work.

**What it demonstrates:** AI-assisted coordination with explicit approvals, permission checks, and scenario-based evaluation.

Repository: `rally` — private, in development

### Sam Morris Pickleball — Turn interest into a useful next step

**Problem:** Players exploring coaching need help understanding their options and making contact.

**My approach:** Bring programs, inquiries, educational content, and a skill quiz into one coaching website.

**What it demonstrates:** Connecting content, self-assessment, search, and inquiry flows, with fuzzy search and keyboard navigation in the public source.

[Visit the site](https://www.sammorrispb.com/) · [Public code](https://github.com/sammorrispb/sam-morris-website)

## Supporting systems

Some of the most useful work happens behind the scenes. These repositories are private.

| Repository | Problem it addresses | Approach |
| --- | --- | --- |
| `nga-coaching-system` | Keeping instruction consistent across coaches | Version-controlled coaching handbook, onboarding, shared vocabulary, and lesson tools |
| `nga-weather-watch` | Spotting weather risk before booking decisions become urgent | Forecast checks tied to upcoming bookings and refund windows |
| `open-brain` | Retrieving useful context across projects and conversations | Semantic search, CRM workflows, and decision tracking |

## Earlier work

These public repositories are archived. They show earlier approaches to local discovery, competition, and community administration.

| Project | Its part of the community experience | Engineering example |
| --- | --- | --- |
| [MoCoPB](https://github.com/sammorrispb/mocopb) | Finding local courts and community information | Indoor/outdoor court directory and location pages |
| [Tournament Series](https://github.com/sammorrispb/tournament-website) | Following a season's events and standings | Notion pagination, medal aggregation, tiebreakers, and caching |
| [Circle Community Manager](https://github.com/sammorrispb/circle-community-manager) | Managing members, events, and community posts | Claude Code plugin and cross-system API workflows |
| [Link & Dink / P3 prototype](https://github.com/sammorrispb/link-and-dink) | Discovering competitive pop-up events | Early discovery interface and stubbed RSVP flow |

## Technical toolkit

**Web:** TypeScript · JavaScript · React · Next.js · Tailwind CSS  
**Data & integrations:** Supabase · PostgreSQL · API integrations · pgvector  
**Automation & quality:** AI tool workflows · MCP · Playwright · scenario-based evaluation

## Let's build something useful

I'm interested in product and technical opportunities where understanding people, operations, and software matters—especially in sports, youth development, and local communities.

If you're working on a problem in that space, [let's talk](https://www.sammorrispb.com/contact).

