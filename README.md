# eduroam-rpi
/etc/wpa_supplicant/wpa_supplicant.conf settings for eduroam

network={
        ssid="eduroam"
        scan_ssid=1
        key_mgmt=WPA-EAP
        eap=PEAP
        identity="user@domain"
        password="password"
        phase1="peaplabel=0"
        phase2="auth=MSCHAPV2"
}
