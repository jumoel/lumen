> **Warning**: Work in progress. See the [project board](https://github.com/users/colebemis/projects/3).

# Lumen

A system for thinking, writing, learning, and mindfulness. Based on the [Zettelkasten Method](https://zettelkasten.de/introduction/).

🌐 [uselumen.com](https://uselumen.com)

[![Netlify Status](https://api.netlify.com/api/v1/badges/9e55f1c2-783d-4abb-9fa2-edc59f8aa0c3/deploy-status)](https://app.netlify.com/sites/lumen-notes/deploys)

## Syntax

Lumen supports [GitHub Flavored Markdown](https://github.github.com/gfm/) with the following syntax extensions:

### Note links

Link to another note using its ID.

```
[[<note-id>|<link-text>]]
```

| Example                           | Rendered HTML                               |
| :-------------------------------- | :------------------------------------------ |
| `[[1652342106359\|Randie Bemis]]` | `<a href="/1652342106359">Randie Bemis</a>` |

### Date links

Link to all other notes that reference the same date.

```
[[YYYY-MM-DD]]
```

| Example          | Rendered HTML                                       |
| :--------------- | :-------------------------------------------------- |
| `[[2021-07-11]]` | `<a href="/dates/2021-07-11">Sun, Jul 11, 2021</a>` |

### Tag links

Link to all other notes with the same tag.

```
#<tag-name>
```

| Example   | Rendered HTML                        |
| :-------- | :----------------------------------- |
| `#recipe` | `<a href="/tags/recipe">#recipe</a>` |

## Keyboard shortcuts

| Action                 | Shortcut                  |
| ---------------------- | ------------------------- |
| Toggle command menu    | <kbd>⌘</kbd> <kbd>K</kbd> |
| Toggle new note dialog | <kbd>⌘</kbd> <kbd>I</kbd> |

**With focus inside the new note dialog...**

| Action       | Shortcut                      |
| ------------ | ----------------------------- |
| Create note  | <kbd>⌘</kbd> <kbd>Enter</kbd> |
| Close dialog | <kbd>Esc</kbd>                |

**With focus inside a panel...**

| Action             | Shortcut                  |
| ------------------ | ------------------------- |
| Focus search input | <kbd>⌘</kbd> <kbd>F</kbd> |
| Close panel        | <kbd>⌘</kbd> <kbd>X</kbd> |

**With focus inside a note card...**

| Action                | Shortcut                               |
| --------------------- | -------------------------------------- |
| Open note action menu | <kbd>⌘</kbd> <kbd>.</kbd>              |
| Edit note             | <kbd>E</kbd>                           |
| Copy note markdown    | <kbd>⌘</kbd> <kbd>C</kbd>              |
| Copy note ID          | <kbd>⌘</kbd> <kbd>⇧</kbd> <kbd>C</kbd> |
| Delete note           | <kbd>⌘</kbd> <kbd>⌫</kbd>              |
