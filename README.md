# Conservation-Mode-for-Linux 🌱

### What is conservation mode ?

`Conservation mode` in Lenovo laptops helps to prolong the life of the battery while plugged in. This mode in energy manager affects the firmware on the battery, and stops the charging when it reaches 60%.
This script will help you control the battery charging and expand 2 more options to stop charging when it reaches 80% and 95% .

### Install

- 1 - Clone this repo
- 2 - cd to the directory which your clone , open terminal from this and type:

```
$ chmod +x maki
```

- 3 - run it 💥

```
$ ./maki
```

# .shellrc

Add something like this in your .shellrc ( such as .zshrc , .bashrc , config.fish , etc. )

```
alias maki='path/to/maki'
```

Every time you want to use it , open the terminal and type `maki` .
