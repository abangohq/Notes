Setup Digitalocean server

Create project folder

Add remote origin like this 
```bash
git remote add origin https://{username}:{password}@github.com/{username}/project.git
```
If you get "fatal: remote origin already exists." then you have to use set-url:
```bash
git remote set-url origin https://{username}:{password}@github.com/{username}/project.git
```
