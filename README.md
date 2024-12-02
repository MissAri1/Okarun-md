### **OKARUN MD**


```**WHATSAPP BOT MULTI DEVICE CODED BY CYBER TECH ☢️*```



![460676718_392018660637444_7340705730428309119_n](https://github.com/user-attachments/assets/60f7559d-141e-4f44-85c5-3e37066a7099)






##           [![FORK OKARUN_MD](https://img.shields.io/badge/FORK%20-OKARUN%20MD-red)](github.com/Lordhades-qp/Okarun-md/fork)

-------

 <p align="center">
  <a href="#"><img src="http://readme-typing-svg.herokuapp.com?color=00008B&center=true&vCenter=true&multiline=false&lines=`ARIMA+FORGER+DU+CLAN+ÉTERNEL`" alt="">

<br>

--------

       
<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=800&size=28&duration=4000&pause=1000&random=false&width=435&lines=+•★⃝ OKARUN-+MD★⃝•;MULTI-DEVICE+WHATSAPP+BOT;DEVELOPED+BY+CYBER TECH ☢️;DECEMBER+2024." alt="Typing SVG" /></a>
 </p>


--------


### <br>    ❖ SESSION_ID ❖


`✠ IF YOU DON'T HAVE YOUR SESSION_ID SO U CAN GET IT CLICK ON SESSION_ID BUTTON AND PASTE YOUR NUMBER With COUNTRY CODE EXAMPLE:+237xxxxxxxxx THEN YOU CAN GET YOUR SESSION_ID ✠`

----------
. `USE SESSION `.
<p align="center">
<a href="https://cyber-tech-session-generator.onrender.com"><img height= "35" title="Author" src="https://img.shields.io/badge/GET SESSION ID:1-black?style=for-the-badge&logo=render"></a>
<p/>


---------------


## <p align="center"><br>   DEPLOY IN RENDER
<a href='https://dashboard.render.com' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/RENDER-h?color=maroon&style=for-the-badge&logo=render'/></a></p>


------------

`yaml

## <p align="center">  `WHATSAPP`
<a href='https://wa.me/2250565647864.com' target="_blank"><img
alt='><[![`0565647864`]><a' src='https://img.shields.io/badge/WhatsApp-h?
color=green&style=for-the-badge&logo=WhatsApp'/></a></p>
</p>

----------


<p align="center"><h1>okarun.md</h1><br> </p>
![banner](okarun.jpg)


----------


- ## <br>  **DÉPLOIEMENT SUR KOYEB** :
  1. Si vous n'avez pas de compte **Koyeb**, cliquez [**ici**](https://dashboard.koyeb.com/signup) pour en créer un.
  2. Cliquez sur le bouton ci-dessous pour déployer sur Koyeb :<br>
     [![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=okarun md&type=docker&image=docker.io%2FCYBER TECH ☢️077%2Fokarunmd%3Alatest&env%5BPREFIXE%5D=.&env%5BLECTURE_AUTO_STATUS%5D=oui&env%5BTELECHARGER_AUTO_STATUS%5D=oui&env%5BNOM_BOT%5D=OKARUN-MD&env%5BLIENS_MENU%5D=https%3A%2F%2Fwallpapercave.com%2Fuwp%2Fuwpuwp4572692.jpeg&env%5BPM_PERMIT%5D=non&env%5BMODE_PUBLIC%5D=non&env%5BETAT%5D=1&env%5BSESSION_ID%5D=mettez+votre+session&env%5BNOM_OWNER%5D=CYBER TECH ☢️%2B%2B&env%5BNUMERO_OWNER%5D=2250565647864&env%5BWARN_COUNT%5D=3&env%5BSTARTING_BOT_MESSAGE%5D=oui&env%5BANTI_VUE_UNIQUE%5D=oui&env%5BPM_CHATBOT%5D=non&env%5BHEROKU%5D=non&env%5BDATABASE_URL%5D=mettez+une+database&env%5BANTI_COMMAND_SPAM%5D=non&ports=8000%3Bhttp%3B%2F)

## <br> **SUGGESTIONS DE DÉPLOIEMENT SUR RENDER**.

  1.Choisissez **Public Git Repository**.  
  2. Dans le champ , entrez `https://gitlab.com/bankai421341/senbonzakura.git`.
  3. Cliquez sur **Connect**.  
  4. Sélectionnez le **Free Plan** si vous ne voulez pas payer.  
  5. Dans la section **environemment variable**, cliquez sur 
  **Add from .env** et copiez le contenu suivant :

     ```env
     PREFIXE=.
     LECTURE_AUTO_STATUS=oui
     TELECHARGER_AUTO_STATUS=oui
     NOM_BOT=OKARUN-MD
     LIENS_MENU=https://wallpapercave.com/uwp/uwp4572692.jpeg
     PM_PERMIT=non
     MODE_PUBLIC=non
     ETAT=1
     SESSION_ID=okarun
     NOM_OWNER=CYBER TECH ☢️
     NUMERO_OWNER=2250565647864
     WARN_COUNT=3
     STARTING_BOT_MESSAGE=oui
     ANTI_VUE_UNIQUE=oui
     PM_CHATBOT=non
     ANTI_COMMAND_SPAM=non
     ```

  8. Cliquez sur **Add env** pour enregistrer, puis modifiez selon vos besoins. N'oubliez pas d'entrer votre session ID.  
  9. Cliquez sur **Deploy service** et profitez-en !


 - ## <br>   **DÉPLOIEMENT SUR GITHUB**

  1. **Forkez le dépôt**.
  2. Modifiez le fichier `exemple_de_set.env` en `set.env` et ajoutez-y votre **session_ID**.
  3. Créez un nouveau fichier `.github/workflows/deploy.yml` et mettez-y ce contenu :

```yml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */4 * * *'

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: |
        npm install -g pm2
        npm install

    - name: Start application with timeout
      run: |
        timeout 14520s npm run OKARUN

```


## Licence 📜

Le Bot WhatsApp OKARUN-MD est publié sous la [Licence MIT](https://opensource.org/licenses/MIT).


## Développeurs :
- [**Lord Hadès**](github.com/lordhades-qp/okarun-md)
- [**᚛CYBER TECH ☢️᚜**]
- [**ARIMA FORGER**]

-------<br>/alt/<p>

