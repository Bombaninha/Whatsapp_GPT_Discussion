# Chrome Driver Installation

1. Download the latest stable version of Google Chrome:

  ```bash
  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

2. Install the downloaded `.deb` package:

  ```bash
  sudo dpkg -i google-chrome-stable_current_amd64.deb
  sudo apt-get install -f
  ```

3. Clean up by removing the downloaded package:

  ```bash
  rm google-chrome-stable_current_amd64.deb
  ```

4. You can obtain the binary location running:
 
  ```bash
  which google-chrome
  ```
