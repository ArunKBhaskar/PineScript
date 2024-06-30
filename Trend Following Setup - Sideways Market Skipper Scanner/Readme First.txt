// Readme First:
// 
// Trend Following Setup - Sideways Market Skipper Scanner
// 
// Long Signal Logic:
//  - Close crosses above the Supertrend.
//  - Add ATR value (with multiplier) to the close to identify the potential sideways or volatility range.
//  - When the price crosses this range, it's considered a breakout.
//  - The ATR should be rising or the volatility is increasing.
// 
// Short Signal Logic:
//  - Close crosses below the Supertrend.
//  - Substract ATR value (with multiplier) to the close to identify the potential sideways or volatility range.
//  - When the price crosses this range, it's considered a breakdown.
//  - The ATR should be rising or the volatility is increasing.
//
// Entry: Enter after the retracement once the signal is generated.