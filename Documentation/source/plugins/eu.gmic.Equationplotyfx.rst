.. _eu.gmic.Equationplotyfx:

G’MIC Equation plot y=f(x) node
===============================

*This documentation is for version 0.3 of G’MIC Equation plot y=f(x).*

Description
-----------

Note :

Use variable X instead of x in the above equation to take care of the X-min/max settings.

Variable c refers to the current channel number.

Variable u refers to a uniformly distributed random value in [0,1.

Reduce resolution to be able to view

separate graph vertices.

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

+-----------------------------------+---------+-------------------+-----------------------+
| Parameter / script name           | Type    | Default           | Function              |
+===================================+=========+===================+=======================+
| F(x) / ``Fx``                     | String  | X*c+10*cos(X+c+u) |                       |
+-----------------------------------+---------+-------------------+-----------------------+
| X-min / ``Xmin``                  | Double  | -10               |                       |
+-----------------------------------+---------+-------------------+-----------------------+
| X-max / ``Xmax``                  | Double  | 10                |                       |
+-----------------------------------+---------+-------------------+-----------------------+
| Resolution / ``Resolution``       | Integer | 100               |                       |
+-----------------------------------+---------+-------------------+-----------------------+
| Channels / ``Channels``           | Integer | 3                 |                       |
+-----------------------------------+---------+-------------------+-----------------------+
| Plot type / ``Plot_type``         | Choice  | Splines           | |                     |
|                                   |         |                   | | **None**            |
|                                   |         |                   | | **Lines**           |
|                                   |         |                   | | **Splines**         |
|                                   |         |                   | | **Bars**            |
+-----------------------------------+---------+-------------------+-----------------------+
| Vertex type / ``Vertex_type``     | Choice  | None              | |                     |
|                                   |         |                   | | **None**            |
|                                   |         |                   | | **Points**          |
|                                   |         |                   | | **Crosses 1**       |
|                                   |         |                   | | **Crosses 2**       |
|                                   |         |                   | | **Circles 1**       |
|                                   |         |                   | | **Circles 2**       |
|                                   |         |                   | | **Square 1**        |
|                                   |         |                   | | **Square 2**        |
+-----------------------------------+---------+-------------------+-----------------------+
| Output Layer / ``Output_Layer``   | Choice  | Layer 0           | |                     |
|                                   |         |                   | | **Merged**          |
|                                   |         |                   | | **Layer 0**         |
|                                   |         |                   | | **Layer 1**         |
|                                   |         |                   | | **Layer 2**         |
|                                   |         |                   | | **Layer 3**         |
|                                   |         |                   | | **Layer 4**         |
|                                   |         |                   | | **Layer 5**         |
|                                   |         |                   | | **Layer 6**         |
|                                   |         |                   | | **Layer 7**         |
|                                   |         |                   | | **Layer 8**         |
|                                   |         |                   | | **Layer 9**         |
+-----------------------------------+---------+-------------------+-----------------------+
| Resize Mode / ``Resize_Mode``     | Choice  | Dynamic           | |                     |
|                                   |         |                   | | **Fixed (Inplace)** |
|                                   |         |                   | | **Dynamic**         |
|                                   |         |                   | | **Downsample 1/2**  |
|                                   |         |                   | | **Downsample 1/4**  |
|                                   |         |                   | | **Downsample 1/8**  |
|                                   |         |                   | | **Downsample 1/16** |
+-----------------------------------+---------+-------------------+-----------------------+
| Ignore Alpha / ``Ignore_Alpha``   | Boolean | Off               |                       |
+-----------------------------------+---------+-------------------+-----------------------+
| Log Verbosity / ``Log_Verbosity`` | Choice  | Off               | |                     |
|                                   |         |                   | | **Off**             |
|                                   |         |                   | | **Level 1**         |
|                                   |         |                   | | **Level 2**         |
|                                   |         |                   | | **Level 3**         |
+-----------------------------------+---------+-------------------+-----------------------+
