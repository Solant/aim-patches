# aim-patches
Some patches for A.I.M. executable found during reverse engineering, target executable version is 1.0.6.3

| Description                    | Address | Original Value | Patched Value |
|--------------------------------|---------|----------------|---------------|
| Enable WIN key in game         | 0x4A40D | 0x10             |  0x00            |
| Turn on free camera by default (press F3 during flight) | 0x1F805 | 0x00             | 0x01            |
