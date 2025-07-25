### phishing-email-analysis

This project details the step by step process of analysing an email, that is suspected to be a phishing mail. Most of the attacks launched by cyber criminal are through phishing, irrespective of the extended education of individuals on what a phishing email looks like and it's respective characteristics, having a safe system to check makes it easier and faster to detect.

---

### Technology used
- Kali Linux lab
- virustotal.com
- Thunderbird
- Firefox or any browser of your choice
- Emails from phishing pot github repo 

---

### Steps 

#### 1. Create a directory and move into your directory

```bash
mkdir phishinglab && cd phishing lab
```

---

#### 2. Clone the email within your lab directory

```bash
git clone https://github.com/rf-peixoto/phishing_pot.git
```

---

#### 3. You will be using Thunderbird to open the mails, so install thunderbird

```bash
sudo apt update
sudo apt install thunderbird -y
```

---

#### 4. Change directory to _Phishing_pot_ and access the emails listed

```bash
cd phishing_pot && cd email
```

---

#### 5. List the emails and choose one to analyse

```bash
ls
```

---

#### 6. Analyse an email

```bash 
thunderbird sample-272.eml
```

---

#### 7. Copy and scan the url using 

```
https://www.virustotal.com/gui/home/url

```


---


### 📌 Notes

- Always perform email analysis in a secure lab environment like Kali Linux.

- Avoid clicking on suspicious links in a regular browser.

- Consider capturing indicators of compromise (IoCs) such as IP addresses, domains, or attachments for further threat intel.


---

### 🔒 Disclaimer

This project is for educational and research purposes only. Do not engage in any unauthorized analysis or distribution of potentially malicious content outside a secured lab environment.

---
