# Push Checklist

This folder is prepared as the local source for a public GitHub repository named `pixel-39`.

## Create and push with GitHub CLI

From this directory:

```powershell
cd D:\MY\FUN\v_bubblewell\publish\pixel-39
gh repo create pixel-39 --public --source . --remote origin --push
```

If the repository already exists:

```powershell
cd D:\MY\FUN\v_bubblewell\publish\pixel-39
git remote add origin https://github.com/<your-handle>/pixel-39.git
git push -u origin main
```

After pushing, replace the `TBD` source URL in `SUBMISSION.md`, `ISSUE_SUBMISSION.md`, and `pets/pixel-39--qing/submission.json` with the public repository URL.

Then submit here:
https://github.com/legeling/awesome-codex-pet/issues/new?template=pet-submission.yml
