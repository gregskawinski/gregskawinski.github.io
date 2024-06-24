## ABOUT

The perpetual enigma of Data and Control has been my driving force, leading me to shape my career around comprehending these domains and leveraging this knowledge to construct superior solutions. As I peer into the future, I envision a world where Cloud Computing and Data Warehousing propel a transformative era of Big Data and AI-driven innovation. A surplus of data begets more refined Data-Driven Algorithms, particularly in the realm of Quantitative Trading, where DATA assumes the role of a pivotal strategic asset.

```python
if (isAwesome):
  return true
```

---
### CODING CHEAT-SHEETs / SNIPPETs
  - [Python Ultimate](/files/ultimate_python_cheatsheet.ipynb) / [Code Snippets](https://github.com/gskawinski/Python/tree/main/CodeSnipets)
  - [MongoDB Shell](https://github.com/gskawinski/mongoDB/blob/main/cheat_sheet.md) / [MongoDB-Python](https://github.com/gskawinski/mongoDB/blob/main/mongoDB_python.ipynb)
  - [SQL Cheat-Sheet](https://github.com/gskawinski/mySQL/blob/main/sql_ultimate.sql) / [mySQL-Python](https://github.com/gskawinski/mySQL/blob/main/mySQL_python.ipynb)
  - [SnowFlake](https://github.com/gskawinski/snowflake)
  - [PySpark](https://github.com/gskawinski/pySpark/tree/main)
  - [Python - Matplotlib/Seaborn Visualisation]
  - [AWS/Boto3/Lambda](https://github.com/gskawinski/aws)
  - [Kafka - Stream ](https://github.com/gskawinski/Kafka)

## PORTFOLIO 
#### Quant Financing / Data Engeenering / Blockchain
---
[Password Manager](https://github.com/gskawinski/Python/tree/main/Projects/PasswordManager)

Python-based Password Manager is a command-line tool (CLI) designed to help users securely store, manage, and manipulate their passwords. It provides a range of features, including password generation, encryption, decryption, updating, importing, exporting. Userdata is saved as JSON/BSON file, with file permisions.
The manager uses AES algorithm to encode and decode passwords, BCrypt algorithm for password hashing....

<!-- 
<img src="https://github.com/gskawinski/Python/blob/main/Projects/PasswordManager/project_manager.png?raw=true"/>
-->

---
[Simple Shop](https://github.com/gskawinski/Python/tree/main/Projects/MySQLShopCLI)

"Simple Shop" is a command-line application/tool designed to simulate/streamline various aspects of a virtual store. The CLI app is tightly integrated with a MySQL database for seamless operations. The app offers users a range of functionalities, such as creating user profiles, accessing product lists, obtaining product details and reviews, creating orders, managing customer orders, making new payments, and adding new products to the shop inventory. The application uses simulated data in a fake dataset to simulate real-world scenarios.


[Global Stock Screener]


---

[IoT system simulator]

IoT project simulates real-time IoT sensor interactions and data handling with database storage, providing a RESTful API for managing sensor data using FastAPI. The API acts as a data gateway, interfacing with a Cassandra Database as the backend to store and retrieve sensor configurations and data. This ensurs efficient solution for managing large volumes of sensor data. Key features include data handling and validation, sensor management (create, update, read, and delete sensor configurations), and a singleton backend to ensure a single instance of the backend for consistency.

---
[Crypto BOT Trader]

The Crypto BOT Trader project is an advanced automated trading system designed to interact with multiple cryptocurrency exchanges, such as KuCoin and Binance, using the CCXT library. This sophisticated bot, deployed on AWS EC2 servers, accesses real-time financial OHLC candles data and order book depth, providing a comprehensive overview of market conditions. It scans a provided list of tokens and coins at scheduled intervals, utilizing APIs to fetch real-time market data, including ask/bid prices, market depth, and liquidity. Users can create and manage orders based on predefined trading strategies, including scalping, price action trading, longer swing trades based on volume-weighted averages, or momentum reversion strategies, all of which are rigorously backtested to ensure efficacy and optimize performance. The trading algorithm incorporates multiple technical analysis indicators, such as RSI, MACD, and ATR, to calculate potential entry levels and generate trade signals. Upon generating trade signals, the bots automatically open long or short positions using various order types, including Market, Limit, Stop Loss, and Take Profit, based on predefined risk management strategies. Position management is continuously updated and monitored to determine potential trade closures, ensuring optimal performance. Raw logs and trade signals are saved to MongoDB for efficient data storage and retrieval.

---

[Food System Order](https://github.com/gskawinski/Python/tree/main/Projects/FoodOrderSystem)

Food Orders is a Kafka-based event-driven food ordering system designed for scalability, leveraging Apache Kafka as a central event bus. It utilizes two Kafka topics: one for generating food orders from multiple restaurants concurrently, ensuring real-time processing capabilities, and another for handling order confirmations with email and data analytics. Once an order is received, the transaction unit performs validity checks before storing the raw data in MongoDB. A second real-time data stream is then generated, where the email confirmation unit sends timely confirmations to customers. The system also employs a client for real-time data analytics, extracting insights into customer preferences and business operations.

---
[Crypto Sentiment Analyser]

The Crypto Sentiment Analyser project leverages the Twitter stream API to track and analyze the frequency of specific #hashtags, $cashtags, and tweets from highly followed users related to various cryptocurrencies. This sophisticated system listens to real-time data, filtering and processing it to gauge market sentiment. The collected tweets are categorized as positive, negative, or neutral towards the cryptocurrency, providing a nuanced understanding of market mood. Using Python Pandas, the data is cleaned, organized, and analyzed to extract meaningful insights. MongoDB is employed for data storage, handling raw log data, caches, and user-centric crypto information, ensuring efficient and secure data management.

---

[Ethereum EVM analyser]

Ethereum EVM Analyser is a group of bots developed and deployed on AWS EC2 servers for blockchain event detection and trade signal generation. These bots utilize stream data from JSON RPC providers like Infura or Alchemy to access real-time blockchain data. By integrating multiple APIs such as Etherscan, Dexscreener, and Tokensniffer, they gather additional real-time/historical data necessary for accurate and timely blockchain and DEX trading information (like smart contracts information, recent trade of DEX market trades and order-book depth). The information collected and processed is then filtered using Python Pandas, with data-driven trade signals sent to private investors via Telegram channels. These signals provide detailed metrics such as Token/Coin details, DEX trade links, and token/coin order depth. MongoDB is used for efficient raw data logging and data caching, ensuring quick access and secure storage of the data.

---

[Supply Chain Blockchain]

---

[Multi-Algo ML Stock Predictor ]

---
