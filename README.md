# Fixed Income Investing : Duration of the Bonds

During my tenure at an asset management company, I learned that Eurobonds are one of the most popular investment vehicles for investors. Due to tax advantages, investors prefer to invest in Eurobonds with funds in Turkey. Personal and institutional investors have to pay more tax if they directly invest in Eurobonds, whereas if they invest in Eurobonds with mutual or hedge funds, they only need to pay a 10% stoppage on their profits, as opposed to paying more income taxes. Duration is an important metric for investors in bonds, as long-term duration Eurobonds are more volatile than short-term duration bonds. Therefore, investors frequently ask for the duration of the funds. To help investors calculate the duration and duration effect of a bond, I have prepared the script below.

The purpose of this script is to calculate the duration and duration effect of a bond given its coupon rate, maturity, interest rate, coupon frequency, and a specified basis point (bps) scenario. The code uses the numpy_financial and pandas libraries to perform financial calculations and create a dataframe to store the bond's cash flows, present values, and durations. The output of the function includes the bond's present value, Macaulay duration, modified duration, and the duration effect of the specified bps scenario. 


 ![Logo](https://cdn.educba.com/academy/wp-content/uploads/2019/12/Macaulay-Duration-Formula.jpg)
