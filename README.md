# 💱 Bank of Canada Currency Rate Bot

This is a UiPath RPA project that automatically retrieves the USD exchange rate from the [Bank of Canada](https://www.bankofcanada.ca/rates/exchange/daily-exchange-rates/) website and writes it into an Excel file.

---

## 🧠 Project Summary

- Uses **UI Automation** to get the current USD exchange rate  
- Saves the value in `ExchangeRate.xlsx`  
- Includes a `.bat` file to run the bot manually  
- Can be scheduled with Windows Task Scheduler  

---

## 📁 Files

| File | Purpose |
|------|---------|
| `Main.xaml` | UiPath automation file |
| `project.json` | Project definition |
| `ExchangeRate.xlsx` | Output Excel file |
| `run_bot.bat` | Batch script to trigger the robot |

---

## 🧰 Dependencies

- UiPath.Excel.Activities = 3.0.1  
- UiPath.System.Activities = 25.4.2  
- UiPath.UIAutomation.Activities = 25.10.2  
- Studio version: `2025.0.16 STS`

---

## ▶️ How to Use

1. Open the project in UiPath Studio  
2. Run `Main.xaml` or publish the project  
3. Double-click `run_bot.bat` to run the bot outside Studio  
4. Or schedule it using **Task Scheduler**

---

## 📌 Author

Developed by **Enes Aydogdu**  
UiPath Automation Developer Associate Certified  
🇨🇦 Based in Toronto | 🌐 Fluent in English & Turkish
