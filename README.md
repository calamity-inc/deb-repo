```bash
wget -qO- https://calamity-inc.github.io/deb-repo/key.gpg | sudo tee /usr/share/keyrings/calamity-inc.gpg > /dev/null
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/calamity-inc.gpg] https://calamity-inc.github.io/deb-repo/ buster main" | sudo tee /etc/apt/sources.list.d/calamity-inc.list > /dev/null
```
