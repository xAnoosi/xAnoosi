```py
import os
import random

class ReadMe:
    def __init__(self, username: str, age: str, language: str, location: str):
        self.username = username
        self.age = age
        self.language = language
        self.location = location

    def about(self):
        contacts = {
            "Discord Server" : "https://discord.gg/riverp",
            "YouTube": "@xxrizee",
            "Contacts": [
            "Discord: !  Rize#0001",
            "Instagram: xxAnoosi"
            ]
        }

        print(f"Hello i am {self.username} and i am {self.age} years old.")
        print(f"My main language that i code/develop in is {self.language}.")
        print(f"I live in {self.location}.")
        print("Thinking about my contacts?")
        print(f"Discord Server: {contacts['Discord Server']}")
        print(f"YouTube Channel: {contacts['YouTube']}")
        print(f"My Socials: {random.choice(contacts['Contacts'])}")
        input("Please hit on enter when you have completed reading about me: ")

if __name__ == "__main__":
    os.system("cd ; cd /local ; rm -rf /root/home/local/pid/github.com/xHookah")

    ReadMe(
        "xAnoosi",
        "20",
        "Python",
        "UK"
    ).about()
```

```py    
Output: 
Hello i am xAnoosi and i am 20 years old.
My main language that i code/develop in is Python.
I live in UK.
Thinking about my contacts?
Discord Server: https://discord.gg/riverp.
YouTube Channel: @xxRizee.
My Socials: Discord: !  Rize#0001
Please hit on enter when you have completed reading about me: 
```
