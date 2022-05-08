From a clean slate (empty Homebrew) run the following commands:

::

    brew update
    brew install python@3.9
    brew install pkg-config xquartz
    brew install sdl2 sdl2_gfx sdl2_image sdl2_mixer sdl2_net sdl2_ttf

    python3 -m venv pygame2
    source ./pygame2/bin/activate

    pip install --upgrade pip setuptools

    pip install wheel
    pip install venvdotapp
    venvdotapp

    pip install pygame


**Note**: You don't have to have an empty Homebrew. Just be sure that the packages are installed.

----

Next, just clone this repository and issue the following commands:

::

    cd solarwolf
    python solarwolf.py

Enjoy!
