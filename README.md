# Local Market Convention

The current process to mark FX Forwards on a corresponding curve is largely a holdover from the days before efficient and liquid derivative markets existed in Mexico. During that time, FX Forwards were the lynchpins of liquidity in FX and interest rate markets.  In recent years however, the market standard for calculating and trading FX Forwards has become to interpolate interest rates and create a synthetic forward curve from Mexico zero rates, USD zero rates, binded with a cross currency basis curve (using applicable FX spot rate). 

Market volumes in FX Forwards (except in the very short term <3M for funding purposes) have dropped sharply, largely losing market share to derivative products. As a result, some tenors in the FX Forward market can go for days and weeks at a time, without any real FX Forward trades executed in the markets.

With most of the liquidity in FX Forwards created via entry into swaps and synthetically created FX Forwards, market data provided on FX Forwards has the potential to be stale and/or inaccurate, except in tenors out to 3m where Forwards remain the benchmarks for interest rate liquidity.

Current valuation methodology can as a result potentially create distortions of P&L from the true market value that can be significant.

Interpolate interest rates and create a synthetic forward curve from Mexico zero rates, USD zero rates, binded with a cross currency basis curve (using applicable FX spot rate).

The proposed methodology suggests that Mexico Products should be marked on a single curve to enhance transparency between products, and avoid potential arbitrage between internal systems. The proposed method would offer more accurate and stable PL calculations as we would be using the most applicable curve across products.

Brokers will send a quote around 3pm each day with mid level pricing to be taken from MXN tiie swaps and basis swaps data and input in Infiniti curves by the back office.
In the short end of the curve (up to 3m nodes) we may back out the Mexico rate by calibrating the implied interest rate from the fx forwards (the most liquid product out to 3m). A MXN TIIE curve will be produced from the combined results.

The corresponding risk exposure will be captured in the MXN swap curve, USD curve, FX spot position, and USD/MXN swap basis curve.

Currently, valuation of the Brazil local interest rate and FX curves are marked or interpolated from a Bank of America Brazil markets contribution Page. This is not the most accurate method of achieving valuation and price integrity as the method does not take into account the most up to date real time information.
Moreover, this method does not take into account the development of products in the Brazil capital markets.  Current valuation methodology therefore potentially can create distortions of P&L from true market value which can be significant.  To date, this has not been a big area of concern as trade volumes and product breadth in BRL denominated assets has been very limited or offset by back to back trades.

Recent developments in the Brazil Market allow us to put forward a methodology used to value Brazilian FX products and interest rate curve risk reflecting the most recent developments in accurate price capture, valuation, and liquidity.

In 2001 Banco Central do Brasil approved greater foreign access to the local BRL curves via the local futures exchange. Prior to this, the only offshore BRL market was the FX NDFs and the implicit BRL rates were set by offshore supply and demand. Once foreigners were allowed to trade the local curves, the offshore BRL began to be priced as a function of the local curve plus a USD basis adjustment.

The most complete and accurate snapshot of the Brazilian Interest Rate curve is reflected in the BM&F futures (The Brazilian Mercantile and Futures Exchange (Bolsa de Mercadorias & Futuros, BM&F is Brazil’s derivative exchange, based in Sao Paulo).

Reference:

https://finpricing.com/FinPricing-ProductBrochure.pdf

