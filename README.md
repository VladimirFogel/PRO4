# PRO4 - SSH Playground

## Prerequisites

Before starting make sure you have the following programs installed.
* git
* pip
* python3-virtualenv

## Installation

Clone this repository using:
```
git clone https://github.com/VladimirFogel/PRO4.git
```
Navigate to the cloned directory using:
```
cd PRO4
```
Install the required packages using:
```
pip install -r requirements.txt
```

## Table of Contents
+ CVE-2020-14145 -  AutoAdd Policy Attack
+ CVE-2018-10933 -  LibSSH Attack
+ CVE-2018-7750 -   Denial of Service Attack

## Usage

Open the folder of the attack you want to simulate.
Follow instructions for the attack given in the folder.

## Contribute

To make sure that your Git commits are properly attributed to you, you should set your Git name, email, and safe directory using the following commands:
```
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global --add safe.directory /path/to/PRO4
```
Make sure to replace "Your Name", "you@example.com", and "/path/to/PRO4" with your own name, email address, and the path to the PRO4 directory.

If you are still having issues, try setting the SSH URL for your Git remote manually by running the command:
```
git remote set-url origin git@github.com:Mrgoodwill/PRO4.git 
```
(replace "Mrgoodwill" and "PRO4" with your own GitHub username and repository name).

Check that your SSH key is being used by Git. To do this, run the command:
```
ssh -T git@github.com
```
This should return a message that starts with
"Hi username! You've successfully authenticated...". If you see an error message instead, it means that your SSH key is not being used by Git.

## External Links

### Zeitdokumentation:
* https://docs.google.com/spreadsheets/d/1mwbqgdCWlFgcgNUbmIdQwrI29UEeELdBSZa5vNcmR4U/edit?usp=sharing

### Jira Board:
* https://pro4projektmanagement.atlassian.net/jira/software/projects/PRO4/boards/1

### SSH Schwachstellen Template:
* https://forms.gle/CfSYcY2WqVsZDadf7
