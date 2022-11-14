
# [[WIP][0.90] Karbon Fiber: Version 0.5](https://forum.kerbalspaceprogram.com/index.php?/topic/101360-wip090-karbon-fiber-version-05/)

for KSP 0.90.

![image](https://user-images.githubusercontent.com/39887717/201591449-3195e70f-da5f-413d-9254-88023e1a2013.png)

## by [Nycidian](https://forum.kerbalspaceprogram.com/index.php?/profile/138349-*)

![](https://kerbal-forum-uploads.s3.us-west-2.amazonaws.com/set_resources_17/84c1e40ea0e759e3f1505eb1788ddf3c_default_photo.png)

### Important!

Due to changing file structure, for now you must delete the old KarbonFiber folder before installing a new version.

[Imgur](https://imgur.com/a/oKizk)
[Imgur](https://imgur.com/a/K36yQ)

### License

### Source

### Bundled Mods

* Tech Manager
* Community Tech Tree
* Module Manager
* NearFutureSolar

### Supported Mods

* Remote Tech
* Near Future Propulsion


What is it?

Karbon Fiber started out as a project due to my personal frustration with making smaller satellites. What I wanted to make were structural pieces that were much smaller than those I had, along the way some other ideas came to me as well. At the moment the plan is to make a full set of modular structural pieces as well as some specific sized non structural pieces that look similar and will fit together with the structural pieces. The base building blocks are in the following table.

| Name                   | Nodes (T/S/B) | ~Height  | ~Diameter |
| :--------------------- | :-----------: | :------: | :-------: |
| Karbon Fiber Hex Strut |   1 / 0 / 1   | 93.75 cm | 31.25 cm  |
| DuoTetraHedron         |   4 / 0 / 4   | 58.75 cm | 58.75 cm  |
| TetraHedral            |   3 / 0 / 1   | 37.25 cm | 37.25 cm  |
| Bihedral               |   1 / * / 1   |  39 cm   | 31.25 cm  |

As I am trying to stay semi-realistic I needed a material that was very light but strong and that material is Karbon (Carbon) Fiber. From what I understand carbon fiber depending on how it is made can do some amazing things ending up being stronger and lighter than other materials however the cost is much greater in most cases. however one of the weaknesses is that when used in a manner that it is not designed for carbon fiber often fails easily and spectacularly. That in mind, these pieces are smaller, lighter and much stronger than similar structural pieces. However the cost is much higher and the crash tolerance is very low.

| Cost                      | Mass  | Max Temp | Crash Tolerance | breaking Force | breaking Torque |
| :------------------------ | :---: | :------: | :-------------: | :------------: | :-------------: |
| Modular Girder Segment XL |  25   |  0.375   |      5000       |    80.0 m/s    |       200       | 200 |
| Karbon Fiber Hex Strut    | 2000  |  0.035   |       ???       |    3.0 m/s     |       400       | 600 |

Unique Shape

At some point when I was messing around with model shapes I decided to try making a tetrahedron (why I do not remember) this snowballed into the DuoTetrahedron, taking me many hours to get the alignment right for the point directions that would become the nodes. After which, I remembered that this shape is actually very simple to get simply by propping a cube up on a corner and making an axis from each opposing corner :confused:.

But all was not lost in this process as I got some very interesting regular geometric shapes that align perfectly with my hex struts in the tetrahedral axes. Hence the names don't refer to the shapes but the axes that their nodes face.

Other Features

Besides purely structural pieces I plan on making other parts within the confines of these four shapes.

* Fuel Tanks for the fuels used for low thrust engines
* Ion and monopropelant engines.
* Low thrust RCS
* Expanding sat dish
* Omni-direction antenna
* Expanding Tracking Solar Panel
* Probe Core

Flywheel batteries / SAS / Reaction wheel Combination
As well as the above I will be making adapters that go from the stock larger sizes to this size and possibly in the future and even further smaller parts.

In the future I want to have the Inertial batteries reaction wheel force to be based off of their current charge but this will require me learning a bit about coding in c#/unity.
