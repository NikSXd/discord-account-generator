[![discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)
[![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AcierP)
[![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/downloads/)

# Currently patched and will be rewritten soon
An hcaptcha-solving discord account generator; capable of generating unlocked discord accounts.

**MADE SOLELY FOR EDUCATIONAL PERSONAL PURPOSES**

## Usage

```bash
$ pip install -r requirements.txt
```

## Config
```json
{
    "threads": 100,
    "invite": "discord invite code",
    "names": {
        "static": {
            "enabled": false,
            "name": "acier"
         },
        "random": {
            "enabled": true
         }
    },
    "verification": {
        "phone": {
            "enabled": false,
            "onlinesim_token": "your onlinesim.io token"
        },
        "email": {
            "enabled": true
        }
    }
}
```
