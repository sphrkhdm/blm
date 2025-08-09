# Data Directory

This directory is intended for dataset files.

To upload data, copy or download files into this folder. For example, you can:

- Use the file upload feature of your environment.
- Run `curl -o data/<filename> <url>` or `wget -P data <url>` to download from the internet.
- Use `scp` to copy files from your local machine: `scp <local_path> user@host:/workspace/blm/data/`.

If you want the data tracked in git, run:

```
git add data/<filename>
git commit -m "Add <filename>"
```
