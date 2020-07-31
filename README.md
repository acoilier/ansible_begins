# Formation Ansible : De zéro à l'autonomie
Cette formation présente l'outil Ansible et aborde les compétences de bases pour commencer à l'utiliser. 

Lors de cette formation des Labs permettrons de manipuler Ansible et de manager plusieurs serveurs, nous utiliserons pour ceci la plateforme [Play Whis Docker](https://labs.play-with-docker.com/) comme lab. Il est nécessaire que tu aies les connaissances de base d'utilisation d'un système Linux pour suivre cette formation.

## Lien du cours:
- [Présentation du cours]() (pas disponible pour l'instant)
- [Projet github](https://github.com/acoilier/ansible_begins)
- [Play Whis Docker](https://labs.play-with-docker.com/)

## Utilisation de Play Whis Docker :
### Connexion à PWD :
La plateforme PWD est un projet soutenu par Docker afin de faire des Labs Docker gratuitement. Dans notre cas nous n'utiliserons pas Docker, mais seulement les instances de serveurs qu'il est possible de générer. Afin de pouvoir l'utiliser il faut que tu aies un compte docker, tu peux t'en créer un en suivant le modop ci-dessous:
1. Se connecter sur le site [Play Whis Docker](https://labs.play-with-docker.com/).  
2. Cliquer sur **Login** puis **docker**  
3. Si tu as un compte Docker tu peux l'utiliser sinon il faudra en créer un en cliquant sur **sign up**.  
### Utilisation de PWD:
Quand tu es connecté, tu as accès pour 4H au Lab avant sa destruction. Il sera possible de le relancer autant de fois que tu le souhaites, mais note bien que tu repars de zéro a chaque fois.  

Commance par te créer une instance en cliquant sur **ADD NEW INSTANCE**. Tu as ensuite la possibilité de taper tes commandes directement dans l'interface web, cependant je te conseille de te connecter dessus directement en SSH avec le l'adresse qui t'est donnée dans le récap du haut de la page (pour pouvoir faire des tabulations).  
Si tu es sur Windows tu as **putty.exe** sinon le [nouveau terminal Microsoft](https://www.microsoft.com/fr-fr/p/windows-terminal-preview/9n0dx20hk701?activetab=pivot:overviewtab) qui exécute une instance [Windows Subsystem Linux](https://docs.microsoft.com/fr-fr/windows/wsl/install-win10), pour WSL je te préviens c'est un peu long à installer (du powershell et un reboot) garde le pour plus tard si ce n’est pas déjà OK pour toi ;)

Bon la on est pas mal, tu as accès à ton serveur et tu peux en ajouter d'autres cliquant sur **ADD NEW INSTANCE**.  

> ***Bon à savoir :*** Sur la plateforme PWD les serveurs utilisés sont des Alpine Linux. Il faudra donc installer les packages avec la commande apk, voir exemple ci-dessous pour 

## Récupération du dépôt sur Github:

Clone le dépôt de la formation dans ton home directory avec la commande ci-dessous:

> git clone https://github.com/acoilier/ansible_begins.git

C'est bon tu es prêt pour commencer les labs, let's go !!!

[Go to LAB 1](https://github.com/acoilier/ansible_begins/...)

