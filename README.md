# base666666h
Python Snippet: Calculate Tx Fee
receipt = w3.eth.get_transaction_receipt(tx_hash)
fee = receipt.gasUsed * w3.eth.gas_price
