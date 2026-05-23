<h1 align="center">
  <br>
  <img width=20% alt="apx hub logo" src="https://github.com/user-attachments/assets/e9d3bcc8-9b4f-4f91-a0a3-35b83ec4b708" />

  <br>
 USB-TO-TTL
  <br>
</h1>

<h4 align="center">
An USB to TTL convertor
</h4>

<div align="center">

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Project](https://img.shields.io/badge/Project-Hardware-yellow.svg)
![Series](https://img.shields.io/badge/Series-Converter-red.svg)
![Devlog](https://img.shields.io/badge/Devlog-13Hr7min-blue)

</div>

<p align="center">
  <a href="#about-the-project">About</a> •
  <a href="#repository-structure">Structure</a> •
  <a href="#schematic-on-easyeda">Schematic</a> •
  <a href="#pcb-on-easyeda">PCB</a> •
  <a href="#cad">CAD</a> •
  <a href="#bill-of-materials">BOM</a> •
  <a href="#license">License</a> •
  <a href="#credits">Credits</a>
</p>

<br>
<br>
<p align=center>
<img src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/Untitled4.png" alt="Banner" width=80%/>
</p>

## About the Project

**USB-TO-TTL** An USB to TTL convertor With CH340C Ic  

### Features

- **Type C port**
- **Auto-Uploading Circuit**
- **Led Indicators**

## Repository Structure

- `src/PCB/` — EasyEDA project sources
- `production/` for fabrication outputs
- `production/pcb/` — PCB fabrication files (Gerbers, BOM, Pick & Place)
- `Render/` for Render Sources


## Schematic on EasyEDA

Source : `src/PCB/Systematic/`  

<img width=90% alt="SCH_Schematic1_1-P1_2026-05-15 (1)" src="https://github.com/user-attachments/assets/0d76197d-0533-412f-92e7-f195808f841f" />



## PCB on EasyEDA

Source : `src/PCB/Board/`  

<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=90% alt="image" src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/PCB1.png" />

</td>
      <td valign="bottom"><img width=120% alt="image" src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/PCB2.png" />

  </table>
</div>
<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img height=200px width=100% alt="image" src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/PCB2D.png" />
</td>
      <td valign="bottom"><img height=200px width=100% alt="image" src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/PCB2D1.png" />
</td>
  </table>
</div>

### Render

<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=100% alt="Render" src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/RENDER.png" />

</td>
      <td valign="bottom"><img width=100% alt="Render" src="https://raw.githubusercontent.com/dushyantyadav0303/USB-TO-TTL-Convertor/refs/heads/main/Images/RENDER1.png" />
  </td>
  </table>
</div>

- source: `src/3D model/`  

## Bill of Materials

Source: `production/pcb/bom.xlsx`

| No. | Quantity | Comment        | Footprint                         | Value |
|-----|----------|----------------|-----------------------------------|-------|
| 1   | 1        | 0.1uf          | C0805                             | 0.1uf |
| 2   | 1        | 0.1uF          | C0805                             | 0.1uF |
| 3   | 1        | 2.54-1*6       | HDR-TH_6P-P2.54-V-M               |       |
| 4   | 1        | 3P 1mm         | HDR-TH_3P-P1.00-V-M               |       |
| 5   | 1        | 5.1k           | R0805_NEW                         | 5.1k  |
| 6   | 1        | 10K            | R0805_NEW                         | 10K   |
| 7   | 1        | 10nF           | C0805                             | 10nF  |
| 8   | 1        | 10uF           | C0805                             | 10uF  |
| 9   | 1        | 330E           | R0805_NEW                         | 330E  |
| 10  | 1        | BC846B         | SOT-23-3_L2.9-W1.3-P1.90-LS2.4-BR |       |
| 11  | 1        | CH340C         | SOP-16_L10.0-W3.9-P1.27-LS6.0-BL  |       |
| 12  | 1        | HT7833         | SOT-89_L4.5-W2.5-P1.50-LS4.2-BR   |       |
| 13  | 1        | LED_0402-R     | LED0805-RD_GREEN_C0805YGC         |       |
| 14  | 1        | TYPE-C-31-M-12 | USB-C_SMD-TYPE-C-31-M-12_1        |       |

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions, improvements, and remixes are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) guide to get started.



## Credits

This project uses:

- **EasyEDA** - PCB design and schematic capture
- **Blender** - Render
- **[@NotARoomba](https://github.com/notaroomba) & [@Gabouin](https://github.com/Gabouin)** - Readme template
