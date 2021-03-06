.. _eu.gmic.Flower:

G’MIC Flower node
=================

*This documentation is for version 0.3 of G’MIC Flower.*

Description
-----------

Author: David Tschumperle. Latest update: 2010/29/12.

Author: David Tschumperle. Latest update: 2010/29/12.

Wrapper for the G’MIC framework (http://gmic.eu) written by Tobias Fleischer (http://www.reduxfx.com).

Inputs
------

+-------+-------------+----------+
| Input | Description | Optional |
+=======+=============+==========+
| Input |             | No       |
+-------+-------------+----------+

Controls
--------

.. tabularcolumns:: |>{\raggedright}p{0.2\columnwidth}|>{\raggedright}p{0.06\columnwidth}|>{\raggedright}p{0.07\columnwidth}|p{0.63\columnwidth}|

.. cssclass:: longtable

+--------------------------------------------+---------+---------+-----------------------+
| Parameter / script name                    | Type    | Default | Function              |
+============================================+=========+=========+=======================+
| Center (%) / ``Center_``                   | Double  | 0       |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Radius / ``Radius``                        | Double  | 70      |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Amplitude / ``Amplitude``                  | Double  | 1       |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Center (%)_2 / ``Center__2``               | Double  | 0       |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Amplitude / Angle / ``Amplitude__Angle``   | Double  | 0       |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Petals / ``Petals``                        | Integer | 6       |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Offset (%) / ``Offset_``                   | Double  | 0       |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Boundary / ``Boundary``                    | Choice  | Mirror  | |                     |
|                                            |         |         | | **Transparent**     |
|                                            |         |         | | **Nearest**         |
|                                            |         |         | | **Periodic**        |
|                                            |         |         | | **Mirror**          |
+--------------------------------------------+---------+---------+-----------------------+
| Output Layer / ``Output_Layer``            | Choice  | Layer 0 | |                     |
|                                            |         |         | | **Merged**          |
|                                            |         |         | | **Layer 0**         |
|                                            |         |         | | **Layer 1**         |
|                                            |         |         | | **Layer 2**         |
|                                            |         |         | | **Layer 3**         |
|                                            |         |         | | **Layer 4**         |
|                                            |         |         | | **Layer 5**         |
|                                            |         |         | | **Layer 6**         |
|                                            |         |         | | **Layer 7**         |
|                                            |         |         | | **Layer 8**         |
|                                            |         |         | | **Layer 9**         |
+--------------------------------------------+---------+---------+-----------------------+
| Resize Mode / ``Resize_Mode``              | Choice  | Dynamic | |                     |
|                                            |         |         | | **Fixed (Inplace)** |
|                                            |         |         | | **Dynamic**         |
|                                            |         |         | | **Downsample 1/2**  |
|                                            |         |         | | **Downsample 1/4**  |
|                                            |         |         | | **Downsample 1/8**  |
|                                            |         |         | | **Downsample 1/16** |
+--------------------------------------------+---------+---------+-----------------------+
| Ignore Alpha / ``Ignore_Alpha``            | Boolean | Off     |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Preview/Draft Mode / ``PreviewDraft_Mode`` | Boolean | Off     |                       |
+--------------------------------------------+---------+---------+-----------------------+
| Log Verbosity / ``Log_Verbosity``          | Choice  | Off     | |                     |
|                                            |         |         | | **Off**             |
|                                            |         |         | | **Level 1**         |
|                                            |         |         | | **Level 2**         |
|                                            |         |         | | **Level 3**         |
+--------------------------------------------+---------+---------+-----------------------+
