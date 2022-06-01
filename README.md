### Hello, fellow coder!

Wellcome to my personal page. There's nothing special here, I'll just add some shortcuts for my personal works and keep a updated resume of what I do in general. Thanks for reading!

Github suggested these topics, so I'll use it:

- 🔭 I’m currently working on web and mobile development, focused on React and React Native 
- 🌱 I’m currently learning Python, Shell Scripting and Linux. I use linux 95% of the time for years, but I'm still a regular user with just some basic knowledge, so I try to learn a little more everyday and, when there's something I always do in the termianal, I try to write simple scripts for it. Currently I (try to) use Bash, but I'm looking forward to learn more Python and write more complex scripts with less effort haha
- 👯 I’m looking to collaborate on science! Currently I'm in college studying Computer Engineering, so in the next years I'll be doing science, the thing I love the most in this world
- 🤔 I’m looking for help with writing my own projects from ground. It's still a hard challenge for me to start and finish projects on my own, so help in the process is always wellcome!
- 💬 Ask me about JavaSript, React and Frontend, these are the tools I use and know the most. But I can try to help you with Linux and Shell Scripting to, as with some other languages like Java, C and PHP, and some Electronics stuff :D
- 😄 Pronouns: 🇺🇸 They/them; 🇧🇷 Ele/dele, Elu/delu
- ⚡ Fun fact: I want to work with Biomedical Engineering in the future, and build some Cyberpunk like limbs 🧑‍🔬

#### Code shortcuts

- Check if is root
```bash
if [ "$EUID" -ne 0 ]
  then echo "Please run as root"
  exit
fi
```

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

