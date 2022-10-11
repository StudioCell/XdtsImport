# XdtsImport

Imports and timeremap xdts files into Adobe After Effects

After Effectsスクリプトの機能はXDTSファイルで自動TimeRemapです

## Usage
![image](https://user-images.githubusercontent.com/115112505/195144996-5333424f-1a44-4bd8-8f8f-6641ab4203ae.png)

1. The folder structure should be like this with each animation layer with the cell exports. It is not required to have these names be A, B, C, or etc. however they must be named as they are in the xdts timesheet. The names of the cels within the folder do not matter as long as they are in alphabetical order. 

![image](https://user-images.githubusercontent.com/115112505/195145028-d3edf9a3-ffaf-443f-8c56-657b65c8f337.png)

2. The script will pop up a dialog to select the xdts file to import and provides the option to select which timeline to import. 

![image](https://user-images.githubusercontent.com/115112505/195145066-7b82e5eb-625e-4ece-bbf4-2cafe86145f5.png)

3. Each cell animation layer is imported as image sequences and added to a new composition
4. The timeline information from the xdts file is then used to time remap all the frames
