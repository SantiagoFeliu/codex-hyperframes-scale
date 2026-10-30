# Codex HyperFrames Scale

Linux terminal-only guide to install HyperFrames Skills in Codex.

Includes:

- HyperFrames skills installation
- GSAP
- website-to-hyperframes
- validation
- render workflow
- troubleshooting

Built from real Linux testing and validated commands.

## Scope

This repository documents a **Linux terminal workflow for installing and using HyperFrames-related skills with Codex**. It is an installation and workflow guide, not evidence of a packaged video-generation product or a production render service.

## Verification checklist

1. Confirm the installed Codex version and the Linux environment before following the guide.
2. Verify the skill files are present in the expected local directory.
3. Confirm the documented GSAP and `website-to-hyperframes` dependencies are available.
4. Run the documented validation step before attempting a render.
5. Render a small, non-sensitive sample and inspect the generated artifact directly.
6. Record command versions, input, output location and any error logs.

A successful installation command alone does **not** prove that the rendering workflow works. The checks above are proposed acceptance criteria, not tests performed by this README update.

## Known boundaries

- Exact installation paths and commands can vary by Codex and skill version.
- Rendering may require browser, graphics and FFmpeg dependencies not provided by the skill alone.
- Do not publish API keys, local configuration or private project assets.
- This guide does not claim performance benchmarks or reproducibility on every Linux distribution.

## Portfolio evidence to add

A sanitized command transcript, dependency versions, one sample input, a generated output and a short failure/recovery example would turn this guide into a verifiable case study. Add those artifacts only after running the workflow successfully.
