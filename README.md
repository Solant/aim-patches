# aim-patches
Some patches for A.I.M. executable found during reverse engineering

| Description                    | Address | Original Value | Patched Value |
|--------------------------------|---------|----------------|---------------|
| Enable WIN key in game         | 0x4A40D | 10             | 00            |
| Turn on free camera by default (press F3 during flight) | 0x1F805 | 00             | 01            |
