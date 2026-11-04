# Draft

**Public incubator for functional, unadvertised web-app experiments.** This is a place to try live concepts before deciding whether they deserve their own named repositories. A prototype may be experimental, unfinished or unpublished elsewhere, but its source here is **public**. “Unadvertised” does not mean private or inaccessible.

## Working model

- Place each actual experiment under `apps/<short-name>/`, with its own publishable code, required assets and minimal usage notes when useful. Do not create empty experiment folders or a mandatory site/app framework.
- Prefer self-contained static or browser-runnable prototypes first. Use relative asset paths so a tool can work under a repository subpath. Any dynamic backend or external service requires a separately reviewed hosting/security arrangement.
- Do not commit credentials, private configuration, backend secrets, restricted datasets, internal briefs or reports, agent locks or private operational instructions. Public code, tests, safe sample data, and publishable documentation belong here.
- An experiment can be linked directly without adding it to a public catalog; GitHub and any hosted app remain publicly discoverable. Do not promise secrecy or unlisted access.

## Graduation

When an experiment warrants sustained independent maintenance, select a new dedicated repository with its own name, permissions and release process. Transfer only reviewed publishable source and assets, retaining provenance. A project-specific private companion can receive authorized internal notes when needed. Graduating does not automatically delete the prototype here, rewrite its Git history, or preserve/redirect a public URL; decide those matters deliberately.

**Hosting is not configured or verified by repository initialization.** Enabling GitHub Pages or another publisher, deploying experiments, making them discoverable on a home page, and changing release settings require an explicit decision for that task. No web application has been added yet.
