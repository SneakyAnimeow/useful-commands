///.NET

dotnet ef dbcontext scaffold <Connection String> <Microsoft.EntityFrameworkCore.InsertYourDatabase> --context <YourContext> --context-dir Context --output-dir Model

dotnet tool update --global dotnet-ef 

///JAVA

jdeps --ignore-missing-deps -q -s -recursive .\build\libs\fat-jar.jar

def os = System.getProperty("os.name").toLowerCase()

///UFW
sudo iptables -L &&
sudo iptables-save > ~/iptables-rules &&
sudo iptables -P INPUT ACCEPT &&
sudo iptables -P OUTPUT ACCEPT &&
sudo iptables -P FORWARD ACCEPT &&
sudo iptables -F &&
sudo iptables --flush &&
sudo apt install -y ufw &&
sudo ufw allow ssh &&
sudo ufw allow 80 &&
sudo ufw allow 443 &&
sudo ufw allow 21 &&
sudo ufw default deny incoming &&
sudo ufw reload &&
sudo ufw enable

///INSTALLING LUA LAPIS ON ORACLE CLOUD (x86-64/AMD64 && ARM) && SWITCHING FROM IPTABLES TO UFW
#UBUNTU 16-20

#ARM
  
sudo apt update -y && 
sudo apt upgrade -y &&
sudo apt install screen -y &&
sudo apt install libssl-dev -y &&
sudo apt install lua5.1 -y &&
sudo apt install luarocks -y &&
sudo apt-get -y install --no-install-recommends wget gnupg ca-certificates &&
wget -O - https://openresty.org/package/pubkey.gpg | sudo apt-key add - &&
echo "deb http://openresty.org/package/arm64/ubuntu $(lsb_release -sc) main"  | sudo tee /etc/apt/sources.list.d/openresty.list &&
sudo apt update -y &&
sudo apt install -y openresty &&
sudo apt install -y nginx &&
sudo mkdir /usr/lib/x86_64-linux-gnu/ &&
sudo cp /usr/lib/aarch64-linux-gnu/libssl* /usr/lib/x86_64-linux-gnu/ &&
sudo cp /usr/lib/aarch64-linux-gnu/libcrypto* /usr/lib/x86_64-linux-gnu/ &&
sudo luarocks install lapis &&
sudo iptables -L &&
sudo iptables-save > ~/iptables-rules &&
sudo iptables -P INPUT ACCEPT &&
sudo iptables -P OUTPUT ACCEPT &&
sudo iptables -P FORWARD ACCEPT &&
sudo iptables -F &&
sudo iptables --flush &&
sudo apt install -y ufw &&
sudo ufw allow ssh &&
sudo ufw allow 80 &&
sudo ufw allow 443 &&
sudo ufw allow 21 &&
sudo ufw default deny incoming &&
sudo ufw reload &&
sudo ufw enable

#amd64
  
sudo apt update -y && 
sudo apt upgrade -y &&
sudo apt install screen -y &&
sudo apt install libssl-dev -y &&
sudo apt install lua5.1 -y &&
sudo apt install luarocks -y &&
sudo apt-get -y install --no-install-recommends wget gnupg ca-certificates &&
wget -O - https://openresty.org/package/pubkey.gpg | sudo apt-key add - &&
echo "deb http://openresty.org/package/ubuntu $(lsb_release -sc) main" \ | sudo tee /etc/apt/sources.list.d/openresty.list &&
sudo apt update -y &&
sudo apt install -y openresty &&
sudo apt install -y nginx &&
sudo luarocks install lapis &&
sudo iptables -L &&
sudo iptables-save > ~/iptables-rules &&
sudo iptables -P INPUT ACCEPT &&
sudo iptables -P OUTPUT ACCEPT &&
sudo iptables -P FORWARD ACCEPT &&
sudo iptables -F &&
sudo iptables --flush &&
sudo apt install -y ufw &&
sudo ufw allow ssh &&
sudo ufw allow 80 &&
sudo ufw allow 443 &&
sudo ufw allow 21 &&
sudo ufw default deny incoming &&
sudo ufw reload &&
sudo ufw enable
