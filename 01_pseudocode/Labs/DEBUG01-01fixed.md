// computing the price of an item on sale for 10% off
start
   input origPrice
   discount = price * 0.25
   finalPrice = origPrice - discnt
   output finalPrice
stop


//Below is the fixed code
start
    input origPrice
    discount = \b origPrice\b0  * \b 0.10\b0
    finalPrice = origPrice - \b discount\
    \b0 output finalPrice\par
stop\par
}
 