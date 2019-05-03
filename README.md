Building Ganesha (And other RPMS)

This is a yaml2rpm-based (https://github.com/RCIC-UCI-Public/yaml2rpm) 
repo for building RPMS with explicitly managing RPM spec files

0. If you have a vanilla CentOS7 system, you can prep it for building.
See https://github.com/RCIC-UCI-Public/development-RPMS
1. make download   
2. cd yamlspecs; make bootstrap; make

your ganesha rpm should be in RPMS/x86_64


