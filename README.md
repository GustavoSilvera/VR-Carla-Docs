# Getting a VR player to work in `Carla 0.9.11`

## NOTE: these are *unfinished* guides for an upcoming CMU `DReyeVR` project
(`DReyeVR` will be released soon, but is currently private)

### Prerequisites
- As expected, you'll need to have a fully-functional [`Carla 0.9.11`](https://carla.org/2020/12/22/release-0.9.11/) build working on your machine
- And you'll need a [UE4+SteamVR-capable](https://www.unrealengine.com/en-US/vr) VR headset 

## Caveats
- All these guides were written with [**UE4 Blueprints**](https://docs.unrealengine.com/en-US/ProgrammingAndScripting/Blueprints/GettingStarted/index.html) in mind, therefore these may not be the most performant methods to achieve VR, but it definitely still works!
    - Blueprints should quickly translate to `C++`, but if you are interested in the exact steps to follow let me know and I'll write new guides for a `C++` actor.
        - (Main benefits of C++ are flexibility and performance)
    - For our `DReyeVR` project, the upcoming documentation includes the `C++` version of these guides but is highly unfinished. If there is demand for these then I'll finish those quickly.
- These guides were written first with Carla `0.9.10@{some commit}` but everything should translate directly to the new `Carla 0.9.11` release.
- There may be typos, these guides have not been updated in a while... happy to take any issues!


## Getting started
1. Follow all the steps in [Setup.md](Setup.md) to get everything working with your headset in VR. 
2. Follow the [VRPlayer.md](VRPlayer.md) guide to create a new vehicle actor that can be used in VR in Carla.

## More questions?
I'll be happy to answer them! 