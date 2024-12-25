# bash-command
Some useful bash commands

## List out files with specific pattern under current directory
```bash
ls -l ./some*zipped*files[0-9]*.gz
```

## Count files / directories number
```bash
echo ./* | wc
```

## Directory size
```bash
du -hs .
```

## Count file contents (how many lines)
```bash
wc -l filename.txt
```

## Create soft-link
```bash
ln -s /path/to/target /path/of/shortcut

# if want to implement soft-link to an executable
# add `export PATH="$PATH:~/bin"` command to ~/.bashrc file
ln -s /path/to/executable ~/bin/your_path
```