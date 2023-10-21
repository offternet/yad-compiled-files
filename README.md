# yad-compiled-files
Yad Gui Compiled Files x64

The above files in yad-compiled-files repository can be used as named or if you want to replace your existing yad file, change the yad-html-X-X  files name to yad

Dependencies that still must be installed are (Plus the dependencies if listed below filename below)

  sudo apt-get install libwebkit2gtk-4.0 libwebkit2gtk-4.0-dev
  sudo apt-get install gstreamer1.0-plugins-good gstreamer1.0-libav


If distored sound:

  sudo apt-get install gstreamer1.0-plugins-bad)


yad13-html-standalone = compiled on Debian 12 x64 system. 
    ./configure --enable-html --standalone


yad13-html-sourceview = compiled on Debian 12 x64 system. 
    ./configure --enable-html ---sourceview --standalone

    sudo apt-get install libgtksourceview-3.0-1 libgtksourceview-3.0-common libgtksourceview-3.0-dev


yad-settings

    cp ./yad-settings  /usr/local/bin (THis is yad-13.0 original file)


yad-tools 

    cp ./yad-tools  /usr/local/bin (THis is yad-13.0 original file)


yad-icon-browser

     cp ./yad-icon-browser  /usr/local/bin (THis is yad-13.0 original file)
