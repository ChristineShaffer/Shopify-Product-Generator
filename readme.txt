    Store Product Generator - Creates bulk shopify products for inputted 
    municipalities and product variants.
    Copyright (C) 2016 Christine Shaffer

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


WHAT THIS PROGRAM DOES

This program auto-generates Shopify.com-compatible products in csv format
for the array of available products in the econometrics.ca store located
at store.econometrics.ca


USAGE

Create csv of municipalities/regions and their associated pricing level 
('small', 'medium', 'large') based off population.  First column should 
contain municipality/region name, while the second should contain one of the
pricing levels OR an associated population.

Create template of each product/variant in Shopify.com product csv input
format for 'Edmonton'.  Name file template.csv
*Inputted template must have exact name

Place both of these in /inputs/ and run program.


OUTPUTS

Generated-Shopify-Products.csv - All generated products in 
			         Shopify.com-compatible csv format
