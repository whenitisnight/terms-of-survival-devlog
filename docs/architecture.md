# System structure

Unreal C++ supplies exploration, movement, interaction and presentation. Authored story and scene data describe dialogue conditions, choices, residents, locations and travel links. A casebook connects discoveries and current leads to saved state.

The new consequence catalog defines five standing tracks: ward trust, civic access, labor credit, corporate favor and security heat. Rules derive scores and explanatory reasons from remembered flags, town state and inventory. Dialogue conditions can query those scores; the casebook presents the resulting standing and its causes. Deriving standing from saved facts avoids a second mutable score ledger that could drift out of sync.

An outcome-commit guard makes authored resolutions mutually exclusive and resists reward replay. Downstream conditions select conversations, resident remarks, casebook consequences and scene props. Permanent-injury flags alter relevant skill values and select compatible character variants. These mechanisms are separate from a claim of fully polished sensory or visual simulation.

Scene resources include painted environments, characters, audio, editable source art and authoring scripts. Packaging retains referenced aftermath art while filtering obsolete revisions from generated archives. Source assets remain in the private repository with Git LFS; player saves, caches and generated executables stay outside it.

The architecture is intended to make existing locations react consistently and support future content without restarting the project. The number of data entries does not establish a coherent finished story, distinct playtime or complete acceptance.
