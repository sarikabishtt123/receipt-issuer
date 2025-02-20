# receipt-issuer
This project is a Solidity-based smart contract that issues receipts for transactions. It records transaction details such as sender, receiver, amount, and timestamp, allowing users to retrieve receipts later.  
# Smart Contract Receipt Issuer

## Description  
Smart Contract Receipt Issuer is a Solidity-based smart contract that generates and stores receipts for transactions. It records transaction details such as sender, receiver, amount, and timestamp, allowing users to retrieve receipts later.

## Smart Contract Address  
`0xCfDFD758D2ef2c60C639614747f1f2d8db5AbeB7`

## Features  
- Issue receipts for transactions  
- Store sender, receiver, amount, and timestamp  
- Retrieve receipts by ID  
- Track total number of issued receipts  

## How to Use  
1. **Deploy the contract** (if not already deployed).  
2. **Issue a receipt** by calling `issueReceipt(address _receiver)` and sending ETH.  
3. **Retrieve a receipt** using `getReceipt(uint256 _receiptId)`.  
4. **Check total receipts** with `getReceiptCount()`.  

## License  
This project is licensed under the MIT License.  

---
  
🔗 *Feel free to contribute or suggest improvements!* 🚀  
