## T568A to RJ11 Adapter


## Introduction

The T568A to RJ11 Adapter is a small board that adapts from a standard 8P8C modular jack with [T568A wiring](https://en.wikipedia.org/wiki/ANSI%2FTIA-568#Wiring) to four [RJ11](https://en.wikipedia.org/wiki/Registered_jack#RJ11,_RJ14,_RJ25_wiring) modular jacks.  **_Note: If you use T568B wiring, RJ11 ports 3 and 4 will be swapped, but otherwise this adapter will work fine._**



![Photo of the assembled adapter](https://raw.githubusercontent.com/hharte/T568A_to_RJ11_adapter/main/images/T568A_to_RJ11_adapter.jpg "image_tooltip")



## Status

The Issue 1 boards have been fabricated, hand assembled, and tested to work well.


## Bill of Materials

Online [DigiKey BOM](https://www.digikey.com/en/mylists/list/4QF6TJ3CTL).  [Interactive BOM](https://html-preview.github.io/?url=https://github.com/hharte/T568A_to_RJ11_adapter/blob/main/hardware/bom/ibom.html).


<table>
  <tr>
   <td>Quantity
   </td>
   <td>Reference Designator
   </td>
   <td>Value
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>J1, J2, J3, J4
   </td>
   <td>6P6C<sup>[1]</sup>
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>J5
   </td>
   <td>8P8C
   </td>
  </tr>
</table>


<sup>[1]</sup> Note: 6P6C, 6P4C, or 6P2C connectors may be used.

In addition to the electrical parts in the BOM, the following hardware is required when building the supplied 3D enclosure.


<table>
  <tr>
   <td>Quantity
   </td>
   <td>Description
   </td>
   <td>Link
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>M3x6mm Phillips screws
   </td>
   <td><a href="https://www.amazon.com/Uxcell-a15070200ux0064-Stainless-Phillips-Screws/dp/B012TE12CY">Amazon link</a>
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>M3x15 + 6mm standoffs.
   </td>
   <td><a href="https://www.amazon.com/Hxchen-Female-Hexagon-Standoff-Pillars/dp/B07WR5ZD8G">Amazon link</a>
   </td>
  </tr>
</table>



## Enclosure

A 3D-printable enclosure designed with [FreeCAD](https://www.freecad.org/) is provided.  The PCB mounts to the bottom half of the enclosure, secured with three M3x6mm screws, and two M3x15+6mm threaded standoffs.  The top half of the enclosure is attached to the standoff in the middle of the board using one M3x6mm screw.

