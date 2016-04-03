# test-project

Empty project to test team workflow on GitHub

1. Repository created by clazaro (origin)

2. Cloned to clazaro's local machine
   ```
   cd [path-to-GitHub-on-local-machine]
   git clone https://github.com/PuentesUPV/test-project.git
   cd test-project
   ```

   Link to origin repository can be checked with
   ```
   git remote -v
   ```

3. Branch named 'readme-modify' created on local machine
   ```
   git checkout -b readme-modify
   ```

   Branches can be checked with
   ```
   git branch
   ```

   Asterisk shows the active branch


4. README.md modified from a text editor and saved


5. README.md modification added for version control and committed
   ```
   git add .
   git commit -m 'readme-v1'
   ```

   This syntax adds all new or modified files to version control

6. Push the new branch to origin
   ```
   git push origin readme-modify
   ```
