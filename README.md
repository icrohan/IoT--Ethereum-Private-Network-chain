# IoT + Ethereum Private Network

This project demonstrates the integration of **IoT devices** with a **private Ethereum blockchain network**.  
The setup includes smart contracts, IoT sensor simulation, and blockchain-based data validation.

---

## 🚀 Features
- Private Ethereum blockchain network setup  
- Smart contract deployment for secure IoT data storage  
- Node.js backend for blockchain interaction  
- IoT device simulation using Python/ESP32  
- Frontend (React/HTML) for monitoring real-time data  
- Secure and tamper-proof data logging

---

## 🛠️ Tech Stack
- **Blockchain:** Ethereum (Geth / Ganache / Hardhat)  
- **Smart Contracts:** Solidity  
- **Backend:** Node.js, Express  
- **Frontend:** React.js / HTML / CSS  
- **IoT Devices:** ESP32 / Python simulation  
- **Database:** MongoDB (optional for caching)  

---

## 📂 Project Structure
📦 IoT--Ethereum-Private-Network-chain
┣ 📂 contracts # Solidity smart contracts
┣ 📂 backend # Node.js backend APIs
┣ 📂 frontend # React / HTML dashboard
┣ 📂 iot-scripts # ESP32/Python IoT code
┣ 📜 README.md # Project documentation
┣ 📜 package.json # Dependencies
┗ 📜 hardhat.config.js (if using Hardhat)


---

## ⚡ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/icrohan/IoT--Ethereum-Private-Network-chain.git
cd IoT--Ethereum-Private-Network-chain

Install Dependencies
npm install

3. Start Private Ethereum Network

If using Ganache:

ganache-cli


Or if using Geth:

geth --networkid 1234 --datadir ./data --http --http.port 8545 --http.api eth,web3,personal,net,miner --allow-insecure-unlock

4. Compile & Deploy Contracts
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost

5. Run Backend
cd backend
node server.js

6. Run Frontend
cd frontend
npm start

📡 IoT Device Setup

Connect ESP32 with DHT11/other sensors

Flash the provided script (iot-scripts/esp32.ino)

Sensor data will be published via MQTT/HTTP → Backend → Blockchain

📊 Demo Workflow

IoT sensor collects data (e.g., temperature, humidity)

Data is sent to the backend

Smart contract validates and stores data on the blockchain

Frontend dashboard displays real-time readings with blockchain verification

🔒 Security

Uses private Ethereum network (not public mainnet)

Data integrity ensured via smart contracts

Can be extended with IPFS for secure off-chain storage

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

📜 License

MIT License

👨‍💻 Author

Rohan Immidichetty
Blockchain & IoT Enthusiast 🚀
