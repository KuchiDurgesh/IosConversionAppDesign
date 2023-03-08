# IosConversionAppDesign

# Objective:
TO design an Ios application that allows its users to perform following conversions:


Type |Conversions | Formula
--- | --- | --- 
Length | Kilometers to Miles | 1 Km = 0.621371 miles 
Length | Miles to Kilometers | 1 Mile = 1.60934 Kilometers
Length | Yard to Feet | 1 Yard = 3 Feet
Length | Feet to Yard | 1 Feet = 0.33333 Yards
Length | Inches to Centimeters | 1 Inch = 2.54 Centimeters
Length | Centimeters to Inches | 1 Centimeter = 0.3937 Inches
Liquid | Liters to Gallon|  1 Liter = 0.264172 Gallons
Liquid | Gallons to Liters | 1 Gallon = 3.78541 Liters
Liquid | Pints to Gallons | 1 Pint = 0.125 Gallons
Liquid | Gallons to Pints | 1 Gallon = 9.60762 Pints
Liquid| Quarts to Gallons | 1 Quart = 0.20817 Gallons
Liquid | Gallons to Quarts | 1 Gallon = 4.80381 Quarts
Temperature | Fahrenheit to Celsius | 1 Fahrenheit = (Celsius x 1.8) + 32
Temperature | Celsius to Fahrenheit | 1 Celsius = (Fahrenheit - 32)*0.5555
Mass | Kilograms to Pounds | 1 Kg = 2.20462 Pounds
Mass | Pounds to Kilograms | 1 Pound = 0.453592 Kgs
Mass | Ounce to Grams | 1 Ounce = 28.3495 Grams
Mass | Grams to Ounce | 1 Gram = 0.035274 Ounces


# specifications:

1) Develop a tabbar application where each conversion type (for example Length,
Liquid etc) is on its own tab
2) When a tab is selected, your app must show all available conversion options for
that type (for example, in case of Length tab, conversion options are Kilometers to
Miles, Miles to Kilometers etc) in a table view, and must use navigation interface
to transition from table view to actual conversion view.
3) The conversion view should provide a text field where the user can type the value
of required conversion and a button to perform the conversion and show the
output in a label. 
