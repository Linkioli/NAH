# NAH

A program that prevents you from typing the word "yeah" by closing the window you currently have active. You maybe asking your self, why? Firstly, "y\*\*h" often serves as meaningless filler, contributing little to whatever conversation you may be having. The over-reliance on this word can lead to stagnant communication, where the participants of the conversation fail to engage with one another on a deeper level. Using "y\*\*h" can hinder one's ability to express themselves creatively and thoughtfully. By challenging your self to avoid this word, you are prompted to formulate more engaging responses, creating a more dynamic and enriching conversation. Furthermore consciously refraining from using "y\*\*h" forces you to be more mindful, encouraging you to be more deliberate and considerate with your interactions. This mindfulness not only improves communications skills but also enhances overall conversational quality, making interactions more meaningful and rewarding. My program, nah, is a form of self-discipline that punishes the user whenever they use this word.

## Requirements
- Only runs on linux
- Install `xdotool` with your system's package manager

## Installation
Simply install with these 4 commands
```
git clone https://github.com/Linkioli/NAH.git
cd NAH
chmod +x nah
sudo cp nah /usr/local/bin
```

# Usage
- The program closes the current active window when you type "yeah", followed by space, or the return key.
- Use `ctrl+shift+q` to stop the program from executing
- `nah` requires root permissions to run, to have it run and execute in the background you can simply just run `sudo -b nohup /usr/local/bin/nah >/dev/null 2>&1`. I'd alias `nah` in your .bashrc to that.
