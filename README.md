# Add a new git repository

- Create the `.git/` folder

```
git init
```
- Assign the `USER_NAME` to this repository

```
git config user.name "<USER_NAME>"
```

- Assign the `USER_EMAIL` to this repository

```
git config user.email <USER_EMAIL>
```

- Select the `main` branch

```
git branch -M main
```

- Assign the remote `REPOSITORY`

```
git remote add origin https://github.com/<USER_NAME>/<REPOSITORY>.git
```

- Make commit

- Push

```
git push -u origin main
```
