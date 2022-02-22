# shopping-cart-project

## Installation
In order to use the shopping cart program, you need to set up the environment.

### IF USING THIRD-PARTY PACKAGES, USE A NEW ENV:
conda create -n shopping-env python=3.8 
conda activate shopping-env

To use the active virtual environment, simply run the program using the following command:
python shopping_cart.py

## Usage
This program simulates a checkout process at Lara's One-Stop Shop. Input the product ID's, then click done and you will be able to access your receipt.

It is possible to edit the tax rate to customize it based on the municipality. This is done with the .env file as seen in the example below:

 ### this is the ".env" file...
 
 TAX_RATE=0.0875
