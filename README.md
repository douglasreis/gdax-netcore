# gdax-netcore
NetCore based wrapper for the GDAX API (Coinbase Exchange API)

# Notes:

> GDAX primary data sources and servers run in the Amazon US East data center. To minimize latency for API access, we recommend making requests from servers located near the US East data center.
> Some of the methods do not yet have tests and so may not work as expected until a later date. Please raise an issue in github if you want something in particular as a priority.

# Functions to be supported (TBC):
- [ ] Authentication (GET, POST, DELETE supported)
- [ ] Get Account
- [ ] Get Accounts
- [ ] Get Account History
- [ ] Get Holds
- [ ] Place a new Order (limit order)
- [ ] Get an Order
- [ ] Cancel an Order
- [ ] List all open Orders
- [ ] Get Market Data
- [ ] List fills
- [ ] List Products
- [ ] HTTP Error code support
- [ ] List of Currencies - from Accounts
- [ ] Withdrawals - from coinbase accounts / payment methods / crypto account address
- [ ] Deposits - from coinbase accounts / payment methods
- [ ] Transfers - from coinbase accounts
- [ ] Payment methods - coinbase / payment methods
- [ ] Reports
- [ ] Pagination support for all calls that support it.
- [ ] Pagination support for all calls that support it.
- [ ] Sandbox support - *sandbox support was dropped by gdax so this is now redundant*

# Updates
--------
- Initial commit and updated README file

