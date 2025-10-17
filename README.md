# Team Git Projekt

## Utvecklings-konventioner

### Branch-konventioner
- `main` - Produktionsklar kod, skyddad med PR-krav
- `dev` - Utvecklingsbranch för integration  
- `feature/<namn>-<beskrivning>` - Individuella features

### Pull Request Process
1. Alla PRs ska gå mot `dev`, aldrig direkt till `main`
2. Ta bort feature-branch efter merge

## Faktisk Git Log Visualisering

```
*   1fb19ef (HEAD -> main, origin/main) Merge pull request #2 from moodyambr/dev
|\  
| * 14eac44 Merge pull request #1 from moodyambr/feature/Moodys-section
|/| 
| * 9b765fa Implementerat navbar, hero och footer sectioner
|/  
* 89815ce Initial commit
```

## Implementerade Features
- ✅ navbar 
- ✅ Hero-sektion
- ✅ Footer 
