# CineHub

## Problem

Groups of friends in Colombia waste time and lose plans going back and forth in WhatsApp trying to agree on which movie to watch, at what cinema, and at what time. Movie information (showtimes, cinema, poster, rating) gets buried in chat scroll, and there's no single place to propose a plan and see who's actually confirmed to come — so plans quietly fall apart.

## Web App Justification

1. A WhatsApp group can't structure movie data (poster, rating, showtimes, cinema) — it's just scrolling text, and old plans get buried under new messages.
2. A spreadsheet can't show real-time movie listings or let a friend tap "Yes / Maybe / No" on a plan — it has no interactive, shareable view.
3. Existing apps like Cine Colombia or Cinemark let you buy tickets, but they don't help a group agree on *which* movie and *whether everyone is actually coming*.
4. A shareable plan link lets any invited friend confirm attendance in one tap, without needing an account or being added to a group chat.

## Target Users

University students and groups of friends in Colombia who want to plan a movie outing together but struggle to reach a decision and get confirmations through chat alone.

## User Stories

- As a user, I want to search and browse popular movies so that I can decide what to watch.
- As a user, I want to see showtimes and select a cinema, date, and hour so that I can build a plan around a specific screening.
- As a plan creator, I want to share a link to my movie plan so that my friends can see all the details without me repeating them.
- As an invited friend, I want to respond Yes / Maybe / No to a plan so that the organizer knows who is actually coming.

## Team Roles

| Member | GitHub | Role |
|---|---|---|
| Samuel | [@samuraidm45-create](https://github.com/samuraidm45-create) | Frontend Developer — builds the interface, `index.html`, and the visual structure of CineHub's screens |
| Samuel David Ortiz Pico | [@samueldavidortizpico-hash](https://github.com/samueldavidortizpico-hash) | Backend Developer — application logic, movie/showtime/plan data, feature integration |
| Juan Pablo Vanegas | [@juanpablovanegas](https://github.com/juanpablovanegas) | UI/UX & Project Documentation — Figma wireframes, user experience, and project documentation |

## MVP

**Must work:**
- View movies
- View movie details
- View showtimes
- Select a showtime
- Create a plan
- Display the plan

**Stretch (extension):**
- Share plan via a real shareable link
- Account system
- Real attendance voting
- Database persistence
- Ticket purchase

## AI Log

We used AI (Claude) to help turn our team's WhatsApp planning conversation — where we defined the problem, MVP, and roles — into the structured README format this assignment requires (problem statement, web app justification, user stories in As-a/I-want/So-that format). What changed: the AI organized our informal notes into the specific sections and format the rubric asks for, and phrased the problem statement and justification more specifically (e.g., naming concrete alternatives like WhatsApp groups and existing ticketing apps) instead of the general description we had in chat. The underlying idea, MVP scope, and role assignments are unchanged from what the team agreed on.
