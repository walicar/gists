# snippets

Minimal bash prompt: `export PS1='%1~ $ '`

Transcode every .mov: `for vid in *.mov; do ffmpeg -i "$vid" -c:v libx264 -c:a aac -b:v 2M "${i%.*}.mp4"; done`

List every .cc file: `find ./ -name "*.cc"`
