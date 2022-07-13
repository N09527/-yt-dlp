
termux-setup-storage

apt update && apt upgrade -y

pkg install -y ffmpeg

pkg install -y python

python -m pip install --upgrade pip yes

pip install -U yt-dlp

mkdir ~/bin

curl https://raw.githubusercontent.com/N09527/yt-dlp/main/ytdlp -o ~/bin/termux-url-opener

dos2unix ~/bin/termux-url-opener

cd /storage/emulated/0/Download/

mv -f .netrc $HOME

touch $HOME/.netrc

chmod a-rwx,u+rw $HOME/.netrc

