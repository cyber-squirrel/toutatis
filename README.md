# Toutatis
<a href="https://www.buymeacoffee.com/megadose" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
### Educational purposes only
Toutatis is a tool that allows you to extract information from instagrams accounts such as e-mails, phone numbers and more

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

## 💡 Prerequisite
   [Python](https://www.python.org/downloads/release/python-370/)
## 🛠️ Installation
```bash
git clone https://github.com/megadose/toutatis.git
cd toutatis/
python3 setup.py install
```
## Example
![](toutatis.gif)

### ⚠️ Warning with the forgotten password function the user is warned.
## 📈 Usage
```bash
python toutatis.py [-h] -u USERNAME -s SESSIONID 
```
## 📚 To retrieve the sessionID
![alt text](https://github.com/megadose/toutatis/blob/master/sessionsId.png?raw=true)
## 📈 Usage with python
```python3 
from toutatis import *
print(recoveryEmail("username")) #To retrieve the email from the forgotten password function ⚠️ the user is alerted !
print(getUserId("username",sessionsId))#To get the UserID
print(getInfo("username",sessionId))#To get the informations not parsed
print(getFullName("username",sessionId))#To get the Full Name
print(getProfilePicture("username",sessionId))#To get the Profile Picture
print(getBiographie("username",sessionId))#To get the Biography
print(extractEmail("username",sessionId))#To get the public email
print(extractPhone("username",sessionId))#To get the public phone number
print(getAllInfos("username",sessionId))#To get parsed informations
```
## 📝 License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.fr.html)
