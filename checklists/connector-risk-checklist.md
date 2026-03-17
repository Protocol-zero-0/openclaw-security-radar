# Connector Risk Checklist

Use this when connecting OpenClaw to external platforms.

## Exposure

- Who can send input into the agent through this connector?
- Is the connector private, team-only, or public-facing?
- Does the platform expose rich content like links, files, or embeds?

## Identity And Access

- Are allowed senders or groups clearly scoped?
- Can impersonation or message spoofing become a problem?
- Are there role boundaries for who can trigger sensitive actions?

## Prompt Injection Surface

- Can user content include links, screenshots, PDFs, or instructions?
- Can the connector pull remote content automatically?
- Is there a clear rule for when human approval is required?

## Secrets And Data

- What tokens does the connector need?
- Where are those tokens stored?
- Could replies leak internal data back into public or semi-public channels?

## Failure Handling

- If the connector loops, spams, or misroutes, how do you stop it?
- Is there a safe fallback mode?
- Are logs sufficient to trace what happened?
