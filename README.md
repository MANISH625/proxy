# proxy
import requests

proxy = {
    "https":"191.252196.160:8080",
    "http":"191.252196.160:8080"}

url = "https://httpbin.org/ip"
r = requests.get(url)
r.json()
