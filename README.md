# quantitative-investStrategy
基于北向资金流动的量化交易策略——使用XGBoost机器学习算法

本研究旨在探索基于北向资金流动的量化投资策略，采用xGBoost机器学习算法构建多因子量化选股模型。首先，我们分析了北向资金流动与沪深300指数涨跌的相关性，通过单位根 ADF 检验、格兰杰因果检验和 Pearson 相关性检验验证了北向资金流入与沪深 300ETF 涨跌之间的显著正相关关系。接着，基于北向资金流入构建了指数量化策略，并通过策略模拟验证了其在2018年至 2023年期间的超额收益表现。随后，采用 xGBoost 算法进行多因子选股，通过对 2017年至 2023 年北向资金投资的股票数据进行滚动训练和预测，构建了收益率高于市场指数的投资组合。研究结果显示，所构建的量化选股策略在多数年份中均实现了超额收益，且具有较高的经济效益。通过夏普比率和 R²分数的检验，进一步验证了模型的稳定性和有效性。本研究为境内投资者和机构提供了新的量化投资思路和方法，具有较高的实际应用价值。
