<section style="display: flex; flex-direction: column; align-items: center; gap: 16px; margin: 0 auto; text-align: center;">
  
  <!-- Header Image -->
  <a href="https://profile.saputratech.web.id">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./header-dark-new.svg">
      <source media="(prefers-color-scheme: light)" srcset="./header-new.svg" />
      <img 
        alt="SaputraTech | Freelancer · Front-End Developer · UI Designer 🎨" 
        src="./header-new.svg" 
        style="border-radius: 12px; max-width: 896px; width: 100%; height: auto;"
      />
    </picture>
  </a>

<!-- Badges -->
<p align="center">
  <a href="https://profile.saputratech.web.id" target="_blank">
    <img 
      alt="My Website" 
      src="https://img.shields.io/badge/Website-SaputraTech-7733ff?style=for-the-badge&logo=globe&logoColor=ffffff&labelColor=334155"
    />
  </a>
  <a href="https://www.instagram.com/saputratech" target="_blank">
    <img 
      alt="Instagram Profile" 
      src="https://img.shields.io/badge/Instagram-SkartiVPN-7733ff?style=for-the-badge&logo=instagram&logoColor=ffffff&labelColor=334155"
    />
  </a>
  <a href="https://t.me/SkartiVPN" target="_blank">
    <img 
      alt="Telegram Community" 
      src="https://img.shields.io/badge/Telegram-@SkartiVPN-7733ff?style=for-the-badge&logo=telegram&logoColor=ffffff&labelColor=334155"
    />
  </a>
</p>


# Marzban-scripts
Scripts for Marzban

## Installing Marzban
- **Install Marzban with SQLite**:

```bash
sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban.sh)" @ install
```

- **Install Marzban with MySQL**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban.sh)" @ install --database mysql
  ```

- **Install Marzban with MariaDB**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban.sh)" @ install --database mariadb
  ```
  
- **Install Marzban with MariaDB and Dev branch**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban.sh)" @ install --database mariadb --dev
  ```

- **Install Marzban with MariaDB and Manual version**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban.sh)" @ install --database mariadb --version v0.5.2
  ```

- **Update or Change Xray-core Version**:

  ```bash
  sudo marzban core-update
  ```


## Installing Marzban-node
Install Marzban-node on your server using this command
```bash
sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban-node.sh)" @ install
```
Install Marzban-node on your server using this command with custom name:
```bash
sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban-node.sh)" @ install --name marzban-node2
```
Or you can only install this script (marzban-node command) on your server by using this command
```bash
sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban-node.sh)" @ install-script
```

Use `help` to view all commands:
```marzban-node help```

- **Update or Change Xray-core Version**:

  ```bash
  sudo marzban-node core-update
  ```
