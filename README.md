# Unofficial-pfSense-packages
Unofficial packages for pfSense software

As many people knows, Netgate has trimed a lot of packages from official repo since pfSense® 2.3. 

This repo updates some packages for newer pfSense software versions with manual procedure installs.

This is not supported by Netgate or pfSense team. Use it at your own risk.

Feedbacks and contributions are always welcome.

# Install instructions

You can enable unoffical repo creating or downloading the file below:

AMD64
fetch -q -o /usr/local/etc/pkg/repos/Unofficial.conf https://raw.githubusercontent.com/marcelloc/Unofficial-pfSense-packages/master/Unofficial.conf

I386
fetch -q -o /usr/local/etc/pkg/repos/Unofficial.conf https://raw.githubusercontent.com/marcelloc/Unofficial-pfSense-packages/master/Unofficiali386.conf

After fetching the repo file, you will be able to see these packages under System -> Package Manager
