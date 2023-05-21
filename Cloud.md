git clone https://github.com/RhinoSecurityLabs/cloudgoat.git

### terraform

wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform


echo $PATH


mv ~/Downloads/terraform /usr/local/bin/

### Terra download
https://releases.hashicorp.com/terraform/1.4.6/terraform_1.4.6_linux_amd64.zip
