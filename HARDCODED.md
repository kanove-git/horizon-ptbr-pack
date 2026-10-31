# Textos fixos no código (não traduzíveis por pacote)

Estes textos do Horizon aparecem na tela mas não passam por `lang::get`, então só podem ser traduzidos mudando o código do jogo (upstream).

| Texto | Onde |
|---|---|
| Agent Control | `crates/horizon-client-render/src/extras.rs:427 (AI Agent page button, options_ui.rs:1473)` |
| Applying resources | `crates/horizon-client/src/game/packs.rs:406 (RELOAD_LINES pack reload overlay line)` |
| Auto-reconnect | `crates/horizon-client-render/src/extras.rs:421 (Extras page button, options_ui.rs:1705)` |
| Backup worker stopped | `crates/horizon-client/src/title.rs:931 (second line of the Backup failed toast)` |
| Can't be read: {e} | `crates/horizon-client/src/game/mods.rs:179 (mod problem text shown in the Mods list tooltip, Text::literal)` |
| Cancelling world | `crates/horizon-client/src/game.rs:13303 (world loading screen line, Text::literal in draw_progress)` |
| Cannot back up symbolic link: {} | `crates/horizon-client/src/title/world_management.rs:164 (Backup failed toast)` |
| Connected straight to your friend... | `crates/horizon-client/src/net.rs:361 (connect-screen status)` |
| Connected to your friend through the relay... | `crates/horizon-client/src/net.rs:363 (connect-screen status)` |
| Connecting to the server... | `crates/horizon-client/src/game/remote.rs:702 (initial connect-screen status; also crates/horizon-client/src/net.rs:454). Vanilla key connect.connecting exists` |
| Could not read level.dat | `crates/horizon-client/src/title/world_management.rs:28 (error screen after rename)` |
| Disconnected | `crates/horizon-client/src/net.rs:703 and 768 (disconnect reason when the writer is gone; also 681)` |
| Discord Rich Presence | `crates/horizon-client-render/src/extras.rs:428 (Horizon Settings page button, options_ui.rs:1473)` |
| Down sends one item of the slot to the other side, up brings one back. | `crates/horizon-client-render/src/extras.rs:460 (tooltip, options_ui.rs:2654)` |
| Dynamic lights | `crates/horizon-client-render/src/extras.rs:419 (Extras page button, options_ui.rs:1705)` |
| Finding your friend's world... | `crates/horizon-client/src/net.rs:349 (connect-screen status when joining a friend)` |
| Fullbright | `crates/horizon-client-render/src/extras.rs:418 (Extras page button caption, drawn as Text::literal at options_ui.rs:1705)` |
| Happy new year! | `crates/horizon-client/src/title.rs:577 (title splash on Jan 1)` |
| Hides and turns off every AI feature: agent control, horizon-ctl and the MCP servers. The launcher's switch too. | `crates/horizon-client-render/src/extras.rs:469 (tooltip, options_ui.rs:2654)` |
| Horizon {} (Rust) | `crates/horizon-client/src/title.rs:1892 (title screen version label, bottom-left; {} = vanilla version)` |
| Installed, not built into this game: build the game with it in the launcher (Settings > Native mods), then play the instance that build is in. | `crates/horizon-client-render/src/mod_list.rs:19 (NOT_BUILT, set at horizon-client/src/game/mods.rs:144, shown as Mods list tooltip via options_ui.rs:2704-2710, Text::literal)` |
| Internal Exception: {e} | `crates/horizon-client/src/net.rs:421 (argument of disconnect.genericReason, which is "%s", so the English prefix stays on screen)` |
| Invalid server address: {address} | `crates/horizon-client/src/net.rs:452 (disconnect reason)` |
| Invalid world folder | `crates/horizon-client/src/title/world_management.rs:17 (shown in the 'Failed to access world' error screen / backup toast)` |
| Joining world... | `crates/horizon-client/src/net.rs:558 (connect-screen status). Vanilla key connect.joining exists` |
| Loading assets | `crates/horizon-client/src/game.rs:16453 (STAGE_LINES loading progress line)` |
| Loading assets | `crates/horizon-client/src/game/packs.rs:404 (RELOAD_LINES pack reload overlay line)` |
| Loading biomes | `crates/horizon-client/src/game.rs:16455 (STAGE_LINES loading progress line)` |
| Loading block facts | `crates/horizon-client/src/game.rs:16454 (STAGE_LINES loading progress line)` |
| Loading collision | `crates/horizon-client/src/game.rs:16457 (STAGE_LINES loading progress line)` |
| Loading items | `crates/horizon-client/src/game.rs:16458 (STAGE_LINES loading progress line)` |
| Loading menu | `crates/horizon-client/src/game.rs:16452 (STAGE_LINES, startup/world loading progress line drawn by level_loading::draw_progress as Text::literal; also used by startup_menu.rs:769/811 via Progress::new)` |
| Loading pack tables | `crates/horizon-client/src/game.rs:16456 (STAGE_LINES loading progress line)` |
| Loading pack tables | `crates/horizon-client/src/game/packs.rs:405 (RELOAD_LINES pack reload overlay line)` |
| Loading recipes | `crates/horizon-client/src/game.rs:16459 (STAGE_LINES loading progress line)` |
| Loading world resources | `crates/horizon-client/src/game.rs:16460 (STAGE_LINES loading progress line)` |
| Merry X-mas! | `crates/horizon-client/src/title.rs:576 (title splash on Dec 24; vanilla hard-codes it too)` |
| Missing level data | `crates/horizon-client/src/title/world_management.rs:30 (error screen after rename)` |
| Mouse Tweaks controls | `crates/horizon-client-render/src/extras.rs:422 (Extras page button, options_ui.rs:1705)` |
| No AI | `crates/horizon-client-render/src/extras.rs:426 (Horizon Settings page button, options_ui.rs:1473)` |
| Not affiliated with Mojang or Microsoft | `crates/horizon-client/src/title.rs:1899 (title screen bottom-right credits link)` |
| OOoooOOOoooo! Spooky! | `crates/horizon-client/src/title.rs:578 (title splash on Oct 31)` |
| Off | `crates/horizon-client-render/src/extras.rs:513 (value in Extras/Horizon Settings/AI Agent buttons 'Caption: Off', options_ui.rs:1473,1705)` |
| On | `crates/horizon-client-render/src/extras.rs:512 (value in Extras/Horizon Settings/AI Agent buttons 'Caption: On', options_ui.rs:1473,1705)` |
| Opening world | `crates/horizon-client/src/game.rs:13305 (world loading screen line, via level_loading::draw_progress which wraps it in Text::literal)` |
| Own name tag | `crates/horizon-client-render/src/extras.rs:420 (Extras page button, options_ui.rs:1705)` |
| Preparing resources | `crates/horizon-client/src/game/packs.rs:403 (RELOAD_LINES, resource-pack reload overlay line drawn by level_loading::draw_loading_overlay as Text::literal)` |
| Protocol error: {err} | `crates/horizon-client/src/net.rs:505 (disconnect reason during login encryption)` |
| Rejoins a server after a lost connection or a restart, never after a kick or ban. | `crates/horizon-client-render/src/extras.rs:454 (tooltip, options_ui.rs:2654)` |
| Resources are incomplete: registries.json is missing or invalid. Click "Prepare again" in the launcher (or run horizon-prepare), then try again. | `crates/horizon-client/src/game/remote.rs:573 (join error shown on the title/multiplayer screen through title.failed)` |
| Right-drag places one per slot, left-drag gathers the held item, Shift + left-drag moves every slot. | `crates/horizon-client-render/src/extras.rs:457 (tooltip, options_ui.rs:2654)` |
| Saved the game | `crates/horizon-client/src/game.rs:13177 (save_game_with: overlay/action-bar message set directly, no lang lookup; vanilla has commands.save.success = "Saved the game" that could be used)` |
| Scroll wheel moves items | `crates/horizon-client-render/src/extras.rs:423 (Extras page button, options_ui.rs:1705)` |
| Shortcut:  | `crates/horizon-client-render/src/graphics_ui.rs:480 (Graphics: HDR, key button caption)` |
| Shortcut: >  | `crates/horizon-client-render/src/graphics_ui.rs:875 (Graphics: HDR, key button while waiting for a key)` |
| Show blocks and entities at full light, even in dark areas. | `crates/horizon-client-render/src/extras.rs:446 (hover tooltip, Text::literal at options_ui.rs:2654)` |
| Shows Playing Horizon on your Discord profile while Discord runs: menus, single player or multiplayer, the dimension and the time played. Never a world's name or a server's address. | `crates/horizon-client-render/src/extras.rs:472 (tooltip, options_ui.rs:2654)` |
| Shows your name above your head in third person, as other players see it. Hidden when the server hides your team's names or you're invisible. | `crates/horizon-client-render/src/extras.rs:451 (tooltip, options_ui.rs:2654)` |
| Sort buttons | `crates/horizon-client-render/src/extras.rs:424 (Extras page button, options_ui.rs:1705)` |
| Sort key | `crates/horizon-client-render/src/extras.rs:425 (Extras page button, options_ui.rs:1705)` |
| Sorts the inventory, chests, barrels, ender chests and shulker boxes in creative tab order, merging stacks. | `crates/horizon-client-render/src/extras.rs:463 (tooltip, options_ui.rs:2654)` |
| Sorts the part under the cursor. Click, then press a key; Escape unbinds it. | `crates/horizon-client-render/src/extras.rs:466 (tooltip, options_ui.rs:2654)` |
| This server is in online mode. Sign in with your Microsoft account in the Horizon launcher to join it. | `crates/horizon-client/src/net.rs:375 (NOT_SIGNED_IN, shown as the disconnect reason)` |
| Torches and other light sources held, dropped or on fire light the blocks around them. | `crates/horizon-client-render/src/extras.rs:448 (tooltip, options_ui.rs:2654)` |
| World folder is not a directory | `crates/horizon-client/src/title/world_management.rs:21 (error screen / backup toast)` |
| World resources ready | `crates/horizon-client/src/game.rs:16461 (STAGE_LINES loading progress line)` |
| Your own AI agent can play this game through horizon-ctl or an MCP client, on this computer only. | `crates/horizon-client-render/src/extras.rs:475 (tooltip, options_ui.rs:2654)` |
| [native mod description] (mod-supplied) | `crates/horizon-client/src/game/native_hooks.rs:2329 -> horizon-client-render/src/options_ui.rs:2702-2710 (Mods list tooltip, Text::literal). NOT translated` |
| [native mod key labels, e.g. 'Zoom key'] (mod-supplied, NativeMod.keys[1]) | `crates/horizon-client/src/game/native_hooks.rs:467 -> horizon-client-render/src/options_ui.rs:1682 (Text::literal). NOT translated; the key's value uses keybinds::display_name (vanilla keys)` |
| [native mod settings button labels] (mod-supplied via native_settings) | `crates/horizon-client/src/game/native_hooks.rs:788/2321/2352 -> horizon-client-render/src/options_ui.rs:1686-1693 (Text::literal). NOT translated by Horizon; refreshed on each page open so a mod could localize them itself by calling lang::get` |
| [native mod title, e.g. 'Name 1.0'] (mod-supplied) | `crates/horizon-client/src/game/native_hooks.rs:2328 -> horizon-client-render/src/options_ui.rs:1668 (Row::Note, drawn as Text::literal at :2508), :1989 (Mods list row label) and :2709 (tooltip). NOT translated: no lang lookup, shown exactly as the mod pushes it` |
| could not start the pack reload: {e} | `crates/horizon-client/src/game/packs.rs:156 (passed to selection_reload_failed, stored in ui.options.resource_error and shown on the Packs page; borderline error text)` |
| {} IS YOU | `crates/horizon-client/src/title.rs:615 (title splash with the player's name)` |
| {} is not available yet | `crates/horizon-client/src/game.rs:4597-4600 (action-bar message when using a block whose menu is not implemented; {} = block id without minecraft: and with _ as spaces)` |
