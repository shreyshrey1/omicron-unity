# omicron-unity
A Unity3D package for using the Omicron input library for virtual reality devices.

The Omicron library provies access to a variety of input devices mostly used in immersive environments. The library is available at https://github.com/uic-evl/omicron.

This Unity3D package has two primary functions. The first is to provide access to these input devices by connecting to an Omicron oinputserver and receiving a stream of events. The scripts provided will convert the events for use within Unity.

The second function of this package is to provide a series of tools to aid in the development of Unity applications for virtual reality environments such as the Electronic Visualization Laboratory's CAVE2(TM).

## Installation

This repository is a wrapper for the main Omicron Unity module available at https://github.com/arthurnishimoto/module-omicron. Download from here for use as a Unity example project. Use the previous link for use as a submodule of an existing project.

If you are cloning using Git, remember to remember to use the recursive flag:

`git clone --recursive https://github.com/arthurnishimoto/omicron-unity.git`

Alternativly when available, you can use one of the .unitypackage release files.

CAVE2 is a trademark of the University of Illinois Board of Trustees