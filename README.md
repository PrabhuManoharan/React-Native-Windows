# React Native Windows Environment Setup (Typescript)

**Onetime Setup**

1.	Download and Install Visual Studio 2017 [Download Link](https://visualstudio.microsoft.com/downloads/)

2.	Download and Install Visual Studio Code [Download Link](https://code.visualstudio.com/docs/?dv=win)

3.	Download and Install NodeJS [Download Link](https://www.npmjs.com/get-npm)

4.	Install React Native CLI
```
npm i -g react-native-cli
```

5.	Install TypeScript
```
npm i -g typescript
```

6.	Create your project
```
react-native init --version="0.55.0-rc.0" MyApp --template typescript && node MyApp/setup.js
```

7.	Change project directory MyApp
```
cd MyApp
```

8.	Install the React Native Windows CLI Plugin
```
npm i --save-dev rnpm-plugin-windows
```

9.	Run the Windows initialization command
```
react-native windows --windowsVersion 0.55.0-rc.0
```

10.	Open project MyApp.sln file in Visual Studio

11.	Follow the prompts to install the Windows 10 SDK v. 10.0.14393.0

12.	If prompted, select Developer Mode in the Settings window under "Use developer features" and approve the Certificate Installation request. Enable "Developer mode" to allow the custom application to run

13.	Install windows build tools (run in Windows Power Shell)
```
npm i -g --production windows-build-tools
```

14.	Run your application
```
react-native run-windows
```

15.	Prompt Windows PowerShell Installing Certificate: Enter Y to install

16.	Prompt window: Allow Access to windows firewall 
