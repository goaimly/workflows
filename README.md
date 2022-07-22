# workflows

This is a general repository for common workflows used by this org. To use a workflow from here see example:

#### Using tag and release

In another workflows yaml file:

```yaml
jobs:
  call-workflow-passing-data:
    uses: goaimly/workflows/.github/workflows/tag-and-release.yml@main
    with:
      bump: <bump-value>
```

Note: there are other modifications necessary to make this work, this is just an example to call the workflow from another repository.

See [reusing workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for more details.
