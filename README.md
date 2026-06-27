# base17
import requests

url = "https://api.basescan.org/api"
params = {
    "module": "stats",
    "action": "dailytx",
    "apikey": "YOUR_API_KEY"
}

response = requests.get(url, params=params)
print(response.json())
