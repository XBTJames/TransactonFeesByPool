# TransactonFeesByPool
Jupyter Notebook that produces some metrics and visualizations for Bitcoin transaction fees, specifically the distribution of fees by pool

This data was compliled via a selfhosted-instance of Mempool.space on an Umbrel. It is possible to use the https://mempool.space/ API, but I will warn you that it is specifically not designed for this kind of bulk block information download.

From the mempool.space API Documentation: "To return data for more than 10 blocks, consider becoming an enterprise sponsor."

If you are going to go against my advice and hit the https://mempool.space/ API for the block information, please kindly un-comment the sleep(5) functions as to space your API calls out and not overwhelm the server.
