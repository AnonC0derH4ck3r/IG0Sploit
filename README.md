# IG0Sploit by AnonC0derH4ck3r

This tool exploits Tab Nabbing vulnerability on Instagram. The vulnerability is already reported to instagram, but it comes under the exclusions of the Facebook
Bug Bounty Program. However, it can be used to hijack an instagram account using Social Engineer or Phishing Attack.

**Steps to Reproduce:-**
1. You must start ngrok server prior to running this tool by using command **ngrok http 80**.
2. You can install requirements by using **pip install -r requirements.txt**
3. Run the script by using, **python exploit.py**.
4. Provide the main url which the victim will see upon clicking the link in the bio.
5. Provide the redirect url where the parent window (Instagram) will be redirected to.
6. Wait for the script to start the PHP Server. Once the php server has been started, you can copy the ngrok link and paste it into an instagram account's bio.
7. Wait for the victims to open the link via brower by visiting your instagram profile, as soon as they click on your link they'll be tab nabbed to you redirect url.

# Disclaimer:-
Use this tool for educational purpose only. I'll not be held responsibile if you hack accounts using this exploit and get caught without prior consent.

Happy Hacking :-)
