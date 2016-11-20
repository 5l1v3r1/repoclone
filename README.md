# repoclone

Bash Scripts to clone repositories from distributions using wget command .

debian : Clone full debian repository (amd64/i386)
debsec : Clone Full Debian-Security repository (amd64/i386) 
perl : Clone only Cpan (Perl) source repository
perlm : Clone only Cpan (Modules by name) repository
python : Clone only Python (source code) repository
ruby : Clone only Ruby /source code) repository
openwrt : clone full repository of Openwrt
pfsense : Clone full repository of Pfsense

repo : nginx server configuration file to be added to "/etc/nginx/sites-enabled/" directory

note : by default the nginx file is pointed to port 80 , but if you want to user a different port then edit the file and change the listening port

Information :
These scripts will clone the repository to /repositories/ folder on your HDD , if you want to change the location then edit the scripts and where it is :

wget -P /repositories/   -> change to the location you want .

After cloning the git , go to yout git folder in your HDD and apply execution permissions to the scripts :
chmod +x script name



to execute the script just write on scripts folder :
./script name

Requirements : Wget

install Wget in case you dont have it in your system :
apt-get install wget


