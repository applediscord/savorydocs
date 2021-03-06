# v2.3-MSR SavoryBot
## Bug Fixes/Updates
- Update JSONBin API to v3 (#23)
- Add global class for `slashrequest` (#10)
- Merge `hystats` with `commandListener` (#31)
- Cleanup unused environments (#26)
- Slash request won't set permissions if `default_permission` is True (#18)
- Change prefix to `=` (since SavoryApple was having trouble)
- Major organization of the code

## Additions
- Add a profile lookup command with multiple features such as looking up and selecting profiles in the same message, and viewing basic statistics about profiles such as coop members and creation/last seen times with discord's new timestamp system. (#24) (#29)
- Add ability to deny guild applications. (#28)
- Add `/hy` with 4 subcommands (`/hy profiles`, `/hy status`, `/hy counts`, `/hy banstats`).
- Add bot testing commands for owner-only to enable and disable testing commands for users to use.
- Added nested subclasses for `commandListener.hystats` (`util`, and `profiles`).

## Deletions
- My life (#-1)

## Cancelled Issues
Additions planned to be made to the code, but were cancelled.
- Add config flag changer function (#27)
- Built-in discord command for moderators to disable certain commands (may come back at some point) (#25)
- Server support tickets (#20)

## Unfixed issues
- Add namemc/verification update (#11)
- More moderation tools (#32)

## Future plans
- Add cogs (`commandListener.py` and `main.py` are still way too messy)
- More pull requests (maybe for cogs? i'm addicted)
- v2.4 (later today?)
- v3.0 (sometime?)

### Notes:
This is the first time I'm using any formal release formatting, and I didn't document as many of the changes as I would like to have done.
