# RunnerOS Public Web

This is the sanitized public web export for RunnerOS.

RunnerOS is a lightweight run logging and training-notes app for runners, crews, and community run organizers. This export is high-level, dogfood-tested in direction, and influenced by TCO Lab design language without exposing the private RunnerOS app, private runner data, or internal TCO materials.

## Routes

- `/`
- `/runneros`
- `/runneros/support`
- `/runneros/privacy`

## Public Safety

This repo must not include:

- private runner logs
- route files, GPS traces, or location history
- names, emails, invite codes, or tester records
- local SQLite databases
- screenshots containing private data
- internal TCO canon, receipts, prompts, or local paths
- env files, secrets, tokens, analytics, trackers, payments, or private APIs

## Release Lane

RunnerOS follows the ChurchOS release pipeline, but this repo is only the public web lane. The iOS wrapper/TestFlight lane should start after these public routes are reviewed and deployed.

