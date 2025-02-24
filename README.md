# In Class Problem Set 3

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**
static JComboBox cBox1;
static JComboBox<String> cBox1;
cBox1 = new JComboBox(s1);
cBox1 = new JComboBox<String>(s1);


**What caused it to stop working?**
Java is a strong typed language, it needs info on the type
