# Getting Started: Environment Setup

- DS-Flex
- 11/02/21


>- 📺[Recording of a Previous Study Group Using this Notebook](https://youtu.be/Zx5e7OT0UJQ)

<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Getting-Started:-Environment-Setup" data-toc-modified-id="Getting-Started:-Environment-Setup-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Getting Started: Environment Setup</a></span><ul class="toc-item"><li><span><a href="#Learning-Objectives" data-toc-modified-id="Learning-Objectives-1.1"><span class="toc-item-num">1.1&nbsp;&nbsp;</span>Learning Objectives</a></span></li></ul></li><li><span><a href="#Environment-Setup" data-toc-modified-id="Environment-Setup-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>Environment Setup</a></span><ul class="toc-item"><li><span><a href="#Env-Setup-Repositories" data-toc-modified-id="Env-Setup-Repositories-2.1"><span class="toc-item-num">2.1&nbsp;&nbsp;</span>Env Setup Repositories</a></span><ul class="toc-item"><li><span><a href="#👨‍🏫-Environment/Tools-Slide-Show" data-toc-modified-id="👨‍🏫-Environment/Tools-Slide-Show-2.1.1"><span class="toc-item-num">2.1.1&nbsp;&nbsp;</span>👨‍🏫 Environment/Tools Slide Show</a></span></li><li><span><a href="#Question-to-the-group:" data-toc-modified-id="Question-to-the-group:-2.1.2"><span class="toc-item-num">2.1.2&nbsp;&nbsp;</span>Question to the group:</a></span></li></ul></li><li><span><a href="#👨‍🏫--Walk-Through-Environment-Set-Up" data-toc-modified-id="👨‍🏫--Walk-Through-Environment-Set-Up-2.2"><span class="toc-item-num">2.2&nbsp;&nbsp;</span>👨‍🏫  Walk-Through Environment Set-Up</a></span></li><li><span><a href="#Environment-Setup-Troubleshooting:--What-if..." data-toc-modified-id="Environment-Setup-Troubleshooting:--What-if...-2.3"><span class="toc-item-num">2.3&nbsp;&nbsp;</span>Environment Setup Troubleshooting:  What if...</a></span><ul class="toc-item"><li><span><a href="#&quot;learn-env&quot;-doesn't-show-up-in-your-list-of-jupyter-notebook-kernels?" data-toc-modified-id="&quot;learn-env&quot;-doesn't-show-up-in-your-list-of-jupyter-notebook-kernels?-2.3.1"><span class="toc-item-num">2.3.1&nbsp;&nbsp;</span>"learn-env" doesn't show up in your list of jupyter notebook kernels?</a></span></li><li><span><a href="#Your-terminal-doesn't-activate-learn-env-automatically" data-toc-modified-id="Your-terminal-doesn't-activate-learn-env-automatically-2.3.2"><span class="toc-item-num">2.3.2&nbsp;&nbsp;</span>Your terminal doesn't activate learn-env automatically</a></span></li><li><span><a href="#You-have-a-mac-that-displays-a-message-about-the-default-shell-being-zsh" data-toc-modified-id="You-have-a-mac-that-displays-a-message-about-the-default-shell-being-zsh-2.3.3"><span class="toc-item-num">2.3.3&nbsp;&nbsp;</span>You have a mac that displays a message about the default shell being zsh</a></span></li><li><span><a href="#I-have-a-new-Mac-with-an-M1-chip?" data-toc-modified-id="I-have-a-new-Mac-with-an-M1-chip?-2.3.4"><span class="toc-item-num">2.3.4&nbsp;&nbsp;</span>I have a new Mac with an M1 chip?</a></span></li></ul></li></ul></li><li><span><a href="#✅-Install-a-Code-Editor" data-toc-modified-id="✅-Install-a-Code-Editor-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>✅ Install a Code Editor</a></span><ul class="toc-item"><li><ul class="toc-item"><li><span><a href="#Once-you've-installed-a-code-editor:" data-toc-modified-id="Once-you've-installed-a-code-editor:-3.0.1"><span class="toc-item-num">3.0.1&nbsp;&nbsp;</span>Once you've installed a code editor:</a></span></li></ul></li></ul></li><li><span><a href="#✅-Install-Jupyter-Notebook-Extensions" data-toc-modified-id="✅-Install-Jupyter-Notebook-Extensions-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>✅ Install Jupyter Notebook Extensions</a></span><ul class="toc-item"><li><ul class="toc-item"><li><span><a href="#Jupyter-Notebook-Extensions-Resources" data-toc-modified-id="Jupyter-Notebook-Extensions-Resources-4.0.1"><span class="toc-item-num">4.0.1&nbsp;&nbsp;</span>Jupyter Notebook Extensions Resources</a></span></li><li><span><a href="#Installation-&amp;-activation" data-toc-modified-id="Installation-&amp;-activation-4.0.2"><span class="toc-item-num">4.0.2&nbsp;&nbsp;</span>Installation &amp; activation</a></span></li><li><span><a href="#Turning-on-extensions" data-toc-modified-id="Turning-on-extensions-4.0.3"><span class="toc-item-num">4.0.3&nbsp;&nbsp;</span>Turning on extensions</a></span></li><li><span><a href="#Recommended-extensions-&amp;-settings" data-toc-modified-id="Recommended-extensions-&amp;-settings-4.0.4"><span class="toc-item-num">4.0.4&nbsp;&nbsp;</span>Recommended extensions &amp; settings</a></span></li></ul></li></ul></li><li><span><a href="#🔬Workflow-for-Labs-🧪" data-toc-modified-id="🔬Workflow-for-Labs-🧪-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>🔬Workflow for Labs 🧪</a></span><ul class="toc-item"><li><span><a href="#On-Illumidesk" data-toc-modified-id="On-Illumidesk-5.1"><span class="toc-item-num">5.1&nbsp;&nbsp;</span>On Illumidesk</a></span></li><li><span><a href="#On-Your-Local-Machine" data-toc-modified-id="On-Your-Local-Machine-5.2"><span class="toc-item-num">5.2&nbsp;&nbsp;</span>On Your Local Machine</a></span></li></ul></li><li><span><a href="#📜Appendix:" data-toc-modified-id="📜Appendix:-6"><span class="toc-item-num">6&nbsp;&nbsp;</span>📜Appendix:</a></span><ul class="toc-item"><li><span><a href="#GitHubDesktop" data-toc-modified-id="GitHubDesktop-6.1"><span class="toc-item-num">6.1&nbsp;&nbsp;</span>GitHubDesktop</a></span></li><li><span><a href="#Showing-Hidden-Files" data-toc-modified-id="Showing-Hidden-Files-6.2"><span class="toc-item-num">6.2&nbsp;&nbsp;</span>Showing Hidden Files</a></span></li></ul></li></ul></div>

## Learning Objectives

- [ ] Walk Through Environment Setup
- [ ] Walk Through `nbextensions` Setup
- [ ] Discuss installing a code editor (like VS Code or SublimeText).
- [ ] Go over the general workflow for tackling labs on Illumidesk and in your local environment
- [ ] Discuss GitHub Desktop: https://desktop.github.com/

# Environment Setup

## Env Setup Repositories

There is a 2-part setup process on Canvas that you will cover environment installation:

1. **Part 1: OS-Specific Set-Up Lessons:**
    - Setting up a Professional Data Science Environment - MacOS  [[Repo Link](https://github.com/learn-co-curriculum/dsc-data-science-env-mac-installation)]
    - Setting up a Professional Data Science Environment - Windows Installation  [[Repo Link](https://github.com/learn-co-curriculum/dsc-data-science-env-windows-installation)]
    
    
2. **Part 2: Installing your `learn-env` environment**:
    - **Setting up a Professional Data Science Environment - Configuring Git and Anaconda** [[Repo Link](https://github.com/learn-co-curriculum/dsc-data-science-env-config)]
    



### 👨‍🏫 Environment/Tools Slide Show

- **There is also a Central Lecturer recording in Topic 01**: 
    - [**🎬 Video: Data Science Environments** [Central Lecturer Lesson]](https://learning.flatironschool.com/courses/4339/pages/video-data-science-environments?module_item_id=276038)
- Environment/Tools Slide Show: 
    - [Flatiron Tools: Illumidesk and Your Local Environment Slides](https://docs.google.com/presentation/d/1RKgrPf99l7m5r0dRvPp4nFzQQ9NgpA082boj7nvzx4M/edit?usp=sharing)


### Question to the group:

- Who has already taken a stab at installing their environment?
    - Success?
    - Errors?

- Anyone (especially windows users) getting an error every time their terminal starts about conda init? 

##  👨‍🏫  Walk-Through Environment Set-Up

    
2. **Setting up a Professional Data Science Environment - Configuring Git and Anaconda**
    - [Repo Link](https://github.com/learn-co-curriculum/dsc-data-science-env-config)

## Environment Setup Troubleshooting:  What if...

### "learn-env" doesn't show up in your list of jupyter notebook kernels?

1. Make sure that had activated your `learn-env` before booting up your notebook server.
2. Make sure that you had entered the following command in your terminal after installing your learn-env
```bash
  python -m ipykernel install --user --name=learn-env```

### Your terminal doesn't activate learn-env automatically


-  Enter the following command into your terminal (Windows Users replace `conda activate` with `source activate`)<br>
```bash
echo "conda activate learn-env" >> ~/.bash_profile```


### You have a mac that displays a message about the default shell being zsh

- [Original Source URL](https://www.howtogeek.com/444596/how-to-change-the-default-shell-to-bash-in-macos-catalina/)
    - From your terminal, run this command:
```bash
chsh -s /bin/bash
```
- To silence the warning message about the default shell has changed, add this command to your `~/.bash_profile`
 ```bash
 export BASH_SILENCE_DEPRECATION_WARNING=1
 ```


### I have a new Mac with an M1 chip?

- I **think** you should be okay with setting up your environment.
- I found [this blog post that you may find helpful](https://vineethbharadwaj.medium.com/setting-up-anaconda-navigator-spyder-jupyter-python-environments-on-macbook-with-m1-chip-for-2a4b9849c1ec)

- While we don't use it until phase 4, here are some guides on install `tensorflow` on the M1 macs:
    - Article: https://www.ai-buzz.com/18-steps-to-install-tensorflow_macos-on-m1-macbook-2020/
    - Video: https://youtu.be/W_Qbrnp6uis

# ✅ Install a Code Editor

- When dealing with code, the default text editing applications included in Windows and MacOS are not ideal (especially on Mac).

#### You should install at least one of the following (but both is better!):
- [ ] [SublimeText](https://www.sublimetext.com/)
    - Great lightweight text editor with some convenient features. 
    - [Official Anaconda Guide on setting up SublimeText](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/sublime/)
- [ ] [VSCode](https://code.visualstudio.com/)
    - Great more full-featured text editor that is bordering on being an IDE (integrated development environment)
    - [Official Anaconda Guide on setting up VSCode](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/python-vsc/)

###  Once you've installed a code editor:

- [ ] Check out your ~/.bash_profile (**we will discuss your .bash_profile again as part of topic 02: bash and git**)


- **BONUS HACK:** Add a "jnb" shortcut that allows you to type `jnb` to open jupyter notebook.
- Add:
  ```alias jnb="jupyter notebook" to your .bash_profile```
  
  - Note: if you are using a different shell besides bash, you will need to find out its equivalent of `.bash_profile` (e.g. .zschrc)
  

# ✅ Install Jupyter Notebook Extensions

### Jupyter Notebook Extensions Resources

- [Documentation](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html)
    
-  [Study Group Video](https://youtu.be/Fl7Xwr_kUkw)

###  Installation & activation
- [Official `nbextensions` Documentation](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html)


#### Installation via Conda
- **The best way to install is via `conda`** (however, windows users sometimes have issues with the conda installation not working properly).
    0. Open your terminal and make sure learn-env is activated.
        - Mac users: `conda activate learn-env`
        - Windows users: `source activate learn-env`

    1. Install the extensions via conda
    ```bash
      conda install -c conda-forge jupyter_contrib_nbextensions
      ```

    2. Activate the extension configurator
    ```bash
    jupyter nbextension enable jupyter_nbextensions_configurator
      ```
 >- Now, boot up jupyter notebook and look for a new tab called (`nbextensions`) on the jupyter file-explorer view. If its there, great! Move on to the "Turning on extensions" section below.
      
      
#### Installing Using Pip    
- **If you have issues installing with conda, install with pip instead ([Documentation](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html)):**
    1. Install extensions
    ```bash
    pip install jupyter_contrib_nbextensions
    ```
    2. Install additional requirements (Install javascript and css file):
    ```bash
    jupyter contrib nbextension install --user
    ```
    3. Activate the extension configurator
    ```bash
    jupyter nbextension enable jupyter_nbextensions_configurator
    ```
>- Now, boot up jupyter notebook and look for a new tab called (`nbextensions`) on the jupyter file-explorer view. If its there, great! Move on to the "Turning on extensions" section below.
      

### Turning on extensions

- **When you boot up jupyter notebook, there should be a new tab at the top called `nbextensions`.** Click on the tab to open the list of available extensions.


- This opens a menu of all of the available extensions with checkboxes to activate them; 
  - ***NOTE: If the list of available notebook extensions is grayed out:***
    - Uncheck "`disable configuration for nbextensions without explicit compatibility (they may break your notebook environment, but can be useful to show for nbextension development)`" at the top of the page next to the search box.
    
    
    
- **Clicking the name of an extension will load its options menu** below the table of extensions. 

### Recommended extensions & settings



- `Table of Contents (2)`: 
    - Clickable sidebar with markdown headers as bookmarks/links.
    - Recommended options:
        - Change `Maximum level of nested sections to display on the tables of contents` to 3.
        -  Check `Display Table of Contents as a sidebar (otherwise as a floating window)`
        - Check `Collapse/uncollapse ToC sections when the collapsible_headings nbextension is used to collapse/uncollapse sections in the notebook. For the inverse behaviour, see collapsible_headings' configuration`


- `Collapsible Headings`: Collapse sections of your notebook using markdown headers.
    - Recommended options: 
        -  Check 'Collapse/uncollapse notebook sections when the ToC2 nbextension is used to collapse/uncollapse sections in the table of contents. For the inverse behaviour, see ToC2's configuration' at towards the bottom of the options.


- `Codefolding`: Lets you collapse function definitions and blocks of code. 


- `Live Markdown Preview`: Shows a preview of what the markdown cell you are editing will look like once you render it with Shift+Enter
    - Recommended options:
        - Check `Show the input & output of markdown cells side-by-side while editing them.`

- `Ruler` (not Ruler in Editor)
- `spellchecker`

<!-- 
- `Variable Inspector` (but warning/caveat): 
    - Lets you see details about all of the variables in your notebook.
    - HUGELY helpful for new coders.
    - Recommended options:
        - `Display window at startup` (for now while you are learning python)
 -->

# 🔬Workflow for Labs 🧪

> - While you CAN work on both Illumidesk and your local computer, I recommend using your local computer for a few reasons:
    - You will have to do the Key Cumulative Labs for each phase on your local computer. 
    - You will get more activity added to your GitHub user profile (the green boxes on your profile page)

## On Illumidesk

- Any code done on Illumidesk will be saved to Illumidesk ONLY.
- In order to save your labs, you will need to follow the instructions on this repo's README: 
    - https://github.com/learn-co-curriculum/dsc-saving-illumidesk-work-to-github
    


## On Your Local Machine

- From Canvas page:(not illumidesk notebook) click on the GitHub icon <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width=30px style="display:inline"> which will open the repo on GitHub.com
- Click on the `Fork` button and copy the url for your fork.
<!-- - Clone lesson to your PC. -->
- Open terminal, navigate to the folder where you want the repo to appear. 
    - e.g. `cd ~/Documents/Flatiron/Phase_1/`
- Clone your fork using the URL you copied from github.
    `git clone <url-of-your-fork>`

- From your terminal, `cd` into the cloned repo's folder.
- Launch jupyter notebook with terminal.
    - `jupyter notebook`


- Complete the lab.
- Save & checkpoint notebook


- Either open a new terminal in the same folder as your repo
    - OR shut down jupyter (using the `Quit` button or `Cntrl+C`) and use the terminal that was running your notebook.
 

#### Save your completed lab by running the following commands


- To save your updated repo:

```bash
## cd to base folder of repo
cd path/to/repo

## Add changes to commit
git add .
# Commit the changes with a  message
git commit -m "your message here"
# Push changes to GitHub profile
git push
```

- Note, you can actually accomplish steps 2 and 3 above in one line of code with 
```bash
git commit -am "message"
git push
```

# 📜Appendix:

## GitHubDesktop

- Consider installing [GitHub Desktop](https://desktop.github.com/)
<img src="https://desktop.github.com/images/github-desktop-screenshot-mac.png" width=50%>

## Showing Hidden Files

- Windows Users: 
    - Turn on View Hidden Files and Folders in your File Explorer menu:
        - [Microsoft Support Article](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-10-97fbc472-c603-9d90-91d0-1166d1d9f4b5#:~:text=Open%20File%20Explorer%20from%20the,folders%2C%20and%20drives%20and%20OK.)
        
    - On the same settings page, also deselect "Hide extensions for known file types and click OK."
    
    
- Mac Users:
    - Use this keyboard shortcut from inside finder:
    `Cmd+Shift+.`
    - Use it again to hide hidden files. 
