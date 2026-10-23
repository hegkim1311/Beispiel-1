# Beispiel-1: Branch erstellen und mergen

## Verwendete Befehle

```bash
git switch -c feature-text
git add README.md
git commit -m "Text ergänzt"
git switch main
git merge feature-text
```

## Beobachtung

Ich habe einen Branch `feature-text` erstellt und dort Änderungen an der Datei README.md vorgenommen. Nach dem Commit wurden die Änderungen durch einen Merge in den Branch `main`übernommen. ```

