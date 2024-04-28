# StrataMan

Stratagem management system

A companion UI tool to [helldiver-kbd](https://github.com/timonviola/helldiver-kbd) to remap your keys _blazingly fast_.

<img src="misc/screenshot.png" width="400">

# Docs and getting started
This project is a fork of [vial-gui](https://github.com/vial-kb/vial-gui). Meanwhile Vial-gui is a general purpose tool, this project specializes on remapping macros to one specific keyboard for one specific game.


_Prerequisite_
You need to have a vial compatible keyboard e.g.: [helldiver-kbd](https://github.com/timonviola/helldiver-kbd)

Go to Releases and download the latest installer: e.g.'*-win-installer'.

<img src="misc/gif.gif" width="50%">

---


#### Releases

Only Windows is supported.

#### Development

Python 3.6 is recommended (3.6 is the latest version that is officially supported by `fbs`).

Install dependencies:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

To launch the application afterwards:

```
source venv/bin/activate
fbs run
```
