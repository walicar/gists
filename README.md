# snippets

## Minimal bash prompt
```sh 
export PS1='%* %1~ %B$%b '
```

## Transcode every .mov
```sh
for vid in *.mov; do ffmpeg -i "$vid" -c:v libx264 -c:a aac -b:v 2M "${i%.*}.mp4"; done
```

## List every .cc file
```sh 
find ./ -name "*.cc"`
```

## Rename every file
```sh
for file in *_*; do mv "$file" "${file//_/-}"; done
```
