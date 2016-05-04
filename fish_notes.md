#add a remote called origin (key)
#allows me to push (and pull) commits to and from the remote
git remote add origin URL

#push the urrent branch (master) to branch (also master) on the origin remote
#the first master refers to the local branch
#the second master refers to the remote branch
~/P/w/History master ✔ git push -u origin master

# once the local master branch is connect to a remote branh,
#i don't need to specif the remote or branch names
~/P/w/History master ✔ git push

# also shows the commit log of the local and remote branches
git ll

#initialize git repository(create a .git folder in the current working directory)
git init

#Adds my signature globally( for all repositories) in this environment
git config --global user.name "Name"
git config --global user.email "Email"

#take a look at the staging area
#files can be
# - untracked
# - tracked
# - committed (not in the staging area anymore)
git status

#creates a special file that ats as the bouncer to the staging area
#text colored grey
touch .gitignore

#adds changes in a file to the staging area
git add <file>

# commits the changes in the staging area to the commits area
# cleans out the staging area (prepares it for the next commit)
git commit -m 'MESSAGE'

#take a look at the commits area
#a bit verbose
git log

#like git log, but less verbose
#ot built-in to git, but an alias added on day 1
git ll

# like git log, but extremely verbose
#the only command tha shows the chnges
# not built-in git, but an alias we added on day 1
git la


#pipes sends hello world to notes.txt
echo 'hello world' > notes.txt

#This command is used to list the detail information of files and folder of a current directory
ll

# rm= removed rr= remove forcibly
rm -rf notebook/

#makes directory
mkdir notebook

#remove recursively
rm -r notebook

#remove(can do multiple files)
rm whatever.txt notes.txt

#cat prints contents of file to terminal(can do multiples)
cat notes.txt whatever.txt

#change ownership
chown whatever.txt

#opens fle in atom
atom whatever.txt

#copy contents to paste elsewhere
cp notes.txt whatever.txt

#opens in atom
atom notes.txt
atom notes

#creates file
touch notes.txt

#print working directory
pwd

#change directory
cd Notebook/

#make directory
mkdir week1

#home directory
~

#shows contents ma
less notes.txt

#moves file
mv backup.txt

#Moves file up a directory
mv backupfile.txt../

#search term
grep jake

tree
cd Applications/
cd sbin
sbin/pwd
ls
cd /
tree -L 2
tree -L 1
brew install tree
echo ~
echo .
echo '~'
open Documents
open .
id
ls -n
-n
ls -TR
ls -R
ls -r
ls -lTt
ls 0lT
ls -T
ls -t
ls -S
-S
ls -H
ls -B
ls -a
ls -A
ls - A
ls -1
ls -l
open http://peterdoane.surge.sh
surge
cat CNAME
cd ~/Projects/peterdoane.surge.sh/
..
npm install -g surge
npm -v
which npm
brew postinstall node
sudo chown -R peterdoane:admin node_modules/
cd /usr/local/lib/
brew install node
brew cleanup
brew uninstall node
sudo chown peterdoane:admin subl
sudo peterdoane:admin subl
chown peterdoane:admin subl
unlink npm
unlink node-inspector
unlink node-debug
unlink learnyounode
unlink jshint
unlink javascripting
cd /usr/local/bin/
node -v
brew link --overwrite node
sudo rm -rf /usr/local/lib/dtrace
sudo rm -rf tapset/
cd /usr/local/share/systemtap/
sudo rm -rf node/
cd /usr/local/share/doc/
brew doctor
rm -rf node/
cd /usr/local/include/
git commit -m 'Add a CNAME'
git add CNAME
touch CNAME
git commit -m 'Add a tiny web page'
git add index.html
open index.html
atom .
touch index.html
git init
cd ~/Projects/
cd
mkdir peterdoane.surge.sh
cd /Projects
cd peterdoane.surge.sh/
mkdir ~/Projects
md dir ~/Projects
MD dir ~/Projects
rm ~/Desktop/test.js
rm ~/Desktop/tes.js
node ~/Desktop/test.js/
node
atom ~/Desktop/test.js
git --version
which git
brew link --overwrite git
brew link git
brew install git
curl -fsSL https://git.io/vgqFH | sh
git config --global user.email
git config --global user.name
git config --global user.email 'peterdoane@gmail.com'
git config --global user.name 'Peter Doane'
brew upgrade git
brew update
echo $PATH
which echo
which brew
which
echo $EDITOR
atom ~/.config/fish/config.fish
directory
clear
;dfajf
lhkh
jhh
gjhgjh
brew info fish
fish_update_completions
curl -fsSL https://git.io/vgqFU | ruby
cd ..
cd resources
cd Sublime\ Text.app/Contents/
cd Applications
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/install/master/install)
whichbrew
witchbrew
witch brew
git
node-debug longestword22.js
math.floor(5)
(5)math.floor
node-debug mystery2.js
cd desktop
node-debuy mystery2.js
node-debug mystery.js
node-debug -p mystery.js
node-debut -p mystery.js
node-debuy -p mystery.js
node-inspector
sublime text
Package Control.sublime-package
node-inspector mystery.js
node-inpector mystery.js
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
Web Inspector
node-inpsector mystery.js
$ node-debug mystery.js
node-inpspector mystery.js
Node Inspector v0.10.0
node --debug match.js
cd download
cd downloads
