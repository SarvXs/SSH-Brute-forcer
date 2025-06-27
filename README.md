 SSH-Brute-forcer


````markdown
# 🔐 SSH Brute-Forcer

A Python tool to perform SSH brute-force attacks on remote servers using username and password wordlists. Built with `Paramiko` and designed for educational, ethical hacking, and penetration testing use.

---

 ⚙️ Features

- 🧠 Utilizes Paramiko for establishing SSH connections
- 🎯 Option to execute a custom command** after successful authentication
- 🎨 Displays a stylized ASCII banner using **PyFiglet**

---

 📦 Requirements

- Python 3.x
- Install required libraries:

```bash
pip install paramiko pyfiglet
````

---

 🚀 Usage

 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ssh-brute-forcer.git
cd ssh-brute-forcer
```

 2️⃣ Run the Script

```bash
python ssh_brute_forcer.py --users /path/to/users.txt --passes /path/to/passwords.txt --host <remote_host_ip> --port <remote_host_port> --cmd "<command_to_execute>"
```

 📌 Arguments:

| Argument   | Description                                          |
| ---------- | ---------------------------------------------------- |
| `--users`  | Absolute path to file containing usernames           |
| `--passes` | Absolute path to file containing passwords           |
| `--host`   | (Optional) SSH server IP (default: `localhost`)      |
| `--port`   | (Optional) SSH port (default: `22`)                  |
| `--cmd`    | (Optional) Command to execute after successful login |

> 💡 If valid credentials are found, they will be printed and the specified command (if any) will be executed.

---

## ⚠️ Disclaimer

This tool is intended **strictly for educational and authorized penetration testing purposes** only.
⚠️ **Do not** use this tool on systems without **explicit written permission**. Unauthorized access is **illegal** and **unethical**.

---

 📝 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for more details.

---

 👤 Author

Created by [Sarvesvaraan (SarvXs)](https://github.com/SarvXs)
📫 [k.s.sarvesvaraan@gmail.com](mailto:k.s.sarvesvaraan@gmail.com) | [LinkedIn](https://www.linkedin.com/in/sarvesvaraan-k-s-a06a76251)

---


 ✅ Next Steps

- Paste this into your `ssh-brute-forcer/README.md`
- Make sure the file `ssh_brute_forcer.py` and sample `users.txt`, `passwords.txt` exist (if applicable)
- Optionally, add a demo screenshot or terminal GIF for extra impact

Want help generating those sample wordlists or a banner ASCII logo?
```
