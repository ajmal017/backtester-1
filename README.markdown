# README

## Description

This project implements a simple event-driven backtester described by Michael Halls-Moore, founder of QuantStart. The reading list is as following,

1. [Event-Driven Backtesting with Python - Part I](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-I)
2. [Event-Driven Backtesting with Python - Part II](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-II)
3. [Event-Driven Backtesting with Python - Part III](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-III)
4. [Event-Driven Backtesting with Python - Part IV](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-IV)
5. [Event-Driven Backtesting with Python - Part V](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-V)
6. [Event-Driven Backtesting with Python - Part VI](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-VI)
7. [Event-Driven Backtesting with Python - Part VII](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-VII)
8. [Event-Driven Backtesting with Python - Part VIII](https://www.quantstart.com/articles/Event-Driven-Backtesting-with-Python-Part-VIII)

Part VIII is more about using Interactive Brokers to implement more live trading system. This is not the focus of this project at this moment.

Building a backtester manually is a good learning experience for quant trading starters. Some references are listed:
- [denhartog/quantstart-backtester](https://github.com/denhartog/quantstart-backtester)
    + Code does not work and has bugs
- [JavierGarciaD/AlgoRepo](https://github.com/JavierGarciaD/AlgoRepo)
    + A SQLite/SQLAlchemy data handler implementation
    + A backtest main class to handle the loop
- [quantopian/zipline](https://github.com/quantopian/zipline)
    + A mature backtesting framework

This project is associated with virtual environment **backtest-env**. Code is not directly copied from QuantStart or any reference, some modifications have been made to make it work.

## Structure

- **fundamental_layer** module contains the basic classes for the backtester implementation.
- **strategies** module contains all the trading strategies for backtesting.
