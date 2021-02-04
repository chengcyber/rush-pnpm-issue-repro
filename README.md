Run

```
rush update
```

Result:

```
Rush Multi-Project Build Tool 5.36.2 - https://rushjs.io
Node.js version is 14.15.4 (LTS)


Starting "rush update"

Validating package manager shrinkwrap file.

Trying to acquire lock for pnpm-5.16.0
Acquired lock for pnpm-5.16.0
Found pnpm version 5.16.0 in /Users/admin/.rush/node-v14.15.4/pnpm-5.16.0

Symlinking "/Users/admin/workspace/playground/rush-pnpm-repro/common/temp/pnpm-local"
  --> "/Users/admin/.rush/node-v14.15.4/pnpm-5.16.0"
Copying /Users/admin/workspace/playground/rush-pnpm-repro/common/config/rush/.npmrc --> /Users/admin/workspace/playground/rush-pnpm-repro/common/temp/.npmrc
Updating /Users/admin/workspace/playground/rush-pnpm-repro/common/temp/pnpmfile.js

Updating temp projects in /Users/admin/workspace/playground/rush-pnpm-repro/common/temp/projects
Finished creating temporary modules (0.03 seconds)

Checking node_modules in /Users/admin/workspace/playground/rush-pnpm-repro/common/temp

Linking projects together...

LINKING: my-cli

ERROR: Internal Error: Unable to find dependency ts-node with version /ts-node/8.10.2 in shrinkwrap.
You have encountered a software defect. Please consider reporting the issue to the maintainers of this application.
```
