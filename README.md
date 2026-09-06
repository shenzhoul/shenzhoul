# Hi, I'm Hoa 👋

I'm a **Frontend / Full-stack Developer** building interactive web applications with React, Next.js, TypeScript and Node.js.

My recent work has centred on **frontend architecture, real-time applications, social-platform interactions, frontend performance, and media-heavy web experiences**.

## Tech Stack

**Frontend**

React · Next.js · TypeScript · JavaScript · Tailwind CSS · TanStack Query

**Backend**

Node.js · NestJS · MongoDB · Redis · REST APIs

**Real-time & Media**

Socket.IO · BullMQ · FFmpeg · Sharp

**Infrastructure & Tools**

Docker · Nginx · Cloudflare R2 · Git · GitHub · Bitbucket

## Featured Project

### 🎬 Short Video Platform

A production-deployed full-stack short-video and photo social platform: creator publishing, a discovery feed alongside a personalized recommendation feed, real-time interactions, messaging and notifications, and an asynchronous media pipeline.

**[▶ Live Demo](https://app.136.85.26.121.sslip.io)** · **[Source Code](https://github.com/shenzhoul/short-video-platform)**

**Highlights**

- Two distinct feeds: a **Home** discovery feed for broad browsing, and a personalized **For You** feed ranked from the viewer's own affinity and watch behaviour
- A heuristic recommendation engine — interaction signals, decayed affinity profiles, diversity re-ranking, and session-based pagination that avoids repeats within a browse
- Short-video and multi-image publishing, with creator profiles and content management
- Real-time interactions over Socket.IO: comments, replies, likes, follows and mentions stay in sync across every view of a post
- Private messaging with follow-based permissions, plus grouped notifications with live delivery
- Asynchronous media pipeline — FFmpeg and Sharp on BullMQ workers, with media served from Cloudflare R2 over range requests so video seeking works
- Four independently deployed applications (user, admin, API, file server) running in Docker behind Nginx with TLS, covered by automated test suites

**Tech:** Next.js · React · TypeScript · NestJS · MongoDB · Redis · Socket.IO · BullMQ · FFmpeg · Cloudflare R2 · Docker

## What I'm Currently Working On

Refining the Short Video Platform: frontend performance, the recommendation experience, real-time interaction flows, and expanding automated test coverage.

## Contact

I'm currently open to **Frontend Developer** opportunities.
