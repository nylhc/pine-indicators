
## pine-indicators
[English](README.md) | [中文](README.zh.md)  

在 TradingView 或技术分析中，指标（Indicators）大致可以根据功能和用途划分为以下几类。 

## 📊 1. **趋势类指标（Trend Indicators）**

用于识别市场当前的趋势方向（上升、下降、震荡）。

**常见例子：**

- Moving Averages（SMA, EMA）
- Supertrend
- ADX（Average Directional Index）
- Ichimoku Cloud
- Parabolic SAR

------

## 🔄 2. **震荡类指标（Oscillators）**

用于识别市场的超买/超卖状态，通常在震荡市场中更有效。

**常见例子：**

- RSI（Relative Strength Index）
- Stochastic Oscillator
- MACD（也可算为趋势+震荡）
- CCI（Commodity Channel Index）
- Ultimate Oscillator

------

## 📉 3. **动量类指标（Momentum Indicators）**

用于测量价格变动的速度和强度。

**常见例子：**

- Momentum Indicator
- ROC（Rate of Change）
- MACD（动量+趋势）
- DMI（Directional Movement Index）

------

## 📈 4. **成交量类指标（Volume Indicators）**

结合价格和成交量分析，识别趋势确认或反转。

**常见例子：**

- OBV（On-Balance Volume）
- Volume Profile
- VWAP（Volume Weighted Average Price）
- MFI（Money Flow Index）

------

## 🔔 5. **信号类指标（Signal/Entry Indicators）**

直接给出买入/卖出信号，通常是基于上述类型的组合逻辑。

**常见例子：**

- Crossover Strategies（均线交叉、MACD交叉）
- Breakout Alerts
- Pivot Point Signals
- Custom Entry Conditions（如突破+动量组合）

------

## 🧠 6. **策略类（Strategy Scripts）**

内置回测功能（`strategy.*` 函数），不仅提示买卖，还能统计盈亏、胜率等。

**常见例子：**

- Trend-following Strategy
- Reversal Strategy
- Scalping Strategy
- Swing Strategy
- Grid or DCA Strategy

------

## 🕰 7. **多周期分析类（Multi-Timeframe Indicators）**

使用高阶/低阶周期的指标进行更全面分析。

**常见例子：**

- MTF RSI
- MTF Supertrend
- MTF Moving Averages

------

## ⚙️ 8. **辅助类（Utility / Overlay Tools）**

不一定直接提供交易信号，但用于图表辅助、可视化、风险管理等。

**常见例子：**

- Session High/Low
- Price Zones / Supply & Demand
- ATR Bands / Volatility Zones
- Risk/Reward Box
- Time Alerts / Event Markers

------

### ✅ 总结图表

| 类型       | 功能                 | 例子                     |
| ---------- | -------------------- | ------------------------ |
| 趋势指标   | 判断趋势方向         | MA, ADX, Supertrend      |
| 震荡指标   | 判断超买/超卖        | RSI, Stochastic          |
| 动量指标   | 判断动能强度         | ROC, MACD                |
| 成交量指标 | 结合价格和量分析     | OBV, VWAP                |
| 信号指标   | 明确买卖点           | Breakout Alert, MA Cross |
| 策略脚本   | 包含回测、盈亏等统计 | Trend Strategy           |
| 多周期分析 | 跨周期判断趋势/信号  | MTF RSI                  |
| 辅助工具   | 提供图表可视化       | ATR Bands, Sessions      |
