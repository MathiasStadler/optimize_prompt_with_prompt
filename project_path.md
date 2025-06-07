#

## create util file

```bash
# Check if file exists and create new_prompt.md
if [ ! -f new_prompt.md ]; then
    touch new_prompt.md
else
    echo "File already exists. Creating new_prompt_$(date +%Y%m%d).md instead"
    touch "new_prompt_$(date +%Y%m%d).md"
fi
```
