# Kodi-19-for-OpenATV - Dream ONE/TWO

# The purpose is to build , using Gemini feeds, Kodi 19
# as described on IHAD for Dream ONE/TWO under Enigma2. 
# This is new for Dream ONE/TWO Enigma2 due to missing "apt"
# witch is used to install it !

root@dreamone:~# tar -xzf kodi-aarch64-feed.tar.gz -C /
root@dreamone:~# apt-key add keyFile.key
root@dreamone:~# apt-get update && apt-get install enigma2-plugin-extensions-kodimediacenter


