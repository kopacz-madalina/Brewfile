# Automate macOS Config with a BrewFile
Easily install software and applications you use on your macOS by automating the process with [Homebrew](https://brew.sh) and a brewfile.

A brewfile is a text file that lists the commands Homebrew needs to install specific software and applications. 

### Step 1:
Install [Homebrew](https://brew.sh) by pasting this command in your terminal:

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 2:
Install the applications from the Brewfile using this command in your terminal:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/kopacz-madalina/Brewfile/refs/heads/main/INSTALL.sh)"
```


If everything runs without error, you are good to go!
