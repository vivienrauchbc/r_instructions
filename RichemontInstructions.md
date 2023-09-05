# Camera-Calibration & Basler-Grab Instructions

1. Open PyCharm

2.	Open 2 projects:
- Menu – Recent projects:
    - Camera-Calibration
    - basler-grab

3.	First run **Camera-Calibration**:
- main.py – Run
- then you can adjust the focus to your need
- press next (**n**) – then the exposure control algorythm is executed automatically and finishes by itself

4. Now run **basler-grab**:

```sh
python basler_grab_png.py --ring-light-port=COM7 --verbose
```
(available in the program’s README file)

- if the COM7 doesn’t work, open up the Device Manager from the Start menu and search for Ports (COM & LPT) and you can access the port information
- the captured images will be saved in the project's sidebar
