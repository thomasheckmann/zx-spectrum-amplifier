# zx-spectrum-amplifier
DIY Amplifier from danish magazine for ZX Spectrum re-created in KiCad as close as possible to original design. This constructions was published in Ny Elektronik issue 3 in 1984.

# Original construction
This is the constructions as published in the magazine in 1984.
<table>
  <tr>
    <td colspan="3" align="center"><img width="819" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/c8b028a6-f614-44fc-b808-dd039d655ebb"></td>
  </tr>
  <tr>
    <td align="center"><img width="715" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/54514dc8-bd44-4938-91c9-286ba0c0a9d1"></td>
    <td align="center"><img width="676" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/7e934ceb-f831-4ad2-8e71-cf435404e2d4"></td>
    <td align="center"><img width="614" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/3fd2755e-88b4-4ba1-beec-95b31a442f02"> </td>
  </tr>
  <tr>
    <td align="center">Schema</td>
    <td align="center">PCB</td>
    <td align="center">Components layout</td>
  </tr>
</table>

# Recreated construction

## First prototype
The main goal was to get the schema redrawn in KiCad and a first try at a PCB, in order to build a version to check if everything works.

| Schema | PCB |
| ------ | --- |
|<img width="400" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/2096266e-0673-4e0c-9e8c-9f8f8056f335">|<img width="400" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/77bb2987-278d-44b2-ba3b-c14338011828">|

First version of PBC was done by manually layout of tracks, according to the original component layouts from the magazine

## Second prototype
As the first version worked perfektly, the main goal was to add relevant plugs for EAR and DC power and resize the board to fit in a suitable enclosure. I even had to create a new footprint for the DC plug, but than again - great learning. Also a small trimmer-pot has been added, in order to be able to recude the noise that is generated in general - it can be skipped and replaced with a small wire, if you wish.

<img width="724" alt="image" src="https://github.com/thomasheckmann/zx-spectrum-amplifier/assets/14136378/e7768d3b-d412-4ba7-94bc-38c5fd2ee56a">

For the track layout, I decided to go with the autoroute plugin - as it makes a nice layout and makes a double sidded print as well.

The new PCB is adjusted to fit in a box of size 84mm X 56mm X 20mm. For example this enclosure box from [Hammond](https://www.hammfg.com/part/1591XXMGY)
