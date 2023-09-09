# YAPSC:10V firmware

<table>
    <tr>
        <td colspan="2" align="center"><strong>Прошивки для YAPSC:10V</strong></td>
    </tr>
    <tr>
        <td>btldr.hex</td><td>Ingenia бутлоадер для dsPIC30</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.7_orig.hex</td><td>Оригинальная прошивка без конфигурационных бит</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.7_with_cnf.hex</td><td>Прошивка с добавленными конфигурационными битами</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.7_with_btldr.hex</td><td>Прошивка с добавленным бутлоадером и конфигурационными битами</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.8_U1BRG_fix.hex</td><td>Прошивка без конфигурационных бит, с исправлением скорости UART</td>
    </tr>
        <tr>
        <td>YAPSC_10v_2.0.8_with_cnf_U1BRG_fix.hex</td><td>Прошивка с добавленными конфигурационными битами, с исправлением скорости UART</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.8_with_btldr_U1BRG_fix.hex</td><td>Прошивка с добавленным бутлоадером и конфигурационными битами, с исправлением скорости UART</td>
    </tr>
</table>


Прошивки **YAPSC_10v_2.0.7_orig.hex** и **YAPSC_10v_2.0.8_U1BRG_fix.hex** не имеют конфигурационных бит, прошивать только через бутлоадер.

Остальные прошивки прошиваются программатором.

В прошивках версии 2.0.8 исправлена скорость UART, значение U1BRG изменено на 31(В прошивках версии 2.0.7 U1BRG = 30).

Для прошивок версии 2.0.7 фактическая скорость UART составляет 59435 бод, скорость завышена на 3.19% от заданной 57600 бод.</br>

Для прошивок версии 2.0.8 фактическая скорость UART составляет 57578 бод, скорость занижена на 0.04% от заданной 57600 бод.

## Внимание!
Только прошивки **btldr.hex** и **YAPSC_10v_2.0.7_orig.hex** являются оригинальными прошивками без изменений с сайта www.max-mod-shop.com .
Все остальные прошивки созданы путём прямого редактирования оригинальной прошивки, без перекомпиляции исходников, используйте данные прошивки на свой страх и риск.


## English
<table>
    <tr>
        <td colspan="2" align="center"><strong>Firmware files for YAPSC:10V</strong></td>
    </tr>
    <tr>
        <td>btldr.hex</td><td>Ingenia bootloader for dsPIC30</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.7_orig.hex</td><td>Original firmware without configuration bits</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.7_with_cnf.hex</td><td>Firmware with added configuration bits</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.7_with_btldr.hex</td><td>Firmware with added bootloader and configuration bits</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.8_U1BRG_fix.hex</td><td>Firmware without configuration bits, with UART speed fix</td>
    </tr>
        <tr>
        <td>YAPSC_10v_2.0.8_with_cnf_U1BRG_fix.hex</td><td>Firmware with added configuration bits, with UART speed correction</td>
    </tr>
    <tr>
        <td>YAPSC_10v_2.0.8_with_btldr_U1BRG_fix.hex</td><td>Firmware with added bootloader and configuration bits, with UART speed fix</td>
    </tr>
</table>


Firmware files **YAPSC_10v_2.0.7_orig.hex** and **YAPSC_10v_2.0.8_U1BRG_fix.hex** do not have configuration bits; flash only via bootloader.

The remaining firmware files is flashed by the programmer.

In firmware version 2.0.8, the UART speed is fixed, the value of U1BRG is changed to 31 (In firmware version 2.0.7, U1BRG = 30).

For firmware version 2.0.7, the actual UART speed is 59435 baud, the speed is overestimated by 3.19% of the specified 57600 baud.

For firmware version 2.0.8, the actual UART speed is 57578 baud, the speed is reduced by 0.04% from the specified 57600 baud.


## Attention!

Only the **btldr.hex** and **YAPSC_10v_2.0.7_orig.hex** files are original firmware files without changes from the site www.max-mod-shop.com .
All other firmware files were created by directly editing the original firmware files, without recompiling the sources, use these firmware files at your own peril and risk.
