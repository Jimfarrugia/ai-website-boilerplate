# AI Website Boilerplate

## How it works

1. Give the agent the website goal, requirements and any constraints.
2. The agent creates or updates `PROJECT.md` with a clear goal and verifiable acceptance criteria.
3. The agent asks only about material ambiguities it cannot resolve itself.
4. Once `PROJECT.md` is sufficiently clear, the agent builds the website autonomously.
5. The agent verifies the acceptance criteria before declaring completion.

## How to use it

1. Clone this repository and delete the `.git` directory. Then run `git init` to take ownership.

2. Install the skills:

```sh
npx skills add anthropics/skills@frontend-design
npx skills add shadcn-ui/ui@shadcn
npx skills add https://github.com/DietrichGebert/ponytail/tree/main/skills
```

3. Open the repository with your agent.

4. Describe the website you want built.

For example:

> Build a website for a residential landscaping company in Sydney.
>
> It should generate qualified enquiries from homeowners looking for premium landscape design and construction.
>
> Include home, services, projects, about and contact pages. It should be responsive, accessible and feel premium.

Include specific requirements, constraints or acceptance criteria when they matter. Otherwise, let the agent derive them and record them in `PROJECT.md`.
