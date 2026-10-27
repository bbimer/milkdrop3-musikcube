# milkdrop3-musikcube

Enhanced MilkDrop 3 visualizer plugin for [musikcube](https://github.com/clangen/musikcube).  
Forked from [clangen/milkdrop2-musikcube](https://github.com/clangen/milkdrop2-musikcube) with MilkDrop 3 / BeatDrop2077 improvements.

### Key Improvements:
- **MilkDrop 3 presets compatibility**: Updated internal engine constants to MilkDrop v3.37.
- **Shader support**: PS 4.0 fallbacks to PS 3.0 execution.
- **Smooth 60 FPS**: Increased frame limit cap from 30 FPS to 60 FPS by default.
- **Always-on-Top**: Toggle window topmost state with `F7`.
- **Quality & Memory**: 64x64 mesh size, 100% canvas stretch, expanded texture cache (up to 2 GB and 3000 images).

### Building
You'll need Visual Studio with C++ tools and the DirectX 9 SDK (or NuGet `Microsoft.DXSDK.D3DX`) to compile this plugin.
