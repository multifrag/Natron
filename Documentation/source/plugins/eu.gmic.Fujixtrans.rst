.. _eu.gmic.Fujixtrans:

G’MIC Fuji xtrans node
======================

*This documentation is for version 0.3 of G’MIC Fuji xtrans.*

Description
-----------

Note: The color LUTs used in this section have been designed by Stuart Sowerby. More info at:

Fuji Film Simulation Profiles: http://blog.sowerby.me/fuji-film-simulation-profiles

Authors: Stuart Sowerby and David Tschumperle. Latest update: 2017/13/01.

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

+--------------------------------------------+---------+---------+--------------------------------+
| Parameter / script name                    | Type    | Default | Function                       |
+============================================+=========+=========+================================+
| Preset / ``Preset``                        | Choice  | None    | |                              |
|                                            |         |         | | **None**                     |
|                                            |         |         | | **Astia**                    |
|                                            |         |         | | **Classic Chrome**           |
|                                            |         |         | | **Pro Neg Hi**               |
|                                            |         |         | | **Pro Neg Std**              |
|                                            |         |         | | **Provia**                   |
|                                            |         |         | | **Velvia**                   |
+--------------------------------------------+---------+---------+--------------------------------+
| Strength (%) / ``Strength_``               | Double  | 100     |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Brightness (%) / ``Brightness_``           | Double  | 0       |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Contrast (%) / ``Contrast_``               | Double  | 0       |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Gamma (%) / ``Gamma_``                     | Double  | 0       |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Hue (%) / ``Hue_``                         | Double  | 0       |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Saturation (%) / ``Saturation_``           | Double  | 0       |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Normalize colors / ``Normalize_colors``    | Choice  | None    | |                              |
|                                            |         |         | | **None**                     |
|                                            |         |         | | **Pre-process**              |
|                                            |         |         | | **Post-process**             |
|                                            |         |         | | **Both**                     |
+--------------------------------------------+---------+---------+--------------------------------+
| Preview type / ``Preview_type``            | Choice  | Full    | |                              |
|                                            |         |         | | **Full**                     |
|                                            |         |         | | **Forward horizontal**       |
|                                            |         |         | | **Forward vertical**         |
|                                            |         |         | | **Backward horizontal**      |
|                                            |         |         | | **Backward vertical**        |
|                                            |         |         | | **Duplicate top**            |
|                                            |         |         | | **Duplicate left**           |
|                                            |         |         | | **Duplicate bottom**         |
|                                            |         |         | | **Duplicate right**          |
|                                            |         |         | | **Duplicate horizontal**     |
|                                            |         |         | | **Duplicate vertical**       |
|                                            |         |         | | **Checkered**                |
|                                            |         |         | | **Checkered inverse)**       |
|                                            |         |         | | **Preview split = point(50** |
|                                            |         |         | | **50**                       |
|                                            |         |         | | **0**                        |
|                                            |         |         | | **0**                        |
|                                            |         |         | | **200**                      |
|                                            |         |         | | **200**                      |
|                                            |         |         | | **200**                      |
|                                            |         |         | | **0**                        |
|                                            |         |         | | **10**                       |
|                                            |         |         | | **0**                        |
+--------------------------------------------+---------+---------+--------------------------------+
| Output Layer / ``Output_Layer``            | Choice  | Layer 0 | |                              |
|                                            |         |         | | **Merged**                   |
|                                            |         |         | | **Layer 0**                  |
|                                            |         |         | | **Layer 1**                  |
|                                            |         |         | | **Layer 2**                  |
|                                            |         |         | | **Layer 3**                  |
|                                            |         |         | | **Layer 4**                  |
|                                            |         |         | | **Layer 5**                  |
|                                            |         |         | | **Layer 6**                  |
|                                            |         |         | | **Layer 7**                  |
|                                            |         |         | | **Layer 8**                  |
|                                            |         |         | | **Layer 9**                  |
+--------------------------------------------+---------+---------+--------------------------------+
| Resize Mode / ``Resize_Mode``              | Choice  | Dynamic | |                              |
|                                            |         |         | | **Fixed (Inplace)**          |
|                                            |         |         | | **Dynamic**                  |
|                                            |         |         | | **Downsample 1/2**           |
|                                            |         |         | | **Downsample 1/4**           |
|                                            |         |         | | **Downsample 1/8**           |
|                                            |         |         | | **Downsample 1/16**          |
+--------------------------------------------+---------+---------+--------------------------------+
| Ignore Alpha / ``Ignore_Alpha``            | Boolean | Off     |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Preview/Draft Mode / ``PreviewDraft_Mode`` | Boolean | Off     |                                |
+--------------------------------------------+---------+---------+--------------------------------+
| Log Verbosity / ``Log_Verbosity``          | Choice  | Off     | |                              |
|                                            |         |         | | **Off**                      |
|                                            |         |         | | **Level 1**                  |
|                                            |         |         | | **Level 2**                  |
|                                            |         |         | | **Level 3**                  |
+--------------------------------------------+---------+---------+--------------------------------+
