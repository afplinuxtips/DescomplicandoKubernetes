# Descomplicando o Kubernetes

## Creating directory and repository

### Local directory

- Created local directory:

```shell
mkdir -p ~/projects/linux-tips/kubernetes
cd ~/projects/linux-tips/kubernetes
```

### Github repository

- Logged in Github
- Created [afplinuxtips] (https://github.com/afplinuxtips) organization
- Created [DescomplicandoKubernetes] (https://github.com/afplinuxtips/DescomplicandoKubernetes) repository
- Configured git:

```shell
echo "# DescomplicandoKubernetes" >> README.md
git init
git config --global user.email "pfalisson@gmail.com"
git config --global user.name "Alisson Fernandes de Paula"
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/afplinuxtips/DescomplicandoKubernetes.git
git push -u origin main
```
