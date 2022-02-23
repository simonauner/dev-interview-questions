# dev-interview-questions

A curated list of highly opiniated questions that could be asked during an interview for a tech position.

## Questions

### 1. Are there any device/OS requirements?

**nudge nudge** Do I need to run Windows?

**Motivation:** Most open source tools are primary written for Linux/Unix/OSX. Having to work with Windows seriously cripples work.

### 2. How is communication handled in the team/company?

If not Slack - what rock are you living under?
I also prefer Teams over Zoom, but that's just details.

**Motivation:** If communication isn't easy and transparent the company is building silos between teams which doesn't foster collaboration and transparency.

### 3. Is git used?

If not - run away!

Github is better than Gitlabs but both are better than Bitbucket.

**Motivation:** Version control is such a basic need for software that if it doesn't work flawlessly the daily work is being crippled.

### 4. IDE? Up to me?

Rider > Visual Studio

**Motivation:** Having a good IDE is without a doubt essential. Being able to choose how I produce code is key.

### 5. How do you run applications in production?

Kubernetes? Docker? AWS Lambda?

**Motivation:** If it's easy to run and deploy applications it's easy to change. Rapid change -> innovation.

### 6. How is infrastructure configured?

Terraform?

**Motivation:** Infrastructure as code means that everything can be traced and replicated.

### 7. How far away from production is `main` branch?

If not continously deployed - why?

**Motivation:** Complicated release cycles, release branches, release trains etc makes it difficult to make changes to what is in production. If it's difficult to make changes in production then people will need to "squeeze in" features before the release train leaves which makes for poor quality and constant stress.

### 8. How do you work with releases?

Are there any release branches? Is `main` in production?

**Motivation:** `main` should always be releasable and reflect production. Patching release branches takes time and gets complicated. Rolling forward on `main` makes life easier.

### 9. Are there any legacy PHP systems we have to maintain?

Are you sure?

**Motivation:** A legacy (PHP :smirk:) system takes time from the team to maintain and shows that the company doesn't take technical debt into (enough) consideration. If there is a legacy system all new functionality should be written in a new system to that the old system can be strangled.

## Contributing

Fork and submit a PR.
