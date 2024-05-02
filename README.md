[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
# SliceableSkeletalMesh

![screenshot](https://github.com/leejeonghun/SliceableSkeletalMesh/assets/11531985/d82ce978-8290-4682-afd4-a0a9ce23ca78)

This repository contains a proof-of-concept implementation of sliceable SkeletalMesh. Inspired by the invisible SkeletalMesh from [Lyra Starter Game](https://www.unrealengine.com/marketplace/en-US/product/lyra), each corresponding part of the invisible body is filled with StaticMesh which can be sliced utilizing [ProceduralMesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh). Therfore all parts of the body can be sliced, although there are directional restrictions. Also it supports physics(ragdoll) after slicing. It was written using only Blueprint.

All assets used are licensed under the [Epic Content License Agreement](https://www.unrealengine.com/en-US/eula/content).

* Animation sequences from [Lyra Starter Game](https://www.unrealengine.com/marketplace/en-US/product/lyra).
* Character meshes from [UE4 Mannequin: Mobile](https://www.unrealengine.com/marketplace/en-US/product/ue4-mannequin-mobile)

All blueprint files are licensed under the BSD License.
