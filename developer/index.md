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

- **`master`** - **master version (production version)**, a thoroughly tested version that contains minimal risks. It can run in the production environment directly and cannot be deleted.
- **`feature.<NAME>`** - **feature version** that contains independent features, such as holiday themes `feature.new_year`, educational version `feature.edu`. Usually it is based on `master` and used in a combined manner (cannot be deleted).
