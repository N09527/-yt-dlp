
termux-setup-storage

apt update && apt upgrade -y

pkg install -y ffmpeg


pkg install -y python


python -m pip install --upgrade pip

yes | pip install youtube-dl


mkdir -p ~/.config/youtube-dl


mkdir ~/bin


curl https://raw.githubusercontent.com/N09527/youtube-dl/main/ytdl -o ~/bin/termux-url-opener



dos2unix ~/bin/termux-url-opener
