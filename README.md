# Fixed Income Investing : Duration and Convexity Effect on the Bonds

During my employment at an asset management company, I learned that Eurobonds are one of the most popular investment vehicles for investors. Due to tax advantages, investors prefer to invest in Eurobonds with funds in Turkey. Personal and institutional investors have to pay more tax if they directly invest in Eurobonds, whereas if they invest in Eurobonds with mutual or hedge funds, they only need to pay a 10% stoppage on their profits, as opposed to paying more income taxes. Duration is an important metric for investors in bonds, as long-term duration Eurobonds are more volatile than short-term duration bonds. Therefore, investors frequently ask for the duration of the funds. To improve my financial modelling skills in python, i modelled the duration and duration effect of a bond what if yield of the bond increase scenario. Additionally the relation between modified duration and bond price is not linear so we need to consider to include convexity calculations in our model for accurate results.

*Convexity, a measure of the curvature of the changes in the price of a bond, in relation to changes in interest rates, addresses this error, by measuring the change in duration, as interest rates fluctuate.* **- Investopedia**.

The purpose of this script is to calculate the duration, convexity and their effect of a bond given its coupon rate, maturity, interest rate, coupon frequency, and a specified basis point (bps) scenario. The code uses the numpy_financial and pandas libraries to perform financial calculations and create a dataframe to store the bond's cash flows, present values, and durations. The output of the function includes the bond's present value, Macaulay duration, modified duration, convexity, and the duration and convexity effect of the specified bps scenario. 

*Note : If you are Turkish reader and would like to learn about mathematical modelling of the script, you can find detailed explanation https://www.spl.com.tr/docs/other/eadaaf6f-b394-4c.pdf in this note with CTRL + F "Tahvilde Konveksite".*

If you know easier or simpler model to calculate effect of the duration and convexity and coupon payment structure of the bonds, please let me know.


 ![Logo](https://cdn.educba.com/academy/wp-content/uploads/2019/12/Macaulay-Duration-Formula.jpg)
 ![Logo](https://www.investopedia.com/thmb/sWdOeyNmFkhjEyWUlQtC-MztFGQ=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/DurationandConvexitytoMeasureBondRisk2-0429456c85984ad3b220cd23a760cda5.png)
