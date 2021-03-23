# Setup Proiect iTEC

 

 - Pentru început,trebuie să dai **Fork** la repository-ul cu numele echipei tale / proiectului tău cu ajutorul butonului de sub profilul propriu (colț dreapta sus), pentru a îți crea o clona a proiectului iTEC in profilul tău.
![Fork here](https://i.ibb.co/8r7f1xZ/fork.jpg)
 - După ce ești redirecționat la Repository-ul nou creat, trebuie să faci o **clonă**( **Clone** ) prin apăsarea butonului **Code** și să copiezi link-ul.
![enter image description here](https://i.ibb.co/1nFWmkq/Clone.jpg)
 - După ce ai copiat link-ul, ai mai multe metode prin care poți lua local repository-ul pentru a îl putea edita. Poți folosi **Github Desktop** sau direct din **Git Bash**.  (Pentru ambele metode trebuie să ai instalat **Git**.)
## Git Clone din Git Bash
 -  Deschide Git Bash .
    
 -  Schimbați directorul de lucru curent în locația în care doriți directorul clonat.
    
 -  Tastați `git clone`, apoi lipiți adresa URL pe care ați copiat-o mai devreme.
    
    ```shell
    $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    ```
    
 -  Apăsați **Enter** pentru a crea clona locală.
    
    ```shell
    $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    > Cloning into `Spoon-Knife`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.
    ```
## După clonarea proiectului
 - Odată ce ai repository-ul local, poți începe să lucrezi și să îți creezi folderele necesare în locul unde ai clonat repository-ul.
 - Când ai terminat proiectul, poți urca codul acestuia pe GitHUB, prin operațiile de **commit** și **push**.
 - Pentru a putea fi jurizați, trebuie să creați un **Pull Request** din repository-ul vostru către cel al concursului, folosind secțiunea de **Pull Requests**.
 ![enter image description here](https://i.ibb.co/VLxtbcZ/pull-request.jpg)
 - Apeși pe butonul **New Pull Request**
 ![enter image description here](https://i.ibb.co/4j1NGL0/newpullrequest.jpg)
- Verificați ca ruta de la ”base repository” să fie **itec-ligaac/** și apoi apasă pe **Create Pull Request**.
![enter image description here](https://i.ibb.co/2ST1Kwn/createpullrequest.jpg)

## Sfaturi și recomandări
 - Odată ce aveți părți din proiect de care sunteți siguri pe ele (nu au erori, codul este compilabil), vă recomandăm să dați *commit* cu acestea, împreună cu mici descrieri a ce reprezintă acea bucată de cod.
 - Proiectele voastre ar trebui să fie originale.
