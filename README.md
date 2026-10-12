# Battlefield 1943 native reconstruction research

Based on the PlayStation 3 release: NPUB30077 version 01.00. This is a PS3-to-native-PC reconstruction project.

An experimental effort to understand Battlefield 1943 and build a native PC port, with offline matches and eventually bots and editable gameplay systems.

Current status: a native Windows build reaches menus, map loading, class selection, and in one diagnostic the beach tutorial's LOOK UP instruction. Controllable gameplay is unconfirmed. World and weapon rendering remain missing; startup is inconsistent. This is not a playable release or original-source recovery.

## Progress

The GitHub Pages site is generated from the project's evidence-based progress snapshot in docs/. It tracks milestones, known functions and remaining questions. Decompilation counts are analysis coverage, not a percentage of a finished game.

The main executable has a reference decompilation. Reconstruction begins with the local-session event dispatcher, UI command dispatch, player spawning and camera input. Names in the map are provisional analyst descriptions.

## Help wanted

- Explain original local-session transitions and their data structures.
- Identify the player/camera input consumer and validate its behavior.
- Trace submitted, uploaded, recorded and presented world draws.
- Investigate offline match rules and whether usable AI exists.
- Review evidence and document reproducible findings.

This initial repository contains progress metadata and original project documentation only. It does not distribute game executables, assets, keys, or extracted/decompiled game bodies. Contributors should describe findings with addresses, observations and independently authored explanations.

The project is independent and is not affiliated with EA or DICE. No release date is established.

