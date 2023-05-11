 2  yum update -y
    4  hostnamectl set-hostname jenkinsserver.com
    5  exec bash
    6  yum install vim wget make tar unzip -y
    7   yum install curl-devel expat-devel gettext-devel openssl-devel zlib-devel -y
    8
    9  yum install gcc perl-ExtUtils-MakeMakers -y
   10
   11  yum install gcc perl-ExtUtils-MakeMaker -y
   12  cd/opt
   13   wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.40.1.tar.gz
   14   tar -xvf git-2.40.1.tar.gz
   15   cd git-2.40.1
   16
   17  ll
   18  make prefix=/usr/local/git all
   19  make prefix=/usr/local/git install -y
   20  make prefix=/usr/local/git install
   21  git --version
   22  vim ~/.bashrc
   23  source ~/.bashrc
   24  git --version
   25  sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
   26    sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
   27
   28   yum install fontconfig java-11-openjdk -y
   29  yum install jenkins -y
    systemctl status jenkins
   32  systemctl start jenkins
   33  systemctl status jenkins
   34  sytemctl stop firewalld
   35  systemctl stop firewalld
   36  ip a
   37  cat /var/lib/jenkins/secrets/initialAdminPassword
   38  which git
   39  cd /var/lib/jenkins/workspace/
   40  ll
   41  cd test-job1/
   42  ll

