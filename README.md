# jenkins-pipeline-commands
 2  yum install java-11 -y
    3  wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
    4   rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
    5  java --version
    6  yum install jenkins
    7  systemctl start jenkins
    8  systemctl enable jenkins
    9  systemctl status jenkins
   10  cat /var/lib/jenkins/secrets/initialAdminPassword~
   11  cat /var/lib/jenkins/secrets/initialAdminPassword
   12  clear
   13  clear
   14  wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.4.0.54424.zip
   15  unzip*
   16  unzip *
   17  chmod -R 755 /home/sonarqube/sonarqube-9.4.0.54424
   18  ls
   19  cd sonarqube-9.4.0.54424
   20  chmod -R 755
   21  cd ..
   22  chmod -R 755 sonarqube-9.4.0.54424
   23  chown -R sonarqube:sonarqube /home/sonarqube/sonarqube-9.4.0.54424
   24  chown -R 755 sonarqube-9.4.0.54424
   25  cd sonarqube-9.4.0.54424/bin/linux-x86-64/
   26  ls
   27  ./sonar.sh start
   28  cd ..
   29  ls
   30  cd ..
   31  ls
   32  rm sonarqube-9.4.0.54424
   33  pwd
   34  git --version
   35  java --version
   36  jenkins --version
   37  docker --version
   38  yum install git
   39  yum install docker
   40  git --version
   41  docker --version
   42  git init
   43  git status
   44  git config --global user.name "balakrishna"
   45  git config --global user.email "balakrishnachary15@gmail.com"
   46  docker start service
   47  service start docker
   48  systemctl start docker.service
   49  systemctl status docker.service
   50  systemctl enable docker.service
   51  systemctl status docker.service
   52  adduser sonarqube
   53  passwd sonarqube
   54  sudo -su sonarqube
   55  ls
   56  cat /etc/passwd
   57  sudo -su sonarqube
   58  wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
   59  cp minikube-linux-amd64 /usr/local/bin/minikube
   60  chmod +x /usr/local/bin/minikube
   61  curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-
   62  curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
   63  chmod +x kubectl
   64  mv kubectl /usr/local/bin/
   65  minikube start --driver=docker
   66  minikube status
   67  minikube start
   69  sudo yum install conntrack
   70  minikube start --driver=none
   71  minikube start
   72  minikube start --force
   73  minikube status
   74  curl -sL https://github.com/operator-framework/operator-lifecycle-manager/releases/download/v0.24.0/install.sh | bash -s v0.24.0
   75  kubectl create -f https://operatorhub.io/install/argocd-operator.yaml
   76  kubectl get csv -n operators
   77  usermod -aG docker ec2-user
      usermod -aG docker jenkins
   78  kubectl get csv -n operators
   79  history
![image](https://github.com/balakrishnachary/jenkins-pipeline-commands/assets/132567878/8bfbb0cd-330f-4e42-939e-92ddc415cb92)
