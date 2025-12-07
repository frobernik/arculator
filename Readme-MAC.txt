Arculator v2.2 Mac supplement


You will need the following software :

homebrew (recommended)
Xcode

Open a terminal window, navigate to the Arculator directory then enter

./mac-setup.sh
./configure --enable-release-build
make

then ./arculator to run.

mac-setup.sh options are :
  force      : Force reinstall
  use_config : Install if theres no homebrew installed

configure options are :
  --enable-release-build : Generate release build. Recommended for regular use.
  --enable-debug         : Compile with debugging enabled.
  --disable-podules      : Don't build external podules

The options are in the menu bar in the Mac port. Right-click on the main window when mouse is not captured.

