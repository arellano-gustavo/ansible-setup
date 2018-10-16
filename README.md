# ansible-setup
Pasos para crear un creador de instancias AWS

  1  sudo nano /etc/hosts
  2  sudo sh -c "echo 'LC_ALL=en_US.UTF-8\nLANG=en_US.UTF-8' >> /etc/environment"
  3  sudo apt-get update
  4  sudo apt-get install ansible
  5  tar xzvf ans.tar.gz 
  6  sudo apt-get install python-pip
  7  pip install -U boto
  8  nano  ~/.boto
  9  cd prueba-ansible-aws
  10  ansible-playbook -vv -i localhost, -e "type=webservers" provision-ec2.yml
  11  ~/.ansible.cfg
  12  nano ~/.ansible.cfg
  13  ansible-playbook -vv -i localhost, -e "type=webservers" provision-ec2.yml
  14  ansible-playbook -vvvv -i localhost, -e "type=webservers" provision-ec2.yml
  15  ansible-playbook -vvvv -i localhost, -e "type=webservers" provision-ec2.yml  --private-key meta.pem 
  16  tar -czvf prueba-ansible-aws.tar.gz prueba-ansible-aws
  17  mv prueba-ansible-aws.tar.gz ans.tar.gz
  18  cat .ansible.cfg 
  19  docker run -d --restart=always -p 8383:8080 rancher/server
  20  sudo sh -c "echo 'LC_ALL=en_US.UTF-8\nLANG=en_US.UTF-8' >> /etc/environment"
  21  nano .bash_history 
  22  cat .ansible.cfg 
  23  scp -i sci.pem  ans.tar.gz ubuntu@1.1.1.1:/ok
  24  scp -i sci.pem  ans.tar.gz ubuntu@34.194.36.54:/home/ubuntu
  25  cat .ansible
  26  cat .boto
  27  cd prueba-ansible-aws/
  28  nano boto-info.txt
  29  tar czvf prueba-ansible-aws.tar.gz  prueba-ansible-aws
  30  scp -i sci.pem  prueba-ansible-aws.tar.gz    ubuntu@34.194.36.54:/home/ubuntu
  31  cat .profile 
  32  cat .ansible.cfg 
  33  rm -rf prueba-ansible-aws.tar.gz 
  34  cd prueba-ansible-aws/
  35  nano ansible-info.txt
  36  tar czvf prueba-ansible-aws.tar.gz  prueba-ansible-aws
  37  scp -i sci.pem  prueba-ansible-aws.tar.gz    ubuntu@34.194.36.54:/home/ubuntu
  38  rm -rf prueba-ansible-aws.tar.gz 
  39  tar czvf prueba-ansible-aws.tar.gz  prueba-ansible-aws
  40  scp -i sci.pem  prueba-ansible-aws.tar.gz    ubuntu@34.194.36.54:/home/ubuntu
  41  cat .boto 
  42  cat .ansible.cfg 
  43  cd .ansible/
  44  cd prueba-ansible-aws/

