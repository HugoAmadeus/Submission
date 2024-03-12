# Dicoding Collection Dashboard ✨

## Upload file dashboard.py into google colab

## Install streamlit
```
!pip install streamlit
```
## install localtunnel
```
!npm install localtunnel
```

## Run password for localtunnel
```
import urllib
print("Password/Enpoint IP for localtunnel is: ",urllib.request.urlopen('https://ipv4.icanhazip.com').read().decode('utf8').strip("\n"))
```
## the output will show an IP/password. After that copy the IP/password and paste in URL that will show after the next step
```
Password/Enpoint IP for localtunnel is:  34.73.30.7
```
## Run streamlit app
```
!streamlit run /content/dashboard.py &>/content/logs.txt &
```
## Run local tunnel
```
!npx localtunnel --port 8501
```
## the output will show a link for url. press the link and paste the IP/password earlier for the localtunnel
```
npx: installed 22 in 1.766s
your url is: https://wild-cows-roll.loca.lt
```
## Run Streamlit on Local

## Install Dependencies

Ikuti langkah di bawah ini untuk menjalankan file dashboard
### Aktivkan virtual environtment : 
```bash
conda create --name main-ds python=3.9
conda activate main-ds
```
### Install file requirement
```bash
pip install -r requirements.txt
```
### Run Dashboard
```bash
streamlit run [dashboard.py]
```
#### Reminder: Pastikan path dashboard tersebut sesuai dengan tempat anda menyimpan file tersebut
