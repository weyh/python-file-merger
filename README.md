# python-file-merger

I've started this project because one of the autotesters at uni
doesn't allow to submit multiple files and I like not writing
everything in a single file.

## Usage

```bash
$> python3 pyfm.py [-h] [-o OUTPUT] files [files ...]
```

## Known limitations

- Does not check for name collisions
- Files are not ordered automaticly
- Check for multiple imports is not the most *sophisticated*
