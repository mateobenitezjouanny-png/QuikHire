# QuikHire
A simple platform that connects students with short-term freelance gigs quickly and without unnecessary complexity.

## Target User
Students and young freelancers who are looking for quick, short-term jobs (e.g., tutoring, design, delivery, coding help) and don’t want to deal with complicated job platforms.

## Features

### Must Have
- Post a JOB:  Make able to Users to create a job listing with title, description, and budget
- Browse Jobs: Users can view a list of available gigs in a simple feed
- Apply to Job: Users can express interest or apply to a job

### Should Have
- User Accounts: Sign up/login to manage posted jobs and applications
- Job Filtering: Filter jobs by category (e.g., remote, local, design, coding)

### Could Have
- Messaging System: Users can chat after applying to a job

## Data Model
--User
id
name
email
password
createdJobs (list of Job IDs)
appliedJobs (list of Job IDs)
--Job
id
title
description
budget
category
location (remote or city)
createdBy (User ID)
applicants (list of User IDs)
createdAt

Example:
- **Recipe**: title, ingredients (list), steps (list), prep time, category
- **User**: name, email, saved recipes (list)

## Tech Stack
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Deployed on Vercel

## Design
[Figma link will go here]

## Live Demo
[Vercel URL will go here]
