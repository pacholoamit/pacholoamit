[![MasterHead](./assets/header-one.png)](https://github.com/pacholoamit)
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pacholoamit/pacholoamit/snake-svg/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pacholoamit/pacholoamit/snake-svg/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/pacholoamit/pacholoamit/snake-svg/github-snake.svg" />
</picture>
<!-- ![Github snake svg](https://raw.githubusercontent.com/pacholoamit/pacholoamit/snake-svg/github-contribution-grid-snake.svg) -->

<h3 align="left">Languages and Tools</h3>

[![My Skills](https://skillicons.dev/icons?i=ts,go,rust,nodejs,dart,py,bash,aws,gcp,apollo,prisma,graphql,react,redis,docker,kubernetes,express,nestjs,firebase,flutter,git,github,grafana,linux,materialui,mongodb,mysql,postgres,supabase,heroku,netlify,js,html,css,bootstrap)](https://skillicons.dev)

### 👋 Hello, I'm Pacholo

:octocat: I joined Github on `21 Aug 2020`.

:people_hugging: I contributed to `47` repositories , made `10218` commits and made `234` PRs.

<img src="/assets/code.gif" width="390" align="right" />
<p>🔭 I'm currently working on <b> Distributed systems </b></p>
<p>📝 I regularly write articles on <b><a href="https://dev.to/pacholoamit">Dev.to</a> and <a href="https://blogs.pacholoamit.com/">Hashnode</a> </b></p>
<p>💬 Want to know more about me? Visit my  <b><a href="https://www.pacholoamit.com/"> Website</a></p>
<p> 📫 Reach me at <b>pacholoamit.tech@gmail.com</b></p>
<p>⚡ I make software engineering tutorials on <b><a href="https://www.youtube.com/channel/UCIrEp6SsrStyP5btF9ZX1Uw">Youtube</a></b></p>

### Find me here 💻</h3>

[<img src='https://ico.now.sh/github/fff' alt='github' height='40'>](https://github.com/pacholoamit) [<img src='https://ico.now.sh/devdotto/fff' alt='dev' height='40'>](https://dev.to/pacholoamit) [<img src='https://ico.now.sh/hashnode/fff' alt='dev' height='40'>](https://blogs.pacholoamit.com/) [<img src='https://ico.now.sh/stackoverflow/fff' alt='stackoverflow' height='40'>](https://stackoverflow.com/users/14199991/pacholoamit) [<img src='https://ico.now.sh/youtube/fff' alt='YouTube' height='40'>](https://www.youtube.com/channel/UCIrEp6SsrStyP5btF9ZX1Uw) [<img src='https://ico.now.sh/gmail/fff' alt='gmail' height='40'>](pacholoamit.tech@gmail.com) [<img src='https://ico.now.sh/linkedin/fff' alt='linkedin' height='40'>](https://www.linkedin.com/in/pacholo-amit/)

### What I've been up to 🤔

**[📰 Recent activity](https://github.com/pacholoamit)**
* 🔍 Reviewed [#106 Add &#39;dealId&#39; field to consolidated_ad_impression schema](https://github.com/MediaJel/mj-snowplow-management/pull/106) in [MediaJel/mj-snowplow-management](https://github.com/MediaJel/mj-snowplow-management)
* #️⃣ Opened [#1258 Fix Test Tag connectivity issue](https://github.com/MediaJel/amplication-nestjs-microservices/issues/1258) in [MediaJel/amplication-nestjs-microservices](https://github.com/MediaJel/amplication-nestjs-microservices)
* ➡️ Pushed 6 commits in [pacholoamit/xevon-ai](https://github.com/pacholoamit/xevon-ai) on branch `main`
  * [#3cf3704](https://github.com/pacholoamit/xevon-ai/commit/3cf3704) fix: Resolve SSO authentication redirect issues

Fixed SSO callback redirect loop by:
- Excluding SSO callback URLs from middleware auth page redirects
- Correcting Clerk metadata access from metadata to publicMetadata
- Enhanced SSO callback page with proper redirect configuration
- Improved CAPTCHA handling for authentication flow

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude &lt;noreply@anthropic.com&gt;
  * [#8624119](https://github.com/pacholoamit/xevon-ai/commit/8624119) feat: Implement all-in-one development environment with Docker and Ngrok

## One-Command Development Setup
- Add comprehensive `bun run dev` command that starts everything automatically
- Docker Compose orchestration for PostgreSQL, Ngrok, and Redis services
- Automatic database migrations and Prisma client generation
- Smart service health checks and dependency waiting

## Docker Services Integration
- PostgreSQL 16 with custom initialization scripts
- Ngrok tunnel with reserved domain (legible-elf-internal.ngrok-free.app)
- Redis for caching and session storage
- Persistent volumes and proper networking

## Development Scripts Enhancement
- `scripts/dev.sh` - Main development orchestrator with colored output
- `scripts/services.sh` - Docker services management (start/stop/status/logs)
- `scripts/db-reset.sh` - Database reset utility
- All scripts with comprehensive error handling and status reporting

## Package.json Scripts Overhaul
- `dev` - Full development environment (Docker + Next.js)
- `dev:next` - Next.js only (when services already running)
- `services:*` - Complete Docker service management
- `db:*` - Database operations (migrate, reset, studio)
- `typecheck` - TypeScript validation

## Database Migration to PostgreSQL
- Update Prisma schema for PostgreSQL with shadow database
- Docker PostgreSQL with proper credentials and persistence
- Automatic migration application on dev startup
- Database initialization with extensions and functions

## Ngrok Webhook Integration
- Reserved domain configuration with auth token
- Automatic webhook URL discovery and display
- Clerk webhook endpoint exposure for development
- Web interface accessible at localhost:4040

## Developer Experience Improvements
- Comprehensive development documentation (docs/development.md)
- Updated README with quick start guide
- Environment configuration examples (.env.example)
- Service persistence between development sessions

## Architecture Features
- Health checks for all services with automatic waiting
- Proper service dependencies and startup order
- Clean shutdown and cleanup procedures
- Production-ready Docker configuration
- Environment-based configuration management

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude &lt;noreply@anthropic.com&gt;
  * [#edb96f1](https://github.com/pacholoamit/xevon-ai/commit/edb96f1) feat: Implement comprehensive Clerk authentication with onboarding flow

## OAuth Authentication Fixes
- Fix OAuth redirect loop by creating SSO callback page
- Update login page redirect URLs for GitHub/Google OAuth
- Replace mock user data with real Clerk user integration
- Implement functional logout with proper sign-out flow
- Add comprehensive forgot password page with multi-step verification

## Onboarding Flow Implementation
- Add onboarding fields to Prisma User model (onboardingComplete, preferences)
- Implement smart middleware routing based on onboarding status
- Create 4-step progressive onboarding flow:
  * Welcome: role and company information
  * Preferences: timezone and notification settings
  * Connectors: platform selection (Slack, Teams, GitHub, Discord)
  * Completion: summary and final setup
- Build professional UI with animations and progress tracking
- Sync data between Clerk publicMetadata and Prisma database
- Add onboarding completion API endpoint with secure metadata updates
- Create useOnboarding hook for centralized state management

## Technical Improvements
- Update dashboard layout to use real Clerk user data
- Add CAPTCHA elements to resolve Clerk Smart CAPTCHA warnings
- Configure ClerkProvider with proper CAPTCHA appearance
- Comprehensive documentation updates in docs/authentication.md

## Architecture Features
- Metadata-based onboarding tracking using Clerk publicMetadata
- Automatic redirect logic: unauthenticated → login, incomplete onboarding → onboarding, complete → dashboard
- Type-safe implementation with proper error handling
- Professional responsive design consistent with existing auth pages

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude &lt;noreply@anthropic.com&gt;
  * [#3cddd47](https://github.com/pacholoamit/xevon-ai/commit/3cddd47) feat: Update landing page sections to align with Xevon AI platform

- Update FeaturesSection with communication intelligence capabilities
- Replace IntegrationsSection with actual connector logos (Slack, Teams, GitHub, Discord)
- Rewrite ContentSection to focus on streamlining team communication
- Implement tiered pricing with Free/Pro/Max plans based on message consumption
- Add detailed PricingComparator with feature breakdown and &#34;Coming Soon&#34; Max plan
- Fix cursor pointer styling on social login buttons
- Add Clerk Provider layout for auth directory

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude &lt;noreply@anthropic.com&gt;
  * [#4d34f25](https://github.com/pacholoamit/xevon-ai/commit/4d34f25) feat: Implement collapsible sidebar and dashboard improvements

- Add collapsible sidebar with smooth animations and responsive behavior
- Update dashboard layout to balanced 2-column grid for better height matching
- Remove Recent Reports, System Health, and Quick Actions bottom sections
- Move QuickActionsFAB to dashboard layout for global availability
- Replace remote logo URLs with local assets from /public/external/
- Reorganize reports page: move Key Takeaways/Actions below stat cards
- Remove Weekly Intelligence Summary and Most Active Channel sections
- Fix TypeScript types and resolve useEffect infinite render issues
- Add ImageKit hostname to next.config.ts for external image support

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude &lt;noreply@anthropic.com&gt;
  * [#17a8eea](https://github.com/pacholoamit/xevon-ai/commit/17a8eea) feat: Implement collapsible sidebar and dashboard improvements

- Add collapsible sidebar with smooth animations and responsive behavior
- Update dashboard layout to balanced 2-column grid for better height matching
- Remove Recent Reports, System Health, and Quick Actions bottom sections
- Move QuickActionsFAB to dashboard layout for global availability
- Replace remote logo URLs with local assets from /public/external/
- Reorganize reports page: move Key Takeaways/Actions below stat cards
- Remove Weekly Intelligence Summary and Most Active Channel sections
- Fix TypeScript types and resolve useEffect infinite render issues
- Add ImageKit hostname to next.config.ts for external image support

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude &lt;noreply@anthropic.com&gt;
* 🔍 Reviewed [#1218 [FOR REVIEW] Added Coda docs to the Microservices](https://github.com/MediaJel/amplication-nestjs-microservices/pull/1218) in [MediaJel/amplication-nestjs-microservices](https://github.com/MediaJel/amplication-nestjs-microservices)
* #️⃣ Opened [#1257 Make schema fields optional in new vs returning template](https://github.com/MediaJel/amplication-nestjs-microservices/issues/1257) in [MediaJel/amplication-nestjs-microservices](https://github.com/MediaJel/amplication-nestjs-microservices)



### Recent Articles & Youtube tutorials 📚

**[✒️ Recent posts from dev.to](https://dev.to/pacholoamit)**
<table>
  <tr>
    <td rowspan="2" width="280">
      <img src="https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Flge8esnf6tohremh681f.png" alt="" width="280">
    </td>
    <th>
      <a href="https://dev.to/pacholoamit/getting-started-with-typescript-generics-40a">Getting started with Typescript Generics 🚀</a>
    </th>
  </tr>
  <tr>
    <td>
      TypeScript has revolutionized the way developers write and manage JavaScript code, offering type...
      <br>
      <i>Published on 5 May 2024</i>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td rowspan="2" width="280">
      <img src="https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F94xlhw1wcbyjdwfi75le.png" alt="" width="280">
    </td>
    <th>
      <a href="https://dev.to/pacholoamit/use-over-140-amazing-chatgpt-prompts-in-10-minutes-na3">Use over 140+ amazing ChatGPT prompts in 10 minutes 🚀</a>
    </th>
  </tr>
  <tr>
    <td>
      We&#39;re going to be exploring this amazing NodeJS library called chatgpt-prompts. This library allows...
      <br>
      <i>Published on 7 Feb 2023</i>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td rowspan="2" width="280">
      <img src="https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Ftvvesouje29b7h2gw0dm.png" alt="" width="280">
    </td>
    <th>
      <a href="https://dev.to/pacholoamit/is-this-the-end-of-localhost-vs-code-server-preview-36ln">Is this the end of localhost? VS Code Server Preview</a>
    </th>
  </tr>
  <tr>
    <td>
      We&#39;re going to take a look at VS Code Server which is currently in private preview. I&#39;m going to walk...
      <br>
      <i>Published on 6 Sept 2022</i>
    </td>
  </tr>
</table>


### Stalk me here ❤️

<img src="/assets/metrics-1.svg" height="100%" align="left" width="390" alt="Metrics-1" >
<img src="/assets/metrics-2.svg" height="100%" align="right" width="390" alt="Metrics-2">
