# IM3DPreview
An initial means of debugging Vector3 and Quaternion math in Sonic Generations via Im3D.

Uses DirectX11 for rendering, set on its own thread so it can run independent of the game.
In the future, a means of overlaying Im3D on top of Gens' window will be ideal, but that will require refitting the DX11 implementation to work with DX9/9Ex. A dedicated window will do fine for now.
