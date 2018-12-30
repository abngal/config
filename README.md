Moved to gitlab (re: private popjects)

# config

#should be applicable to both mac and linux 
#TODO: make a ??python?? script

pseudocodes

mkdir /etc/config
cd /etc
chmod a+rwx config
cd /config


touch aliases
echo ~/.zshrc << "source /etc/config/aliases"
echo ~/.bashrc << "source /etc/config/aliases"
