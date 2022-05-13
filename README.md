**To create own custom set of hooks on repository. Directory called "hooks"** - - > mkdir -p hooks

**To configure hooks path to point to this directory(hooks)** - - > git config core.hooksPath hooks

**To Verify the hook configuration run this command** - - > git config -l --local

**create pre-commit file and script to it** - - > vi hooks/pre-commit

**Make the pre--commit file executable** - - > chmod +x ./hooks/pre-commit
