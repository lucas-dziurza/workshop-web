# Vamos lá
## Instalando VS Code
### Método 1: instalação através do Terminal

#### Mas o que é um terminal? 
Terminal é uma das formas de se lidar com códigos. Vamos ver como:

Encontrando o terminal

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/terminal1.png)

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/terminal2.png)

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/terminal3.png)

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/terminal4.png)

🍃 Precisamos atualizar o Linux Mint antes da instalação, para isso:
```
sudo apt update && sudo apt upgrade
```

Vamos colar o código no terminal e apertar a tecla "Enter"
![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/terminal5.png)

📦 Agora instale esses pacotes:
```
sudo apt install dirmngr ca-certificates software-properties-common apt-transport-https -y
```

✅ Estamos indo bem! Agora vamos verificar a autenticação:
```
curl -fSsL https://packages.microsoft.com/keys/microsoft.asc | sudo gpg --dearmor | sudo tee /usr/share/keyrings/vscode.gpg > /dev/null
```

😥 Próximo passo:
```
echo deb [arch=amd64 signed-by=/usr/share/keyrings/vscode.gpg] https://packages.microsoft.com/repos/vscode stable main | sudo tee /etc/apt/sources.list.d/vscode.list
```

⛹️ Quase lá:
```
sudo apt update
```

🎆 E agora, finalmente a instalação:
```
sudo apt install code
```

![texto](https://github.com/lucas-dziurza/workshop-web/blob/main/Prints/terminal6.png)
