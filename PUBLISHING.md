# Publishing Checklist

## Profile Space

Create a public GitHub repository named exactly:

```text
oliviawen92-stack
```

Because the repo name matches the GitHub username, GitHub will display its `README.md` on the profile page.

## Skill Repositories

Publish each skill as its own repository under the same account, for example:

```text
oliviawen92-stack/book-to-feishu-visual-notes
```

Keep generated artifacts, private links, tokens, screenshots, copyrighted book files, and personal notes out of public repos.

## First Publish Commands

After creating the empty GitHub repository in the browser:

```bash
git remote add origin https://github.com/oliviawen92-stack/oliviawen92-stack.git
git push -u origin main
```

If Git asks for identity:

```bash
git config user.name "oliviawen92-stack"
git config user.email "294075627+oliviawen92-stack@users.noreply.github.com"
```
