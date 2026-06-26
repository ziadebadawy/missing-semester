# Introduction to the Shell
>[!Important]
The information compiled applies to **POSIX-Compliant shells** (e.g, `Zsh`, `Bash`) on Linux or other UNIX-like systems. Windows PowerShell will not be covered or compiled here. 
>
> *For windows users<sub>(me)</sub>  it is highly recommended to either flash a Linux distribution ISO or install **W**indows **S**ubsystem for **L**inux (WSL) for a "Proper Shell".*

## What is the Shell?
Computers have a bunch of interfaces you can use to interact with the computer. <u>**G**raphical **U**ser **I**nterfaces</u> (GUIs), where you move your mouse around to interact, are the most common and widely spread example of interfaces. Their popularity stems from ease of use and visual representation.

We also have other types of interfaces that are more recently developed, such as **A**gentic **U**ser **I**nterfaces (AUIs), **V**oice **U**ser **I**nterfaces (VUIs), **A**ugmented/**V**irtual **R**eality **I**nterfaces (AR/VR). 

All of these interfaces are essentially a way for us, the human, to interact with our machine. However, most of these interfaces are specialized by their manufacturer<sup>(sometimes referred to as the author)</sup> to do what they had in mind when they created the interface. In addition to that, it is quite impossible to make two different interfaces interact without having a custom bridge between them

So, **What if you wanted to go one level down?** Where you can write whatever commands you want and be able to chain them however you want. And that is <u>what the shell is.</u> it is the *Textual* Interface to the computer, it is the predecessor to all of the interfaces and is the core language to interact with the computer.

The Shell runs in the context of a Terminal, the terminal is the Window/UI surrounding the shell's interior. It is responsible for displaying the text, Accepting keyboard input, managing colors, fonts, scrolling, copy/paste, and tabs.

