# Setting up Ruby on Rails for your Windows computer

Go to:

https://rubyinstaller.org/downloads/

On the left hand side, find the following link to download the current stable version:

**=> Ruby 2.4.3-1 (x64)**

After the file has downloaded, double click on the file to start the installation process.

When the installation has completed, open your command prompt (Windows key, `cmd`, hit enter).

Type in `ruby -v` to check that Ruby is installed and working in your terminal/command prompt.

If you see that Ruby is installed, you can download and install Rails by typing in:

```
gem install rails --version=5.1.4 --no-ri --no-rdoc
```

When the installation completes and returns to the prompt, check that it is installed by typing: `rails -v`

