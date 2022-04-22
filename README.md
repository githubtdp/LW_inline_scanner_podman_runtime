## Lacework inline scanner with podman continer runtime configuration

#Download inline scnner for RHEL/CentOS - x86_64 x86_64 x86_64 GNU/Linux
wget https://github.com/lacework/lacework-vulnerability-scanner/releases/download/v0.2.14/lw-scanner
chmod +x lw-scanner
sudo mv lw-scanner /usr/local/bin/

# Integrate Inline scanner with Lacework platform 
Configuring lacework Inline scanner 
lw-scanner configure auth
lw-scanner configure scanner


# Insatlling Podman-dcoker dependancy for podman conatiner runtime 

sudo yum install podman-docker


