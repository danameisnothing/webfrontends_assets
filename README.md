All media files in this repository is tracked via Git LFS

```
git lfs track "*.png,*.jpg,*.jpeg,*.jxl,*.webp,*.avif,*.webm"
```
```
git lfs migrate import --include="*.png,*.jpg,*.jpeg,*.jxl,*.webp,*.avif,*.webm" --everything
```

To pull LFS files from a clean repo :
```
git lfs fetch --all origin
```

migrating out of LFS :
```
git lfs untrack "*.png,*.jpg,*.jpeg,*.jxl,*.webp,*.avif,*.webm"
git lfs migrate export --include="*.png,*.jpg,*.jpeg,*.jxl,*.webp,*.avif,*.webm" --everything
```