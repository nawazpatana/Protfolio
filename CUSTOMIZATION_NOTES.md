# Academic Portfolio Structure

This site is configured so that:

- Clicking **Nawazish Hussain** in the sidebar opens `/profile/` and shows the complete CV (`index.md`).
- **Publications** opens `/profile/publications/` (`publications.md`).
- **Academics** opens `/profile/academics/` (`academics.md`).
- **Projects** opens `/profile/projects/` (`projects.md`).
- **Experience** opens `/profile/experience/` (`experience.md`).

## Replace the circular NH monogram with a real photo

1. Add a professional headshot as `assets/img/profile.jpg`.
2. In `_config.yml`, change both `logo` and `author.picture.path` to `/assets/img/profile.jpg`.
3. In `_data/authors.yml`, change the `picture.path` and `srcset` values to `/assets/img/profile.jpg`.

## CV PDF

The downloadable CV is stored at:

`assets/files/Nawazish_Hussain_CV.pdf`
