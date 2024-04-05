**CPP_CellularAutomata_pt2_FlowingCircuitry**
-----------------------
Another File Dump Of OpenGL renderer. Cleaned up some things as well as did some changes in this one. Interesting patterns were seeming to arise from messing with the sine weight of life or death. It Looked To Follow A Stable State In Which Had A General Direction Of Growth. No Individual "Branch" Wants To Connect With Another (As That Will Percolate A New Unstable State) So Thats Why We Are Seeing Many Basically Lines In This Circuit Design.

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/b8738334-f6e0-40c1-b152-699d03abb5cc" alt="Cornstarch <3" width="95" height="89">

 This helped me a lot get a feeling for cosine's usage in all this as well for less bloaty expansions.

----------------------------------------------------------------------------

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/8bf1a4d0-e437-4864-ad6f-c3f9b23776af" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/8bf1a4d0-e437-4864-ad6f-c3f9b23776af" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/8bf1a4d0-e437-4864-ad6f-c3f9b23776af" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/8bf1a4d0-e437-4864-ad6f-c3f9b23776af" alt="Cornstarch <3" width="55" height="49">


**The Breakdown:**

 This Project Works With A 2D Grid Represented Through A Hexagonal Grid. The Grid And Mainly Its Matrix Is Used For Behaivor Between Associated Grid Cells.

 The Grid Cells Are All Represented With Their Own Cell Object In Which Contains Their Respective Hexagonal Vertexes In The Grid As Well As Their Alive State In Which Is Changed From On And Off Depending On Their Neighbor Alive Count As Well As In This Installment Sine Functions In Which Will Initiate Death Waves That Increase In Frequency As The Program Runs For Longer. These Death Waves Give Off Cool Visualizations Of The Cells. Because Of The Logic Defined As Well In Our React Function, We Have Current Cells Will Generate In A Pattern That At Most Entails A Connection Of 3 Alive Neighbors.


<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/06482a50-ddba-44ff-aed5-d97c381d5d43" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/06482a50-ddba-44ff-aed5-d97c381d5d43" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/06482a50-ddba-44ff-aed5-d97c381d5d43" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/06482a50-ddba-44ff-aed5-d97c381d5d43" alt="Cornstarch <3" width="55" height="49">


------------------------------------------------------------------------------

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/9bc5cc1d-cef7-4da0-8c6f-df558dd183e8" alt="Cornstarch <3" width="85" height="69"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/9bc5cc1d-cef7-4da0-8c6f-df558dd183e8" alt="Cornstarch <3" width="85" height="69"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/9bc5cc1d-cef7-4da0-8c6f-df558dd183e8" alt="Cornstarch <3" width="85" height="69"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/9bc5cc1d-cef7-4da0-8c6f-df558dd183e8" alt="Cornstarch <3" width="85" height="69">


**Features:**

![thePrinkle-ezgif com-optimize](https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/7a281e6b-27f8-4e0d-bb50-41a2cb2d8ab1)

<img width="950" alt="image" src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/e93b7b2d-451a-4a08-98e0-5a29fd9cc792">

![ezgif com-optimize (1)](https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/9e55a5de-08c6-4b72-b21f-7c3e48ff35bf)


<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/3dffe04f-4f7e-44e2-bd07-0cd32096ee66" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/3dffe04f-4f7e-44e2-bd07-0cd32096ee66" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/3dffe04f-4f7e-44e2-bd07-0cd32096ee66" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_FlowingCircuitry/assets/76754592/3dffe04f-4f7e-44e2-bd07-0cd32096ee66" alt="Cornstarch <3" width="55" height="49">
