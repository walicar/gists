# snippets

## Minimal bash prompt
```sh 
export PS1='%1~ $ '
```

## Transcode every .mov
```sh
for vid in *.mov; do ffmpeg -i "$vid" -c:v libx264 -c:a aac -b:v 2M "${i%.*}.mp4"; done
```

## List every .cc file
```sh 
find ./ -name "*.cc"`
```
