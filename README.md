# Polymarket-Manifold paired data

147 pairs of markets with identical resolution criteria on Manifold and Polymarket, hosted 2023-2025. Markets are roughly independent of each other.

* "pair_id": integer assigned to each unique pair
* "market_id_p": Polymarket's slug
* "market_id_m": Contract ID for Manifold API
* "hour": Timestamp in hours
* "expiry": Earliest time of close of markets in pair
* "close_p": Polymarket's final price (last transaction price) for that hour.
* "close_m": Manifold's final price (AMM price) for that hour.
* "outcome": Final resolution, 0 or 1.
* "num_trades_p": Number of trades on Polymarket in that hour.
* "num_trades_m": Number of trades on Manifold in that hour.
