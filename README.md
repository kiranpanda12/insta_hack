# insta_hack
InstaBrute
InstaBrute Two Ways to Brute-force Instagram Account Hacking
what is a InstaBrute
Instagram contained two distinct vulnerabilities that allowed an attacker to brute-force
passwords of user accounts. Combined with user enumeration, a weak password policy
no 2FA nor other mitigating security controls, this could have allowed an attacker to compromise
many accounts without any user interaction, including high-profile ones.
Facebook fixed both issues and awarded a combined bounty of $5.000.
Features
Multi-thread (400 pass/min, 20 threads)
Save/Resume sessions
Anonymous attack through TOR
Check valid usernames
Default password list (best +39k 8 letters)
Check and Install all dependencies
Usage:
git clone https://github.com/thelinuxchoice/instashell
cd instashell
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
Install requirements (Curl, Tor, Openssl):
chmod +x install.sh
sudo ./install.sh
How it works?
Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking.
