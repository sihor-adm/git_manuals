**_Показати блокові пристрої_**

```bash
sudo lsblk
```

**_On CentOS:_**

```bash
sudo yum install cloud-utils-growpart gdisk
```

**_On Debian:_**

```bash
sudo apt-get install gdisk cloud-guest-utils
```

**_On Arch:_**

```bash
sudo pacman -S gdisk cloud-guest-utils
```

**_Додати місця на диску - обовʼязково вказати номер розділу_**

```bash
sudo growpart /dev/sda 3
```

**_Виконати збільшення розміру розділу_**

```bash
sudo xfs_growfs /
```
