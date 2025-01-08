# 🚀 **Check-Token-Live**  

**Check-Token-Live** is a sleek and high-performance terminal application built in **Rust** to track live cryptocurrency token prices. It fetches real-time data using the **PumpFun API**, features an interactive UI powered by **ratatui**, and provides candlestick charts generated with **cli-candlestick-chart** for advanced market analysis.  

🔗 **Monitor any token** by simply entering its address during runtime, all from the comfort of your terminal.  

---

## 🌟 **Features**  

- **⚡ Real-Time Price Updates**: Stay updated with live cryptocurrency prices.  
- **📌 Token Address Input**: Monitor any token on the go by providing its address at runtime.  
- **📊 Candlestick Charts**: Analyze historical price trends with beautiful terminal-based candlestick charts.  
- **🎨 Interactive UI**: Navigate a responsive and clean terminal interface powered by ratatui.  
- **🏎️ Blazing Fast**: Built with Rust for optimal performance, speed, and reliability.  

---

## 🛠️ **Installation**  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/yourusername/check-token-live.git  
   cd check-token-live  
   ```  

2. **Build the Project**  
   ```bash  
   cargo build --release  
   ```  

3. **Set Up API Key**  
   - Obtain an API key from the **[PumpFun API](https://pumpfun.com/)**.  
   - Create a `.env` file in the root directory and add the following:  
     ```bash  
     API_KEY=your_pumpfun_api_key  
     ```  

---

## 🚀 **How to Use**  

1. **Run the App**  
   ```bash  
   ./target/release/check-token-live  
   ```  

2. **Enter the Token Address**  
   When prompted, input the token address of the cryptocurrency you want to track.  

3. **Explore the Features**  
   - View **real-time prices** and **percentage changes**.  
   - Switch to **candlestick chart mode** for a detailed analysis of historical price movements.  

---

## 📦 **Dependencies**  

This project is powered by:  
- **[PumpFun API](https://pumpportal.fun/data-api/)**: Fetch live cryptocurrency data.  
- **[ratatui](https://github.com/tui-rs-revival/ratatui)**: Create the interactive terminal interface.  
- **[cli-candlestick-chart](https://crates.io/crates/cli-candlestick-chart)**: Generate stunning terminal-based candlestick charts.  

---

## 🤝 **Contributing**  

We ❤️ contributions! If you'd like to improve this project, follow these steps:  
1. Fork the repository.  
2. Create a new branch:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes:  
   ```bash  
   git commit -m "Add feature-name"  
   ```  
4. Push your branch:  
   ```bash  
   git push origin feature-name  
   ```  
5. Open a pull request.  

---

## 📜 **License**  

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

## 💡 **Acknowledgments**  

Special thanks to the amazing tools and platforms that made this project possible:  
- [Rust Programming Language](https://www.rust-lang.org/)  
- [PumpFun API](https://pumpfun.com/)  
- [ratatui](https://github.com/tui-rs-revival/ratatui)  
- [cli-candlestick-chart](https://crates.io/crates/cli-candlestick-chart)  