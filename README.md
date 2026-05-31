# ANN Exam Study Notes

Static HTML study notes for the Artificial Neural Networks exam.

## Pages in this site

- `index.html`: Homepage for GitHub Pages
- `unit3_associative_learning.html`: Unit III notes
- `unit4_competitive_learning_notes.html`: Unit IV notes
- `unit5_cnn_notes.html`: Unit V notes
- `unit6_ann_applications.html`: Unit VI notes

## Publish to GitHub Pages

1. Create a new GitHub repository.
2. Upload or push all files from this folder to the repository.
3. Open the repository on GitHub.
4. Go to `Settings` -> `Pages`.
5. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Click `Save`.

GitHub will show the public website URL after the Pages deployment finishes. It is usually:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Git commands

If this folder is not already a Git repository, run:

```bash
git init
git add .
git commit -m "Add ANN study notes site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY-NAME` with your actual GitHub username and repository name.
