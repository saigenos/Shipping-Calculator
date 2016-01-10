# ShippingCalculator.py
# by Teresa Le
# Uses a function to determine total cost of online order
#########################################################
# Shipping:                                            ##
#########################################################
#   All orders under $20 have a shipping of $5         ##
#   Orders between $20 and $50 have a shipping of $10  ##
#   Orders over $50 have a shipping of $15             ##
#   Orders $100 or more get free shipping              ##
#   NOTE:                                              ##
#       If any order amounts are 0 or less,            ##
#           amount will be 0                           ##
#########################################################

# Define the getTotalCost() function
def getTotalCost(cost):
    """ returns total cost with shipping applied """
    
    # Get shipping

    if cost <= 0:
        shipping = 0
        cost = 0
    elif cost < 20:
        shipping = 5
    elif cost >= 20 and cost < 50:
        shipping = 10
    elif cost < 100:
        shipping = 15
    else:
        shipping = 0
        
    # Calculate total cost
    total = float(cost) + float(shipping)
    
    # return total cost
    return(total)
