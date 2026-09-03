# Profile setup

This folder is ready to use as the public GitHub profile repository for `Syreldar`.

## 1. Create the repository

On GitHub, create a **public** repository named exactly:

```text
Syreldar
```

Because your username is also `Syreldar`, GitHub will recognize it as a special profile repository.

Do not initialize it with extra files if you plan to push this folder with Git.

## 2. Push this package

From the extracted `Syreldar` folder:

```bash
git init
git add .
git commit -m "Create GitHub profile README"
git branch -M main
git remote add origin https://github.com/Syreldar/Syreldar.git
git push -u origin main
```

Alternatively, create the repository in GitHub's web interface and upload `README.md` plus the `assets` folder.

## 3. Recommended GitHub profile fields

Suggested bio:

```text
Senior Software Developer · C++ · C# · Java · Python · JavaScript · Lua · SQL · Scientific tooling, automation & game development
```

Suggested location:

```text
Messina, Sicily, Italy
```

Keep your ORCID profile link:

```text
https://orcid.org/0009-0005-1725-5223
```

Consider removing a generic permanent status such as `Working from home` unless it conveys something useful at the time.

## 4. Pins

Once the profile README is live, curate the pinned repositories rather than filling all six slots automatically.

Recommended current first pin:

1. `photo-cat`

For additional pins, prioritize original public projects that demonstrate different strengths: systems/application development, tooling/automation, game systems, or data-heavy software.

## 5. What is deliberately not included

The README does not use animated typing banners, visitor counters, trophy walls, contribution snakes, Spotify widgets, or large stacks of dynamic statistics.

The goal is a restrained professional profile with one strong visual identity and project evidence.

## 6. Editing

- Main profile content: `README.md`
- Banner: `assets/header.svg`

The banner is self-contained SVG, so there is no external image host to maintain.
