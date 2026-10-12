# Currency Converter 💱

A simple **Currency Converter desktop application** built using Java and Swing. This project was created while learning Java GUI development and practicing event handling, user input, and currency conversion logic.

## 📌 About the Project

The Currency Converter allows users to convert an amount from one currency to another through a simple graphical user interface (GUI).

Users can enter an amount, select the source and target currencies, and click the **Convert** button to see the converted amount.

## ✨ Features

- Simple and user-friendly graphical interface.
- Supports 9 currencies:
  - USD — US Dollar
  - EUR — Euro
  - JPY — Japanese Yen
  - GBP — British Pound
  - CAD — Canadian Dollar
  - AUD — Australian Dollar
  - CHF — Swiss Franc
  - CNY — Chinese Yuan
  - INR — Indian Rupee
- Input validation for empty or invalid amounts.
- Displays the converted amount formatted to two decimal places.
- Uses Java Swing components for the desktop interface.

## 🛠️ Technologies Used

- **Java** — Application logic and currency conversion.
- **Java Swing** — Graphical user interface.
- **AWT** — Layout management, colors, fonts, and event handling.
- **DecimalFormat** — Formatting the converted amount.

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Java Development Kit (JDK)
- A code editor or IDE, such as IntelliJ IDEA, Eclipse, or Visual Studio Code.

### Installation and Execution

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/Currency-Converter.git
```

Replace `YOUR-USERNAME` with your GitHub username and adjust the repository name if necessary.

**2. Navigate to the project directory**

```bash
cd Currency-Converter
```

**3. Compile the Java file**

```bash
javac Currency_Converter.java
```

**4. Run the application**

```bash
java Currency_Converter
```

The Currency Converter window should open on your desktop.

## 📖 How to Use

1. Enter the amount you want to convert.
2. Select the currency you are converting **from**.
3. Select the currency you are converting **to**.
4. Click the **Convert** button.
5. View the converted amount in the result label.

## 🧮 How It Works

The application stores predefined exchange rates relative to USD.

It calculates the conversion rate by dividing the target currency's stored rate by the source currency's stored rate.

**Formula:**

```text
Conversion Rate = Target Currency Rate / Source Currency Rate

Converted Amount = Entered Amount × Conversion Rate
```

For example, if the stored rates are:

- 1 USD = 0.84 EUR
- 1 USD = 109.65 JPY

The application uses these rates to calculate conversions between the selected currencies.

**Note:** The exchange rates are predefined sample values in the source code. They are not fetched from a live exchange-rate API and may be outdated. This application is intended for learning purposes, not real-time financial transactions.

## 🎯 What I Learned

While building this project, I practiced:

- Creating desktop applications using Java Swing.
- Working with `JFrame`, `JLabel`, `JTextField`, `JComboBox`, and `JButton`.
- Using `GridBagLayout` to arrange GUI components.
- Handling button clicks with `ActionListener`.
- Reading and validating user input.
- Using arrays to store currency codes and exchange rates.
- Performing calculations and formatting numerical results.
- Handling invalid numeric input using exception handling.

## 🔮 Future Improvements

- Integrate a live exchange-rate API.
- Add more currencies.
- Improve input validation for negative amounts and special numeric values.
- Add a clear or reset button.
- Improve the GUI design and responsiveness.
- Display conversion rates alongside the converted amount.

## 👨‍💻 Author

Created as a learning project while exploring Java programming and GUI development.

---

⭐ If you find this project useful, feel free to star the repository!
