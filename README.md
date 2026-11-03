# Kunle Watchlist Sync

A personal, single-user integration built and used only by Richard Bankole (Trakt: @rickoslyder).

## What it does

- Syncs my own movie watchlist between a local file and my own Trakt account.
- Reads my own Trakt watch history so my personal assistant can keep a local viewing diary in step.
- Non-commercial, no other users, light API use (a few sync calls per day at most).

## How it works

- OAuth 2.0 authorization code flow with PKCE against the Trakt API. The app has no Client Secret.
- Access tokens are held in a secure credential vault, never in this repository or in any distributed app.
- The Trakt app is named "Kunle Watchlist Sync" on Trakt's developer portal.

## Privacy

See PRIVACY.md in this repository.
