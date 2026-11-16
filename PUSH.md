# Push this to GitHub

Run from the folder that holds `README.md`, `design/` and `screenshots/`.

```bash
git clone https://github.com/krishmjradiusagent/document-templates-pdf-editor-soul.git
cd document-templates-pdf-editor-soul
git checkout -b design/soul-document-templates
cp -R ../soul-document-templates-design/README.md ../soul-document-templates-design/design ../soul-document-templates-design/screenshots .
git add README.md design screenshots
git commit -m "Add SOUL Document Templates design: canvas source + artboard screenshots"
git push -u origin design/soul-document-templates
gh pr create --base main --title "SOUL Document Templates design" --body "Canvas source and 2x screenshots for all 5 pages (46 artboards). See README for the index."
```

No `gh`? Open the compare link GitHub prints after the push and create the pull request there.
