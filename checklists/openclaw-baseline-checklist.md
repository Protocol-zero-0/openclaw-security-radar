# OpenClaw Baseline Checklist

Use this for a quick first-pass review.

## Permissions

- Are exec permissions broader than necessary?
- Are file access paths narrower than full-disk by default?
- Are approval prompts enabled where risk is meaningful?

## Secrets

- Are API keys kept out of prompts, screenshots, and shared logs?
- Are sensitive environment variables clearly separated from general config?
- Are example configs free of real tokens?

## Skills And Plugins

- Are installed skills from known sources?
- Is there at least a quick manual review before installation?
- Are abandoned or unclear projects excluded?

## Channels And Connectors

- Are inbound channels restricted to intended users or groups?
- Are public-facing connectors protected against spam and prompt injection?
- Is there a clear rule for what the agent should never do from channel input alone?

## Visibility

- Can you tell what the agent executed?
- Can you review task history or audit output after something goes wrong?
- Are important actions visible enough to debug later?

## Operating Model

- Is this setup for personal use, team use, or public-facing automation?
- Do the permissions match that operating model?
- If the agent misbehaves, do you know how to stop it quickly?
