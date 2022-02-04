A fairly simple Pong game with pygame

## Install pygame on M1

First, using Homebrew, install SDL:

```
brew update  
brew install pkg-config xquartz 
brew install sdl2 sdl2_gfx sdl2_image sdl2_mixer sdl2_net sdl2_ttf 
```

Be sure that you are using the arm64 (M1) version of Homebrew.

Create your virtual environment:

```
python3 -m venv venv  
source venv/bin/activate  
```

Then update your pip:

```
pip install —-upgrade pip setuptools  
```

And finally install pygame:

```
pip install wheel  
pip install venvdotapp  
venvdotapp 
pip install pygame 
```