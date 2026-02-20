# lastclone-test-default

This is an integration test repository for lastclone.

## Expected behavior

When this repository is backed up by lastclone, the branch used for the backup should be `main`. There is another branch named `prod` that should not be backed up.

The branch `main` contains a file `TEST.md` which indicates `TEST PASSED`.
The branch `prod` contains a file `TEST.md` which indicates `TEST FAILED`.

