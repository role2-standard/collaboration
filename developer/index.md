[中文](./index.zh.md)

# Role2 Developer Collaboration Standards

```text
scope: All collaboration scenarios related to programming 
```

## Collaboration

**Push whenever you can.**

Not doing so means teammates cannot know or refer to your latest progress, resulting in an information blackbox which affects everyone's anticipation and blocks the process.

What is pushable: as long as it runs without fatal error, it is pushable. It doesn't need to be perfect and bugs can exist. As for which branch to push, please refer to the [Git > Banches](#Branches) section.

### Git

#### Branches

Format: `{master|[feature.FEATURE.]dev[.MODULE]}`

##### Feature branches

- **`master`** - **master branch (production version)**, a thoroughly tested version that contains minimal risks. It can run in the production environment directly and cannot be deleted.
- **`feature.<NAME>`** - **feature branch** that contains independent features, such as holiday themes `feature.new_year`, educational version `feature.edu`. Usually it is based on `master` and used in a combined manner (cannot be deleted).

##### Development branches

- **`dev`** - **dev branch**, the development version of `master`, other child modules in development will be merged into this branch eventually (can be deleted).
- **`dev.<NAME>`** - **the development version of child module** e.g. `dev.payment` (can be deleted).

Prefixes are not required for branches based on `master`. In other words, use `dev` directly instead of `master.dev`. For feature versions, use feature name as prefix, for instance:

- **`feature.edu.dev`** - Educational features development branch
- **`feature.edu.dev.payment`** - Payment modules for educational features development branch

## Naming scheme

### Principle

**Accuracy is paramount**

### Format

**Under any condition**, use `snake_case` as much as possible, and **do not use `camalCase`**, including (but not limited to) directory, filename, variable name, function name, key, repository name, branch name, URL, parameter name, etc.

**Special case**

- Class name: use `Snake_case` and captitalize the first letter, e.g. `Apple`, `This_is_a_class`

## Formatting

An unified coding style is used by the entire team, meaning that characters are exactly aligned. It is not feasible to maintain such style completely by hand, so you can use formatting tools like [prettier](https://github.com/prettier/prettier), which you can read more at [awesome-code-formatters](https://github.com/rishirdua/awesome-code-formatters)
