To push to two different repositories, you can set multiple remotes in your Git configuration. Here’s how you do it:

1. **Add the first remote** (if not already added):
   ```
   git remote add origin <repository-url-1>
   ```

2. **Add the second remote**:
   ```
   git remote add second <repository-url-2>
   ```

3. **Push to the first repository**:
   ```
   git push origin <branch-name>
   ```

4. **Push to the second repository**:
   ```
   git push second <branch-name>
   ```

You can replace `<repository-url-1>`, `<repository-url-2>`, and `<branch-name>` with your actual repository URLs and branch name. Make sure to double-check your commands and the URLs before executing.



------------------------------------------------

git remote add bukv2 git@github.com:abdulsalamamtech/buk-v2.git
git push bukv2 main

git remote -v
bukv2   git@github.com:abdulsalamamtech/buk-v2.git (fetch)
bukv2   git@github.com:abdulsalamamtech/buk-v2.git (push)
origin  git@github.com:abdulsalamamtech/buk.git (fetch)
origin  git@github.com:abdulsalamamtech/buk.git (push)