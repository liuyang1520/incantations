# Globally Search Replace for Git Files
## Linux
`git grep -l 'original_text' | xargs sed -i 's/original_text/new_text/g'`

## Mac
`git grep -l 'original_text' | xargs sed -i '' -e 's/original_text/new_text/g'`
