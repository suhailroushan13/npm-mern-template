# npm-mern-template
npm-mern-template is an npm package offering a pre-configured MERN (MongoDB, Express.js, React.js, Node.js) stack template. It streamlines web development by providing a ready-to-use backend server, React frontend, and MongoDB integration. Developers can quickly kickstart their MERN projects and focus on building feature-rich applications.

## Usage

To use the script, follow these steps:

```bash
sudo npm install npm-mern-template
npm-mern-template
```

## Screenshots
### Step 1.
![Screenshot](https://i.imgur.com/LivOtDq.png)

### Step 2.
![Screenshot](https://i.imgur.com/RmWpduO.png)

### Step 3.
```bash
cd server && cd config
nano default.json
```
### Step 4.
#### Fill The Details of the json file
### Note: Don't Start the Server Without Filling Up the default.json
```json
{
    "PORT": 5000,
    "URL": "PROJECT-URL",
    "EMAIL_SMTP": {
        "HOST": "Your Host",
        "AUTH": {
            "USER": "USERNAME",
            "PASS": "PASSWORD"
        },
        "PORT": 465
    },
    "SEND_SMS": {
        "TWILIO_SID": "ACbXXXXXXXXXXXXXXXXXXXXXXXX",
        "TWILIO_TOKEN": "c42XXXXXXXXXXXXXXXXXXXXXXXXXXX",
        "TWILIO_NUMBER": "+14XXXXXXXXXX"
    },
    "DB_URI": "MONGODURI"
}
```
### Step 5.
## To Start The App
```bash
# For React Client
cd client && npm start

#For Express Server
cd server && npm start

```


## Authors

- [Suhail Roushan](https://www.google.com/search?q=Suhail+Roushan)

## 🔗 Links

[![GitHub](https://img.shields.io/badge/github-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/suhailroushan13)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suhailroushan/)

[![twitter](https://img.shields.io/badge/twiiter-00acee?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/0xsuhailroushan)
