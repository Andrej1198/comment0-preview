# Perfherder Comment 0 preview

A static page that compares the old and the new Comment 0 of Perfherder regression bugs, for 12 real alerts. Each alert shows the old format on the left and the new format on the right, made to look like Bugzilla bug pages.

- Open `index.html` to see the page. It works from the file system and from GitHub Pages.
- Bugzilla's own Markdown renderer (`/rest/bug/comment/render`) formatted the comments.
- The new format comes from the `Bug2044755_comment0_improvements` Treeherder branch, with live data from Treeherder.
- `attachments/` has the JSON files that the new format attaches to each bug for agents and tools.

None of these pages is a real bug.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open **Pages**.
3. Set the source to the `main` branch and the `/ (root)` folder.
