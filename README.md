# docker
    1  apt -update
    2  apt -get update
    3  apt-get update
    4  apt-get install git
    5  git -- version
    6  git --version
    7  apt-get install maven
    8  sudo apt install default-jdk
    9  sudo apt install default-jre
   10  java
   11  javac
   12  wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key |sudo gpg --dearmor -o /usr/share/keyrings/jenkins.gpg
   13  sudo sh -c 'echo deb [signed-by=/usr/share/keyrings/jenkins.gpg] http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
   14  sudo apt update
   15  sudo apt install jenkins
   16  sudo systemctl start jenkins.service
   17  sudo systemctl status jenkins.service
   18  cat /var/lib/jenkins/secrets/initialAdminPassword
   19  apt-get install docker .io
   20  apt-get install docker.io
   21  sudo sh -c 'echo deb [signed-by=/usr/share/keyrings/jenkins.gpg] http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
   22  docker --version
   23  cd 
   24  exit 
   25  cd 
   26  docker 
   27  docker pull centos
   28  docker images 
   29  docker run -it centos
   30  docker ps -a 
   31  docker commit 29d60005353d java-git-mvn-docker 
   32  docker images 
   33  docker run -itd e4a084866bd1
   34  docker ps -a 
   35  docker exec -it 83263b327a47 
   36  docker exec -it 83263b327a47 bash 
   37  docker images 
   38  docker login 
   39  docker ps -a 
   40  docker commit 29d60005353d reddyp/java-git-mvn-docker 
   41  docker images 
   42  docker push java-git-mvn-docker 
   43  docker push reddyp/java-git-mvn-docker 
   44  histoy
   45  history
   46  docker pull ubuntu
   47  docker images
   48  docker run -itd ubuntu
   49  docker ps -a
   50  docker exec -it 4bdebb75a40c bash
   51  docker ps -a
   52  docker commit 4bdebb75a40c reddyp/ubuntu-git-maven-java-docker
   53  docker images
   54  docker run-itd reddyp/ubuntu-git-maven-java-docker
   55  docker run -itd reddyp/ubuntu-git-maven-java-docker
   56  docker ps -a
   57  docker exec -it e0f0423685bf bash
   58  docker images
   59  docker login
   60  docker push 5e407c154877
   61  docker push reddyp/ubuntu-git-maven-java-docker
   62  docker pull nginx
   63  docker images
   64  $ docker run --name tmp-nginx-container -d nginx
   65  docker ps -a
   66  curl ifconfig.co
   67  curl ifconfig.com
   68  docker run --name some-nginx -d -p 8080:80 some-content-nginx
   69  docker run --name some-nginx -d -p 8080:80 nginx
   70  docker run --name some-nginx -d -p 8081:80 nginx
   71  docker ps -a
   72  docker stop d90001fd7542
   73  docker rm  d90001fd7542
   74  docker run --name some-nginx -d -p 8081:80 nginx
   75  docker ps -a
   76  docker stop 3a512f361e88
   77  docker star 3a512f361e88
   78  docker start 3a512f361e88
   79  docker ps -a
   80  history
   81  docker ps -a
   82  docker rm  5c6ac61ed2be
   83  docker stop 3a512f361e88 5c6ac61ed2be e0f0423685bf 4bdebb75a40c 83263b327a47 29d60005353d
   84  docker ps -a
   85  docker rm  3a512f361e88 5c6ac61ed2be e0f0423685bf 4bdebb75a40c 83263b327a47 29d60005353d
   86  docker ps -a
   87  docker images
   88  docker rmi 5e407c154877 9ab5e6954f03 e4a084866bd1 904b8cb13b93 74f2314a03de 5d0da3dc9764
   89  docker images
   90  exit
   91  docker pull ubuntu
   92  docker images
   93  docker run itd ubuntu
   94  docker run -itd ubuntu
   95  docker ps -a
   96  docker exec -it  74f2314a03de bash
   97  docker exec -it 74f2314a03de bash
   98  docker exec 74f2314a03de bash
   99  docker exec -it 74f2314a03de bash
  100  exit
  101  docker exec -it 74f2314a03de sh
  102  docker images
  103  docker exec -it 74f2314a03de bash
  104  docker ps -a
  105  docker exec -it eb88c0f443ad bash
  106  docker images
  107  docker exec -it eb88c0f443ad bash
  108  docker ps -a
  109  docker commit eb88c0f443ad reddyb/ubuntu
  110  docker images
  111  docker run -itd reddyb/ubuntu
  112  docker ps -a
  113  docker exec -it fd60748ae45a bash
  114  docker images 
  115  docker push reddyb/ubuntu
  116  docker ps -a
  117  docker commit fd60748ae45a reddyp/ubuntu
  118  docker images
  119  docker push reddyp/ubuntu
  120  docker pull nginx
  121  docker images
  122  docker run -itd --p 8081:80
  123  docker run -itd --p 8081:80 nginx
  124  docker run -itd --p 8080:80 nginx
  125  docker run -itd -p 8080:80 nginx
  126  docker run -itd -p 8081:80 nginx
  127  docker pull httpd
  128  docker images
  129  docker run -dit --name my-running-app -p 8082:80 httpd
  130  docker ps -a
  131  docker stop 033785d41592 10fdaf1958c7 e8ae0bc89717 fd60748ae45a eb88c0f443ad
  132  docker images
  133  docker ps -a
  134  docker rm 033785d41592 10fdaf1958c7 e8ae0bc89717 fd60748ae45a eb88c0f443ad
  135  docker ps -a
  136  cd
  137  docker ps -a
  138  docker commit 989e35815189 hemadri92642/jinkens
  139  docker images
  140  docker push hemadri92642/jinkens
  141  docker pull ansible/ansible
  142  docker pull ansible
  143  docker images
  144  docker ps -a
  145  docker run -itd --name nigex nigex
  146  docker pull nigex
  147  docker pull nginx
  148  docker run -itd --name nginx nginx
  149  docker ps -a
  150  docker run -itd --name hemadri nginx
  151  docker ps -a
  152  docker run -itd -p 8080:8080 --name hemadri1 nginx
  153  docker run -itd -p 1234:8080 --name hemadri1 nginx
  154  docker run -itd -p 1234:8080 --name reddy nginx
  155  docker ps -a
  156  mkdir redy
  157  mkdir reddy
  158  ls
  159  docker run -itd -v reddy/:/reddy/ nginx
  160  docker run -itd -v reddy:reddy nginx
  161  docker pull centos
  162  docker volum create reddy
  163  docker volume create reddy
  164  docker image
  165  docker images
  166  docker run -itd -v reddy:reddy centos
  167  docker run -itd -v reddy/:/reddy/ centos
  168  docker volume ls 
  169  dockker run -itd -v reddy/: reddy/ 5d0da3dc9764
  170  docker run -itd -v reddy/: reddy/ 5d0da3dc9764
  171  docker run -itd -v reddy/:reddy/ 5d0da3dc9764
  172  docker run -itd -v reddy:reddy 5d0da3dc9764
  173  docker run -itd --v reddy:reddy 5d0da3dc9764
  174  cd 
  175  $ docker run --name my-custom-nginx-container -v /host/path/nginx.conf:/etc/nginx/nginx.conf:ro -d nginx
  176  mkdir /host/path/
  177  mkdir -p  /host/path/
  178  $ docker run --name my-custom-nginx-container -v /host/path/nginx.conf:/etc/nginx/nginx.conf:ro -d nginx
  179  $ docker run --name my-custom-nginx-co -v /host/path/nginx.conf:/etc/nginx/nginx.conf:ro -d nginx
  180  cd /host/path/nginx.conf/
  181  ls
  182  cd ..
  183  ls
  184  rm -rf nginx.conf/
  185  cd 
  186  ls
  187  docker ps -a 
  188  docker stop beb56f7a091c fdd2ff36c14e 18a50773f237  c60436fa809f  4158ddac527f  df6ba8f04dcf  8fb285722e67  989e35815189  225a2f53389f  655f120fdb94  408357ffc8fe
  189  docker rm beb56f7a091c fdd2ff36c14e 18a50773f237  c60436fa809f  4158ddac527f  df6ba8f04dcf  8fb285722e67  989e35815189  225a2f53389f  655f120fdb94  408357ffc8fe
  190  docker ps -a
  191  docker images 
  192  docker rmi 5b697a67dab1  81806f9e1997  8c3991b2c7d8  a316da458056  b2ba128c8a2d  c1051e096a68  904b8cb13b93  b2aa39c304c2  49b688bb027c  1b3b8dd8a5f6 
  193  docker images 
  194  docker run -itd 5d0da3dc9764
  195  docker ps -a 
  196  docker exec -it ea1cc7c3caae bash 
  197  ls
  198  docker cp reddy/:ea1cc7c3caae/reddyprasad  
  199  docker cp reddy/ ea1cc7c3caae:/reddyprasad  
  200  vim reddy/deveops
  201  docker cp reddy/ ea1cc7c3caae:/reddyprasad  
  202  docker exec -it ea1cc7c3caae bash 
  203  docker cp ea1cc7c3caae:/reddyprasad  redy/ 
  204  cd redy
  205  ls
  206  exit
  207  docker images
  208  docker run -itd -h hemadri 5d0da3dc9764
  209  docker pa -
  210  docker pa -A
  211  docker pa -a
  212  docker ps -a
  213  docker exec -it aa29a4a866d7 bash
  214  cd 
  215  docker images 
  216  docker run --name some-nginx -v /some/content:/usr/share/nginx/html:ro -d nginx
  217  docker ps -a 
  218  ls
  219  /some/content/
  220  ls
  221  mkdir -p /some/content/
  222  ls
  223  cd /some/content/
  224  ls
  225  docker stop 599b03a801b5
  226  docker rm  599b03a801b5
  227  docker stop aa29a4a866d7 ea1cc7c3caae
  228  docker rm aa29a4a866d7 ea1cc7c3caae
  229  docker ps -a
  230  docker images 
  231  docker run --name some-nginx -v /some/content:/usr/share/nginx/html:ro -d nginx
  232  docker run --name some-nginx -p 8081:80  -v /some/content:/usr/share/nginx/html:ro -d nginx
  233  docker ps -a 
  234  docker stop 736357868a5a
  235  docker rm 736357868a5a
  236  docker run --name some-nginx -p 8081:80  -v /some/content:/usr/share/nginx/html:ro -d nginx
  237  exit 
  238  cd /some/content/
  239  ls
  240  mkdir html/
  241  cd html/
  242  ls
  243  vim index.html
  244  docker ps -a 
  245  docker stop cee30c477bfa
  246  docker rm cee30c477bfa
  247  docker run --name some-nginx -p 8081:80  -v /some/content:/usr/share/nginx/html:ro -d nginx
  248  cd ..
  249  ls
  250  rm -rf html/
  251  vim index.html
  252  vim index.html 
  253  cd 
  254  docker ps -a 
  255  docker commit 8f98ec80cf4b hemadri92642/myloginfrom-nginx 
  256  docker images 
  257  docker push hemadri92642/myloginfrom-nginx
  258  history 
  259  cd 
  260  docker pull hemadri92642/myloginfrom-nginx
  261  docker run --name mylogin -p 8082:80  -v /some/content:/usr/share/nginx/html:ro -d nginx
  262  netstat -ntlp
  263  service jenkins start 
  264  systemctl status jenkins.service
  265  java 
  266  systemctl start  jenkins.service
  267  wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key |sudo gpg --dearmor -o /usr/share/keyrings/jenkins.gpg
  268  sudo sh -c 'echo deb [signed-by=/usr/share/keyrings/jenkins.gpg] http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
  269  sudo apt update
  270  sudo apt install jenkins
  271  cd /var/lib/dpkg/lock-frontend
  272  cd /var/lib/dpkg/
  273  ls
  274  rm -rf lock-frontend
  275  sudo apt install jenkins
  276  history 
