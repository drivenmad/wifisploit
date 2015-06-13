A wireless security tools which makes it easy to crack any wep/wpa, or any other wireless pentesting thing in order to test the security of your wireless network.

---

# Features #
  * ## Automated WPA cracking : ##
    1. Crack with a single or several dico(s), airolib is supported.
    1. Crack with bruteforce using crunch to generate password at runtime.
    1. Pyrit (with cuda if needed) if you want to use it.
    1. Maybe some advanced attacks ( focusing on WPA enterprise ).
  * ## Automated WEP cracking : ##
    1. With a client ( basic arp-request attack ).
    1. Without client ( chochop/fragmentation ).
    1. Withtout aps ( attacking clients ).
    1. Attack other than PTW are available if wanted.
  * ## Automated wifi pentesting ( vulnerabilities ) : ##
    1. Find a ssid ( wait for it or bruteforce it ).
    1. Find a mac ( wait for it or bruteforce it ).
    1. WPA downgrade.
    1. DDoS ( for example with aireplay ).
    1. beacon flood/ auth flood and several mdk3 attacks ...
    1. Rogue ap creation for WPA. ( in progress )
  * ## A very nice user interface : ##
    1. A nice console interface with color which can be used easily without argument ( like a ncurse program ), this interface is already fully functional.
    1. A GUI written in pyqt4 ( not realy functionnal for the moment ).
    1. Commandline arguments can be passed directly to be more quick. ( in progress )

It also detects your wireless devices and can change your mac address if you want ( like in wifite ).

---

It is written in python and pyqt and use powerfull tools like the aircrack-ng suite, wireless tools or mdk3.