# Taskline Mobile — 60-day plan

Day 1 = 2026-11-07. Check off as you go; commit with `./commit.sh` referencing the day.

## Phase 1 — Foundations (day 1–14)
- [ ] D1  Clean template scaffold: remove demo game code, CI green
- [ ] D2  Folder structure: screens/, components/, lib/api
- [ ] D3  API client for taskline-api (typed fetch wrapper, JWT)
- [ ] D4  Auth screen: login/signup wired to JWT endpoints
- [ ] D5  Token storage (secure storage preference)
- [ ] D6  Boards list screen
- [ ] D7  Board screen: columns + cards render
- [ ] D8  Card detail view
- [ ] D9  Loading / error states
- [ ] D10 README screenshots placeholder
- [ ] D11 Env config (API base URL)
- [ ] D12 First component tests (rstest)
- [ ] D13 Navigation setup (tabs: boards, settings)
- [ ] D14 Phase 1 retro

## Phase 2 — Depth (day 15–40)
- [ ] D15 Card moves between columns (tap or long-press menu first)
- [ ] D16 Card create/edit form
- [ ] D17 Card comments view
- [ ] D18 Due dates display
- [ ] D19 Pull-to-refresh on boards
- [ ] D20 Infinite scroll on card lists
- [ ] D21 Action Cable client or polling for presence
- [ ] D22 Room list screen
- [ ] D23 Room chat (text) screen
- [ ] D24 Optimistic updates for card moves
- [ ] D25 Offline caching of boards (local storage)
- [ ] D26 Push-notification-ready local reminders (due dates)
- [ ] D27 Dark/light theme via Lynx theme vars
- [ ] D28 Component tests: board, cards, chat
- [ ] D29 Snapshot tests for screens
- [ ] D30 Accessibility pass (labels, contrast)
- [ ] D31 Performance: list virtualization
- [ ] D32 Error boundary + retry screens
- [ ] D33 README: screenshots
- [ ] D34 Refactor: shared UI primitives
- [ ] D35 Demo seed login flow
- [ ] D36–D40 Buffer / stretch: gestures for drag-and-drop

## Phase 3 — Polish (day 41–60)
- [ ] D41 Test coverage push
- [ ] D42 README: demo GIF
- [ ] D43 CHANGELOG.md
- [ ] D44 Docs: architecture note
- [ ] D45 Tag v0.1 release
- [ ] D46 Cross-link taskline-api and taskline-web
- [ ] D47–D60 Buffer / stretch: profile screen, settings, board search
