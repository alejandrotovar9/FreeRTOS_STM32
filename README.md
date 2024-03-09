To add existing STM32CubeIDE to a repository:

On parent folder (directory containing projects):
```
git init
git add :/
git commit -m "commit message" -a
git remote add origin https://github.com/username/repo.git
git push -f origin main
```
If not forced the push won't worked, files already in the repo will be deleted when forcing the push, use with caution
