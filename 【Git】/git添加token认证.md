生成 token：
settings->developer settings ->personal access tokens-generate new token

记住 token 值

git 上添加 token
git remote -v 查看 remote 分支

https://github.com/yorkiiz/yorkiiz.github.io.git
将 remote 分支改成

https://oauth2:token 值@github.com/yorkiiz/yorkiiz.github.io.git
比如

https://oauth2:123456@github.com/yorkiiz/yorkiiz.github.io.git
git remote rm origin

git remote add origin https://oauth2:123456@github.com/yorkiiz/yorkiiz.github.io.git
