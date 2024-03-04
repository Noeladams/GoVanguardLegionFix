# GoVanguardLegionFix
The fix for errors where screenshooter.py on Kali Linux 2024.1

# The 1st Error #
![image](https://github.com/Noeladams/GoVanguardLegionFix/assets/33500545/26fc382b-c656-48d5-a786-a8e0fab1560a)

- To fix this you have to install selenium but you can't use the latest version.
- Open a terminal and type this:
  <code>sudo pip install -U selenium==3.141.0</code>
 
# The 2nd Error #
![image](https://github.com/Noeladams/GoVanguardLegionFix/assets/33500545/d39c4c1d-134e-4c13-bdb1-f748bc9be71c)

To fix this one again in your terminal:

<code>cd /usr/local/share
sudo wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.7-linux-x86_64.tar.bz2
sudo tar xjf phantomjs-1.9.7-linux-x86_64.tar.bz2
sudo ln -s /usr/local/share/phantomjs-1.9.7-linux-x86_64/bin/phantomjs /usr/local/share/phantomjs
sudo ln -s /usr/local/share/phantomjs-1.9.7-linux-x86_64/bin/phantomjs /usr/local/bin/phantomjs
sudo ln -s /usr/local/share/phantomjs-1.9.7-linux-x86_64/bin/phantomjs /usr/bin/phantomjs
</code>

Now when you run legion you should get a nice screenshot.
![image](https://github.com/Noeladams/GoVanguardLegionFix/assets/33500545/c2180fae-867e-48a7-ab9c-52a39318377b)
