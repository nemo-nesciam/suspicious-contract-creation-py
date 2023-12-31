# Tornado Cash Transaction Monitor

This repository contains a Python script designed to monitor Ethereum transactions for activity related to Tornado Cash and detect contract creations. This tool is part of our ongoing effort to enhance blockchain security and transparency, as discussed in our recent blog post.

## About the Project

In light of the vulnerabilities exposed by the OKX DEX hack, as detailed in my [blog post](https://medium.com/@ervin.zubic/unpacking-the-okx-dex-hack-a-detailed-post-mortem-of-the-multi-million-dollar-exploit-18524c90d456), we developed this simple script to help identify potentially suspicious activities involving Tornado Cash. The script fetches recent transactions from the Ethereum blockchain and analyzes them to detect any links to Tornado Cash addresses and subsequent contract creations.

## Getting Started

### Prerequisites

- Python 3.x
- Web3.py
- An Infura API key
- An Etherscan API key

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/nemo-nesciam/suspicious-contract-creation-py
   ```
2. Navigate to the cloned directory:
   ```
   cd suspicious-contract-creation-py
   ```
3. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

### Usage

Run the script using Python3:
```
python3 tornado_cash_agent.py
```

## Contributing

Contributions and suggestions to improve this script are welcome. If you have a different implementation or improvement ideas, please feel free to share them. Your insights are invaluable in making this tool more effective and robust.

## License

This project is licensed under the MIT License - see the [LICENSE](https://en.wikipedia.org/wiki/MIT_License) file for details.

## Acknowledgments

- Special thanks to the contributors and readers of the [blog](https://medium.com/@ervin.zubic/elevate-your-blockchain-security-python-techniques-to-monitor-tornado-cash-and-new-contracts-752320131c4d) for their insights and feedback.
- This project was inspired by the need for enhanced security measures in the blockchain space, as highlighted by the recent [OKX DEX hack](https://medium.com/@ervin.zubic/unpacking-the-okx-dex-hack-a-detailed-post-mortem-of-the-multi-million-dollar-exploit-18524c90d456).
