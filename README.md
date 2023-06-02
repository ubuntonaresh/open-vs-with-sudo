# open-vs-with-sudo


Follow these steps :

sudo chown -R <current_user> <path_to_your_vscode_installation_directory>
As per your requirement, user will be
user : root
You can find path of vscode directory using following command :
whereis code
e.g. path could be : /usr/share/code
So final command will be :
sudo chown -R root /usr/share/code
This will run vscode as root without the need of --user-data-dir argument.
