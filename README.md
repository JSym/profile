# Notes and instructions

Navigate to directory:

```
cd projects/profile~~~
```
Start Jekyll server locally:
```
bundle exec jekyll serve
```
View site locally:

```
http://127.0.0.1:4000
```

Go to admin page:

```
http://127.0.0.1:4000/admin/
```

Make changes as required. Note: changes to config (`http://127.0.0.1:4000/admin/configuration`) require server restart (CTRL+C > `bundle exec jekyll serve`)

Stage & commit changes to git:
```
git add .
git commit -m "commit message"
```

Push to github:
```
git push origin
```
Enter username & Personal Access Token (not password)

Workflow will trigger & site update