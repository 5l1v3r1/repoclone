# repoclone

Bash Scripts to clone repositories from distributions using wget command .

debian : Clone full debian repository (amd64/i386)<br />
debsec : Clone Full Debian-Security repository (amd64/i386)<br /> 
perl : Clone only Cpan (Perl) source repository<br />
perlm : Clone only Cpan (Modules by name) repository<br />
python : Clone only Python (source code) repository<br />
ruby : Clone only Ruby /source code) repository<br />
openwrt : clone full repository of Openwrt<br />
pfsense : Clone full repository of Pfsense<br />
opnsense : Clone full repository of OPNSense<br />
dotdeb : Clone full repository of Dotdeb (PHP/Nginx)<br />

repo : nginx server configuration file to be added to "/etc/nginx/sites-enabled/" directory <br />

note : by default the nginx file is pointed to port 80 , but if you want to user a different port then edit the file and change the listening port<br />

Information :<br />
These scripts will clone the repository to /repositories/ folder on your HDD , if you want to change the location then edit the scripts and where it is :<br />

wget -P /repositories/   -> change to the location you want .<br />

After cloning the git , go to yout git folder in your HDD and apply execution permissions to the scripts :<br />
chmod +x script name



to execute the script just write on scripts folder :<br />
./script name<br />

Requirements : Wget , Git<br />

install Wget in case you dont have it in your system :<br />
apt-get install wget git<br />


