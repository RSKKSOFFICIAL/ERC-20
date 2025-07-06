# ERC-20 Token Project with Foundry

A simple and efficient ERC-20 token implementation using [Foundry](https://book.getfoundry.sh/) for development, testing, and deployment.


## 🔨 Installation

Make sure you have [Foundry installed](https://book.getfoundry.sh/getting-started/installation.html):

```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
````

Clone the repo and install dependencies:

```bash
git clone https://github.com/RSKKSOFFICIAL/ERC-20.git
cd ERC-20
make install
```

## 🚀 Deployment

Update your `.env`:

```env
PRIVATE_KEY=XXXXXXXXX
RPC_URL=http://0.0.0.0:8545
ETHERSCAN_API_KEY=XXXX
```

Run the deploy script:

```bash
make deploy
```

## 🧪 Testing

Run unit tests:

```bash
make test
```

## 📄 License

MIT

Built with ❤️ using Foundry.
