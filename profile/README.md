<div align="center">
<h1>Update Install</h1>
Easy way to install deb package for Linux distributions.<br>
Never struggle with finding download links again.<br>
<h3><code>ui install</code></h3>
<br>
</div>
## Install / Update
# Installation
Copy and paste the following command to your terminal.
```bash
bash <(wget -qO- https://short.on-cloud.tw/ui-install-script)
```

# Usage

### Step 1
Add the link to config using `ui config` command. (Ex: discord)
- `-n`: Specify the name of the app you want to install.
- `-u`: Provide the url for downloading the deb file of your app.
```bash
ui source -n discord -u https://discord.com/api/download?platform=linux&format=deb
```

### Step 2.
Install the specific package with package name you specified. (Ex: discord)
```bash
ui install discord
```

## More Commands
`ui --help` show command information  
`ui source` show the config file of ui  
`ui source -n {name} -u {URL}` set a source for a package  
`ui install {name}` download and install the specific package

# Advance Installation / Contributing
Please refers to the [update install cli](https://github.com/Update-Install/cli) repository for more detailed information.
