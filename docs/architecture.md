# System structure

Unreal C++ provides native exploration, movement, interaction and presentation. Authored story and scene data describe residents, dialogue conditions, choices, locations and travel links. A casebook ties discoveries and current leads to the player's saved state.

Scene resources include painted environments, characters, source art, audio and authoring scripts. Navigation distinguishes walking connections from return travel and revalidates access conditions. The project keeps editable assets alongside its source, using Git LFS for binary assets and excluding generated engine caches and player saves.

The architecture is intended to let improvements to interaction, choice feedback and navigation benefit existing locations. The presence of many data entries does not by itself establish a coherent player experience, a large finished city or complete story coverage.
