# MVP Scope — Thru-Hiking App (PoC)

## Problem we are solving
Hikers and tourists completing long-distance trails over time lack a simple way to:
- aggregate multiple hikes into one journey
- clearly see completed vs remaining trail
- understand progress at a glance
- apply for badges and completion certificates (if any local tourist organization awards badge/certificate)

## Target user (MVP)
- Individual thru-hikers or section hikers
- Tech-comfortable enough to upload GPX files
- Tracking progress for personal motivation (not social sharing)
- Tracking progress of path completion

## Core user flow (happy path)
1. User selects a predefined trail
2. User uploads a GPX file for a completed hike
3. System matches GPX data to trail sections
4. User sees updated progress on the map
5. User views basic cumulative statistics

## Included in MVP (must-have)
- One predefined long-distance trail
- GPX file upload
- Progress visualization on map
- Section-based completion logic
- Basic statistics:
  - distance completed
  - percentage of trail completed
  - number of completed sections

## Explicitly excluded (on purpose)
- Social features (friends, likes, sharing)
- User profiles beyond basic identification
- Route planning or navigation
- Gamification (in-app badges, rankings)
- Offline mode
- Mobile app (web only)

## Key product decisions
- Web-first instead of mobile to reduce scope
- No social layer to focus on core value
- One trail only to validate concept before scaling

## MVP success looks like
- Users complete the full upload → visualization flow
- Users understand progress without explanation
- Users return to upload another GPX file
