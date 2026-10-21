# Emacs Quest

A browser-based learning game for core default GNU Emacs keybindings, generated with AI assistance using OpenAI ChatGPT/Codex.

## Play

Once GitHub Pages is enabled, the expected address is:

https://parsa-alemi.github.io/emacs-quest/

This address is not a deployment confirmation. Check **Settings → Pages → Visit site** for the published URL.

## Features

- 61 core shortcut challenges in eight chapters.
- 11 cursor-navigation puzzles in a simulated text buffer.
- XP, hints, and a weak-key review mode that prioritizes missed commands.
- Searchable keybinding field guide.
- Progress stored locally in your browser when local storage is available.
- Escape-prefix support for Meta and a notation fallback for blocked shortcuts.

Start with **Cursor expedition**, then try **Command quest**. Practice the same commands in real Emacs to reinforce them.

## Publish with GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then click **Save**.
4. Wait for the Pages deployment to finish and use **Visit site**.

No dependencies, build step, or custom domain are required. Changes committed to `main` are published automatically after Pages is configured.

## Run locally

Open `index.html` in your browser, or run this in the repository directory:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000. Press Tab to leave the keyboard practice area.

## Limitations

This is a shortcut trainer, not an Emacs implementation. Command quests check key sequences; they do not execute Emacs commands. The cursor expedition simulates a subset of navigation on simple text. It does not cover every mode, package, custom keymap, or Evil/Doom binding.

Browsers and operating systems may intercept shortcuts such as Control+x or Control+Space. Use the typed-notation fallback when necessary; practice in real Emacs for full keyboard fidelity. On macOS, Control means Control, not Command. Meta can be Alt/Option or Escape followed by the next key.

Clearing browser storage removes progress. Progress does not sync across devices. The app has no analytics or application backend; hosting-provider infrastructure is separate.

## Further learning

- [GNU Emacs](https://www.gnu.org/software/emacs/) — open its built-in tutorial with `C-h t`.
- [Key Quiz](https://github.com/federicotdn/key-quiz) — practice bindings inside real Emacs.
- [Org Dungeon](https://github.com/chainsawriot/orgdungeon) — an adventure for learning Emacs concepts.
- [KeyCombiner](https://keycombiner.com/emacs/) — additional shortcut practice.

These are learning resources, not dependencies or endorsements.

## AI disclosure and disclaimer

This project was generated with AI assistance using OpenAI ChatGPT/Codex and is shared for learning and experimentation.

It is an unofficial Emacs practice tool and is not affiliated with or endorsed by GNU Emacs or the Free Software Foundation. It may contain bugs, inaccuracies, or incomplete simulations of Emacs behavior.

The software is provided “as is,” without warranties of any kind. Use it at your own risk. To the extent permitted by applicable law, the maintainer and contributors disclaim liability for losses or damages arising from its use.
