##Not for Linux Building, based on https://github.com/erincatto/Box2D/issues/387
1. git clone https://github.com/senkal/Box2D.git
2. cd Box2D
3. git submodule init
4. git submodule update --recursive
5. mkdir BuildLinux
6. cd BuildLinux
7. cmake ..
8. make

To run Tests: `Testbed/Testbed` inside BuildLinux



##About
Box2D is a 2D physics engine for games.

For help with Box2D, please visit http://www.box2d.org. There is a forum there where you may post your questions.

Please see Building.txt to learn how to build Box2D and run the testbed.

To run the demos, set "Testbed" as your startup project and press F5. Some test bed commands are:
- 'r' to reset the current test
- SPACE to launch a bomb
- arrow keys to pan
- 'x' and 'z' to zoom in/out
- use the mouse to click and drag objects

Please do not submit pull requests with new features. Instead, please file an issue first for discussion. For bugs, I prefer detailed bug reports over pull requests.

Erin Catto
http://www.box2d.org

