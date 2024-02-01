### Hello, fellow coder!
 
Wellcome to my personal page! I'm a trans non-binary person that spends lots of time either using my computer or playing boardgames with friends haha

[![autocomplete](https://codeium.com/badges/user/abjectly-allowed-mullet-81713/autocomplete)](https://codeium.com/profile/abjectly-allowed-mullet-81713)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dahan-schuster&theme=synthwave)](https://github.com/anuraghazra/github-readme-stats)

There's nothing special here, I'll just add some shortcuts for my personal works and keep a updated resume of what I do in general. Thanks for reading!

Github suggested these topics, so I'll use it:

- 🔭 I’m currently working on web and mobile development, focused on React and React Native
- 🌱 I’m currently learning Shell Scripting and Linux Ricing. I use linux 95% of the time for years, but I'm still a regular user with just some basic knowledge, so I try to learn a little more everyday and, when there's something I always do in the terminal, I try to write simple scripts for it. Currently I (try to) use Bash, but I'm looking forward to learn more Python and write more complex scripts with less effort haha Checkout my [Linux Utils](https://github.com/Dahan-Schuster/linux-utils) and [dotfiles](https://github.com/Dahan-Schuster/dotfiles) repositories!
- 🤔 I’m looking for help with writing my own projects from ground. It's still a hard challenge for me to start and finish projects on my own, so help in the process is always wellcome!
- 💬 Ask me about JavaScript, React, Front-end and Linux Ricing, these are the things I know most. But I can try to help you with Python and Shell Scripting too, as with some other languages like Java, C and PHP, and some Electronics stuff :D
- 😄 Pronouns: 🇺🇸 They/them; 🇧🇷 Ele/dele, Elu/delu
- ⚡ Fun fact: I like to play board-games in my free time, and pretend to code some of them in the future. We can play together in [Board Game Arena](https://boardgamearena.com)

#### Code shortcuts

- Check if is root
```bash
if [ "$EUID" -ne 0 ]
  then echo "Please run as root"
  exit
fi
```

- Ask for confirmation (yes/no)
```bash
# simple way, with read command
read -p "Are you sure? " -n 1 -r
echo   # (optional) move to a new line
if [[ ! $REPLY =~ ^[Yy]$ ]]
then
    exit 1
fi

# sofisticated way, with select command
echo "Do you wish to install this program?"
select yn in "Yes" "No"; do
  case $yn in
    Yes ) make install;;
    No ) exit;;
  esac
done
```

- Linux usage utils
```bash
# see disk usage
du -sh <file or directory>

# real time system monitoring
top

```

- Bcrypt hash for '1234' password (very userful for test users)

    $2a$12$Jn6GUP9IxhsMNNSN5gLiPuOD4YeXP4jGjThLFw532PPqKSzXMl9UC
