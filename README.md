# calliope-mini
tips and tricks around the calliope mini computer

# links
- https://calliope.cc/en
- https://lab.open-roberta.org/#

# helpers

## copy latest *.hex file to calliope mini available under drive "MINI"

```bash
# open shell terminal e.g. iterm2 on macos
cd ~/Downloads/
file=$(ls -rt | grep ".*.hex" | tail -1); cp -n $file /Volumes/MINI; echo "copied '$file' to calliope"
```

