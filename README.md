# Write JavaScript Actions

## Basic Usage

See [action.yml](action.yml).

```yaml
steps:
  - id: joke
    name: My Joke Action
    uses: nviriyadamrongkij/skills-write-javascript-actions@v2

  - run: echo "${{ steps.joke.outputs.joke }}"
```
