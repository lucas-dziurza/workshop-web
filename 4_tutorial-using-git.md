# TUTORIAL DE GIT

🏁 Começe abrindo a pasta do seu projeto no VSCode, clique nos **três pontinhos** na barra superior, em **terminal** e **new terminal**

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git1.png)
![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git2.png)

<br>
<br>


💻 Agora no terminal integrado, copie e cole os códigos na seguinte ordem:


![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git3.png)
![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git4.png)
![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git5.png)


```
sudo apt update
```

```
sudo apt install git
```

```
git --version
```

<br>
<br>

👤 Configurar seu usuário. Para isso, copie os códigos e coloque as suas informações:

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git6.png)
![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git7.png)

```
git config --global user.name "Seu Nome"
```

```
git config --global user.email "seu@email.com"
```
<br>
<br>

🔎 Conferir se está tudo correto:

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git8.png)

```
git config --list
```
<br>
<br>

🏗️ Iniciar o Git no seu projeto. O primeiro comando inicia o Git no projeto e o segundo adiciona todos os arquivos do seu projeto dentro da pasta do Git

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorialgit10.png)

```
git init
```


```
git add .
```

<br>
<br>

🪢 Atrelar o repositório remoto ao repositório local. Atenção, altere o código e adicione o nome de usuário do Github e o nome do repositório.git

📨 Fazer o primeiro commit

🫸 Dar push das mudanças para o repositório remoto (lá no Github)

<br>

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/tutorial-git8.png)

```
git remote add origin https://github.com/seu-user/seu-repositorio.git
```

```
git commit -M "First commit"
```

```
git push -u origin main
```
