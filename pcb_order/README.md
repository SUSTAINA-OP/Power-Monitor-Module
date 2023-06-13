<html lang="en">

<head>
	<meta charset="uft-8">
	<meta name="author" content="Masato Kubotera">
    <meta name="description" content="">
</head>

<body>
	<h1>PCB / PCBA Order</h1>
        <p>
            PCB/PCBA ordering were outsourced to <a href="https://jlcpcb.com/">JLCPCB</a>.<br>
            The following files were used to generate files for PCB/PCBA orders.
            <ul>
                <li>Eagle Design File:
                    <a href="https://github.com/JLCPCB/jlcpcb-eagle/blob/master/design%20rules/jlcpcb-2layers.dru">jlcpcb-2layers.dru</a>
                </li>
                <li>Eagle CAM File:
                    <a href="https://github.com/JLCPCB/jlcpcb-eagle/blob/master/cam/jlcpcb_2_layer_v9.cam">jlcpcb_2_layer_v9.cam</a>
                </li>
                <li>BOM/CPL Exporter ULPs:
                    <a href="https://github.com/JLCPCB/jlcpcb-eagle/blob/master/ulps/jlcpcb_smta_exporter.ulp">jlcpcb_smta_exporter.ulp</a>
                </li>
            </ul>
            These are distributed in <a href="https://github.com/JLCPCB/jlcpcb-eagle">github.com/JLCPCB/jlcpcb-eagle</a>.<br>
        </p>
    <h2>PCB Order Specifications</h2>
        <p>           
            <table>
                <tr>
                    <th>PCB Top Image</th>
                    <th>PCB Bottom Image</th>
                </tr>
                <tr>
                    <td><img src="../images/brd_top.png" width="160px"></td>
                    <td><img src="../images/brd_bottom.png" width="160px"></td>
                </tr>
            </table>
            The following  files used to order the PCB and their specifications. 
            <ul>
                <li>Gerber data: <a href="Gerber_date.zip">Gerber_date.zip</a></li>
            </ul>
            <details close>
                <summary>Click for more specifications</summary>
                <ul>                
                    <li>Base Material: FR-4</li>
                    <li>Layers: 2</li>
                    <li>Dimension: 20.32 mm* 12.7 mm</li>
                    <li>Product Type: Industrial/Consumer electronics</li>
                    <li>Different Design: 1</li>
                    <li>Delivery Format: Single PCB</li>
                    <li>PCB Thickness: 1.6</li>
                    <li>Impedance Control: no</li>
                    <li>PCB Color: Red</li>
                    <li>Silkscreen: White</li>
                    <li>Surface Finish: HASL(with lead)</li>
                    <li>Outer Copper Weight: 1 oz</li>
                    <li>Via Covering: Tented</li>
                    <li>Board Outline Tolerance: ±0.2mm(Regular)</li>
                    <li>Confirm Production file: No</li>                
                    <li>Remove Order Number: Yes</li>
                    <li>Deburring/Edge rounding: No</li>
                    <li>Flying Probe Test: Fully Test</li>
                    <li>Gold Fingers: No</li>
                    <li>Castellated Holes: No</li>
                    <li>4-Wire Kelvin Test: No</li>
                    <li>Paper between PCBs: No</li>
                    <li>Appearance Quality: IPC Class 2 Standard</li>
                    <li>Silkscreen Technology: Ink-jet/Screen Printing</li>
                    <li>Package Box: With JLCPCB logo</li>
                </ul>
            </details>
        </p>
    <h2>PCBA Order Specifications</h2>
        <p>
            <table>
                <tr><th>PCBA Image</th></tr>
                <tr><td><img src="pcba.png" width="160px"></td></tr>
            </table>
            The following files used to order the PCBA and their specifications.
            <ul>
                <li>BOM File: <a href="Power-Monitor-Module_top_bom.csv">Power-Monitor-Module_top_bom.csv</a></li>
                <li>CPL File: <a href="Power-Monitor-Module_top_cpl.csv">Power-Monitor-Module_top_cpl.csv</a></li>
            </ul>
            The following parts are attached in the PCBA.
            <table>
                <tr>
                    <th>Part Image</th>
                    <th>Top Designator</th>
                    <th>MFR.Part #</th>
                    <th>JLCPCB Part #</th>
                    <th>Manufacturer</th>
                    <th>Part Detail</th>
                </tr>
                <tr>
                    <td><img src="https://assets.lcsc.com/images/lcsc/900x900/20230203_YAGEO-CC0402JRX7R7BB104_C541464_front.jpg" width="100px"></td>
                    <td>C1,C2</td>
                    <td>CC0402JRX7R7BB104</td>
                    <td><a href="https://jlcpcb.com/partdetail/Yageo-CC0402JRX7R7BB104/C541464">C541464</a></td>
                    <td>Murata Electronics</td>
                    <td>Multilayer Ceramic Capacitor SMD 100nF 16V ±5% X7R 0402</td>
                </tr>
                <tr>
                    <td><img src="https://assets.lcsc.com/images/lcsc/900x900/20221230_Texas-Instruments-INA226AIDGSR_C49851_front.jpg" width="100px"></td>
                    <td>IC1</td>
                    <td>INA226AIDGSR</td>
                    <td><a href="https://jlcpcb.com/partdetail/TexasInstruments-INA226AIDGSR/C49851">C49851</a></td>
                    <td>Texas Instruments</td>
                    <td>Output Current/Voltage/Power Monitor 36V 16-bit MSOP-10</td>
                </tr>
                <tr>
                    <td><img src="https://assets.lcsc.com/images/lcsc/900x900/20230128_prosemi-LMP25NF3P0R002S_C2838967_back.jpg" width="100px"></td>
                    <td>R1</td>
                    <td>LMP25NF3P0R002S</td>
                    <td><a href="https://jlcpcb.com/partdetail/Prosemi-LMP25NF3P0R002S/C2838967">C2838967</a></td>
                    <td>prosemi</td>
                    <td>Current Sensing Resistors SMD 2mΩ 3W ±1% 2512</td>
                </tr>
                <tr>
                    <td><img src="https://assets.lcsc.com/images/lcsc/900x900/20180914_YAGEO-RC0402FR-074R7L_C137962_front.jpg" width="100px"></td>
                    <td>R2,R3</td>
                    <td>RC0402FR-074R7L</td>
                    <td><a href="https://jlcpcb.com/partdetail/Yageo-RC0402FR074R7L/C137962">C137962</a></td>
                    <td>YAGEO</td>
                    <td>Thick Film Resistor SMD 4.7Ω 62.5mW ±1% 0402</td>
                </tr>
            </table>
            These selected parts are listed in <a href="bom.xls">bom.xls</a>.<br>
            <details close>
                <summary>Click for more specifications</summary>
                <ul>                
                    <li>PCBA Type: Economic</li>
                    <li>Assembly Side: Top Side</li>
                    <li>Tooling holes: Added by JLCPCB</li>
                    <li>Confirm Parts Placement: No</li>
                </ul>
            </details>
        </p>
    </body>
</html>
