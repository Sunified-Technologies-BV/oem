# oem.sunified.ai

UNITY OEM briefing kit. Public, external-facing blocks only.

Source of truth is this repo. Edits arrive through the Sunified deploy bridge:

    ~/Sunified Dropbox/.../Sunified/Design/Deploy/oem/index.html   (drop zone)
      -> deploy-watch.sh sync   (hash check, commit, push)
      -> Vercel                 (project sunified-oem)
      -> https://oem.sunified.ai

Internal blocks (qualification, guardrails, cadence, pilot-scale position)
are deliberately NOT in this repo. They live in the local briefing kit at
~/Documents/Claude/Projects/China OEMs/OEM-BRIEFING-KIT.md

See DESIGN-quant-page-deploy-bridge-2026-07-09.md in the Deploy folder.
