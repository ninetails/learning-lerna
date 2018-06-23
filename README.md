# Learning LernaJS

Discovered on https://medium.com/@antonybudianto/managing-packages-with-lernajs-a15aaa786366

Tutorial on https://github.com/reggi/lerna-tutorial

## Also, when using Yarn with Workspaces

### `lerna.json`

```
{
  ...
  "npmClient": "yarn",
  "useWorkspaces": true
}
```

### `package.json`

```
{
  ...
  "workspaces": ["packages/*"]
}
```
