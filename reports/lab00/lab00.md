## Prvi terminal
    1  mkdir reports
    2  touch reports/lab00.md
    3  history
    4  git commit -a 
    5  git config --global zupanc.beno@gmail.com
    6  git config --global user.email zupanc.beno@gmail.com
    7  git config --global user.name "Zvmcevap"
    8  git commit -a 
    9  git commit -a .
   10  git commit .
   11  git add
   12  git add .
   13  git commit 
   14  git status
   15  sudo service ssh start
   16  sudo apt update
   17  sudo apt install tmate
   18  tmate
   19  history
   20  touch vaja00.sh
   21  vi vaja00.sh 
   22  bash vaja00.sh 
   23  vi vaja00.sh 
   24  bash vaja00.sh 
   25  vi vaja00.sh 
   26  mv vaja00.sh reports/
   27  mkdir lab00
   28  cd reports/
   29  mkdir lab00
   30  mv lab00.md lab00
   31  mv vaja00.sh lab00/
   32  cd lab00/
   33  bash vaja00.sh 
   34  history
## Drugi terminal
    3  clear
    4  whoami
    5  pwd
    6  cd
    7  ll
    8  cd /home/
    9  cd benzo/
   10  mkdir vaje00
   11  mkdir test
   12  ls
   13  ls -l
   14  ll
   15  touch datoteka.txt
   16  ls
   17  ls -l
   18  chmod u+x datoteka.txt 
   19  ls -l
   20  chmod +x datoteka.txt 
   21  ls -l
   22  chmod -x datoteka.txt 
   23  ls -l
   24  rm datoteka.txt 
   25  mv -r vaje00 Vaje00
   26  mv vaje00 Vaje00
   27  ls
   28  mv primer primer.txt
   29  touch primer
   30  mv primer vajat .txt
   31  mv primer vaja.txt
   32  mv vaja.txt Vaje00
   33  ls
   34  mv test/ Vaje00/
   35  ls
   36  cd Vaje00/
   37  ls
   38  ll
   39  alias
   40  ls
   41  ll
   42  nano vaja.txt 
   43  cat vaja.txt 
   44  ll
   45  vi vaja.txt 
   46  ll
   47  vi vaja.txt 
   48  ll
   49  vi vaja.txt 
   50  echo "hello" >> vaja.txt 
   51  cat vaja.txt 
   52  echo "hello" > vaja.txt 
   53  cat vaja.txt 
   54  echo "dodaj na konec" >> vaja.txt && cat vaja.txt 
   55  free
   56  free -h
   57  df -h
   58  top
   59  ps vx
   60  psvx
   61  ps aux 
   62  ps aux | grep vscode
   63  ps aux | grep sh
   64  ps aux | grep tmate
   65  history >> vaja00.txt
   66  ls
   67  cat vaja00.txt 
   68  history -a
   69  history
   70  history -a
   71  wc -l vaja.txt 
   72  wc -w vaja.txt 
   73  man wc
   74  man wc | grep char
   75  wc --help
   76  man awk
   77  history > vaja.txt 

   ## Tretji terminal
       1  ls
    2  cd
    3  ls
    4  ls -a
    5  tree
    6  ls -l
    7  main ls
    8  man ls
    9  ll -h
   10  ll --help
   11  mkdir test
   12  mkdir test/a
   13  rm test
   14  rm test/a
   15  rm -r test/a
   16  rm test/
   17  rm -r test
   18  tail -f /var/log/auth.log
   19  ls /var/log/
   20  cd /var/log/journal/
   21  ls
   22  ll
   23  ls -a
   24  cd ..
   25  ls
   26  tail dpkg.log
   27  cat dpkg.log
   28  cd ..
   29  cd
   30  find /home/ -name *.txt
   31  find /home/ -name "*.txt"
   32  git
   33  ls -a
   34  cp /mnt/c/Users/Beno/Desktop/Wait/.ssh .
   35  cp -r /mnt/c/Users/Beno/Desktop/Wait/.ssh .
   36  ls
   37  ls -a
   38  cd .ssh/
   39  ls
   40  cd ..
   41  mkdir KibernetskaVarnost
   42  cd KibernetskaVarnost/
   43  git clone git@github.com:Zvmcevap/KV-Vaje.git
   44  cd
   45  cd .ssh/
   46  ls
   47  ll
   48  cd ..
   49  chmod 700 ~/.ssh
   50  cd KibernetskaVarnost/
   51  git clone git@github.com:Zvmcevap/KV-Vaje.git
   52  chmod 600 ~/.ssh/id_ed25519
   53  chmod 600 ~/.ssh/id_rsa
   54  chmod 644 ~/.ssh/id_ed25519.pub
   55  git clone git@github.com:Zvmcevap/KV-Vaje.git
   56  cd KV-Vaje/
   57  code .
   58  sudo visudo
   59  passwd
   60  sudo service ssh start
   61  sudo apt update
   62  ssh
   63  ssh service
   64  sudo service ssh --help
   65  sudo service ssh --status-all
   66  sudo service ssh stop
   67  ssh 56yeGJwgQKBpTRVbj3P84g3zE@lon1.tmate.io
   68  history