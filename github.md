# github v3

```bash
$ curl -u 'USER' https://api.github.com/user/repos -d '{"name":"REPO"}'
```

# Remember replace USER with your username and REPO with your repository/application name!

```bash
$ git remote add origin git@github.com:USER/REPO.git
$ git push origin master
```

# repository

## create

```bash
$ curl -F 'login=username' -F 'token=API Token' https://github.com/api/v2/yaml/repos/create -F name=reponame
```


