<html lang="en">

<head>
	<meta charset="uft-8">
	<meta name="author" content="Masato Kubotera">
    <meta name="description" content="">
</head>

<body>
    <p><strong>This product is currently under development!</strong></p>
	<h1>Power Monitor Module</h1>
        <p>
            This product is a high-side sensing current/voltage monitor module. The sensing voltage is 0~28V and the current is ±20A. The operating voltage is 2.7~5.5V, and these values are available via I<sup>2</sup>C I/F. The slave address is selectable on the board, and up to 16 modules in total are connected.
        </p>
	<h2>Features Rev. 1</h2>
        <p>
        </p>
    <h3>PCB</h3>
        <p>
            <ul>
                <li>8" x 5" (20.32mm x 12.7mm) PCB layout</li>
                <li>1" (2.54mm) pitch through-holes for pin headers
                    <ul>
                        <li>2 x 5 pin headers - 1
                            <ul>
                                <li><strong>VIN+</strong>: Power input side</li>
                            </ul>
                        </li>
                        <li>2 x 5 pin headers - 2
                            <ul>
                                <li><strong>VIN-</strong>: Load side</li>
                            </ul>
                        </li>
                        <li>1 x 4 pin headers: I<sup>2</sup>C Interface
                            <ul>
                                <li><strong>SDA</strong>: Serial bus data line</li>
                                <li><strong>SCL</strong>: Serial bus clock line</li>
                                <li><strong>VS</strong>: Supply voltage</li>
                                <li><strong>GND</strong>: Common Ground</li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
            <img src="/images/pinout.png" width="320px">
        </p>
    <h3><a href="https://www.ti.com/product/en-us/INA231">Texas Instruments INA231</a></h3>
        <p>
            <ul>
                <li>Bus voltage sensing from 0 V to 28 V</li>
                <li>Power-supply operation: 2.7 V to 5.5 V</li>
                <li>High accuracy:
                    <ul>
                        <li>Gain error: 0.5% (maximum)</li>
                        <li>Offset: 50 μV (maximum)</li>
                    </ul>
                </li>
                <li>Power-supply operation: 2.7 V to 5.5 V</li>
            </ul>
            Note: The I<sup>2</sup>C address of this product is selectable from 16 addresses by the short lands on the board.
        <p>
	<h2>Development Environments</h2>
    <p>
        This product is designed with the following software.
            <ul>
                <li><a href="https://www.autodesk.com/products/eagle/overview">Autodesk Eagle 9.6.2</a></li>
            </ul>
    </p>
    <h2>Repository Contents</h2>
        <p>
            <dl>
                <dt><a href="/images">\images</a></dt>
                <dd>PCB preview images and capture of design screen</dd>
                <dt><a href="/libraries">\libraries</a></dt>
                <dd>Libraries used in Autodesk Eagle design</dd>
                <dt><a href="/pcb_order">\pcb_order</a> </dt>
                <dd>Gerber data and documentation for ordering PCB</dd>
                <dt><a href="/schematic.pdf">schematic.pdf</a></dt>
                <dd>Circuit diagram of this product</dd>
                <dt>*.brd</dt>
                <dd>Board wiring design file by Autodesk Eagle</dd>
                <dt>*.sch</dt>
                <dd>Circuit diagram design file by Autodesk Eagle</dd>
                <dt><a href="/.gitignore">.gitignore</a></dt>
                <dd>A file that tells Git not to track a particular file</dd>            <dt><a href="/LICENSE">LICENSE</a></dt>
                <dd>License to use this product</dd>
            </dl>
        </p>
    <h2>Documentation</h2>
        <p>
            The following documents are available for this product.
            <ul>
                <li><a href=""></a></li>
            </ul>
        </p>
    <h2>References</h2>
        <p>
            This product was designed with reference to the following products.
            <ul>
                <li><a href="https://www.ti.com/product/INA231EVM/part-details/INA231EVM">Texas Instruments INA231EVM: INA231 evaluation module</a></li>
                <li><a href="http://strawberry-linux.com/catalog/items?code=12231">Strawberry Linux INA231: I2C digital current, voltage, and power meter module (up to 20A)</a></li>
            </ul>
        </p>
    <h2>Contact</h2>
        <p>
            If you have any questions, please contact the designer of this product, Masato Kubodera, by <a href="mailto:masatokubotera06@yahoo.co.jp">e-mail</a>.<br>
            E-mail: <a href="mailto:masatokubotera06@yahoo.co.jp">masato.kubotera@sustaina-op.com </a>
        </p>
    <h2>License Information</h2>
        <p>
            This product is open source. Please review the <a href="/LICENSE">LICENSE</a> for license information.<br>
            <br>
            This product by Masato Kubotera is licensed under a <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
        </p>
</body>
</html>
