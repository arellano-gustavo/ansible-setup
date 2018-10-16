# ansible-setup
Pasos para levantar un servidor "Creador de instancias AWS"

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
    11  cat ~/.ansible.cfg
    12  nano ~/.ansible.cfg
    13  ansible-playbook -vv -i localhost, -e "type=webservers" provision-ec2.yml
    14  ansible-playbook -vvvv -i localhost, -e "type=webservers" provision-ec2.yml
    15  ansible-playbook -vvvv -i localhost, -e "type=webservers" provision-ec2.yml  --private-key meta.pem 
    16  tar -czvf prueba-ansible-aws.tar.gz prueba-ansible-aws
    17  cat .ansible.cfg 
    18  docker run -d --restart=always -p 8383:8080 rancher/server
    19  sudo sh -c "echo 'LC_ALL=en_US.UTF-8\nLANG=en_US.UTF-8' >> /etc/environment"
    20  scp -i sci.pem  prueba-ansible-aws.tar.gz    ubuntu@34.194.36.154:/home/ubuntu
    21  cat .profile 
    22  cat .ansible.cfg 
    23  rm -rf prueba-ansible-aws.tar.gz 
    24  cd prueba-ansible-aws/
    25  nano ansible-info.txt
    26  tar czvf prueba-ansible-aws.tar.gz  prueba-ansible-aws
    27  scp -i sci.pem  prueba-ansible-aws.tar.gz    ubuntu@34.194.36.54:/home/ubuntu
    28  rm -rf prueba-ansible-aws.tar.gz 
    29  tar czvf prueba-ansible-aws.tar.gz  prueba-ansible-aws
    30  scp -i sci.pem  prueba-ansible-aws.tar.gz    ubuntu@34.194.36.54:/home/ubuntu
    31  cat .boto 
    32  cat .ansible.cfg 

FIN
