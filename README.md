# Finite-State-Machine-System
This Finite State Machine System is much more professional, and is developed for the programmer who has previous knowledge about the finite state machine concept.

![image](https://github.com/swordmaster003/Finite-State-Machine-System/blob/master/Screenshots/Cover.png)

## Features

- There is a simple tank battle demo in this package,the AI tank is implemented by this finite state machine framework.so you can easy to learn how to use this framework by studying the code in the demo.

  ![image](https://github.com/swordmaster003/Finite-State-Machine-System/blob/master/Screenshots/1.png)

- You can create your own state classes derived from the FSMState class in the framework and override its OnEnter(),OnUpdate() and OnExit() functions if necessary.No more silly enums and switch cases!

- One state linked to another,is created by the transition class,in other words,the transition class link one state to another state called the next state,besides, it hold the next state reference and a list of condition which determine whether to change to next state or not.

  ![image](https://github.com/swordmaster003/Finite-State-Machine-System/blob/master/Screenshots/2.png)

- In this framework,each condition class is separated,and you should create your own condition by Implement the condition interface : IFSMTransitionCondition.

- When you want to link one state to another, you don't need to create the transition by yourself,just to use the CreateFSMStateToAnotherFSMStateTransition API in this framework,all you need to do is to input two state names and some conditions,the framework will create a transition between two states automatically.

- In this package,the readme file described about how to use this framework and how the AI tank in demo be coded in detail.

## Support Unity Versions

5.6.6 or higher

## Online Documents

[Finite State Machine System Manual](https://www.swordmaster.info/documents/unity-assets-documents/finite-state-machine-system-manual-document//)

## Download

You can download this asset from Unity Asset Store:

[Finite State Machine System](https://assetstore.unity.com/packages/tools/ai/finite-state-machine-system-108051?aid=1101l3qJu)
