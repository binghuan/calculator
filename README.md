# Calculator

<img src="Icon.png" width="auto" height="240">

## Overview

A simple, responsive web-based calculator application with offline capabilities. This mobile-friendly calculator provides basic arithmetic operations and can be used without an internet connection after the initial load.

## 🌐 Live Demo

- **Web App**: [http://binghuan.github.io/calculator/](http://binghuan.github.io/calculator/)
- **Blog Post**: [http://studiobinghuan.blogspot.tw/2013/05/calculator.html?view=flipcard](http://studiobinghuan.blogspot.tw/2013/05/calculator.html?view=flipcard)

## ✨ Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (*), Division (/)
- **Offline Functionality**: Works without internet connection using Application Cache
- **Mobile Optimized**: Responsive design using jQuery Mobile framework
- **Touch-Friendly Interface**: Large buttons optimized for mobile devices
- **Clear Function**: Reset calculator with the "C" button
- **Real-time Display**: Shows calculations as you type
- **Progressive Web App**: Can be added to home screen on mobile devices

## 🛠️ Technology Stack

- **HTML5**: Structure and semantic markup with offline manifest
- **CSS3**: Styling with jQuery Mobile theme
- **JavaScript**: Calculator logic and event handling
- **jQuery 1.10.1**: DOM manipulation and event handling
- **jQuery Mobile 1.3.1**: Mobile UI framework for responsive design
- **Application Cache**: Enables offline functionality

## 📱 Supported Operations

| Operation | Symbol | Button |
|-----------|--------|--------|
| Addition | + | + |
| Subtraction | - | - |
| Multiplication | * | * |
| Division | / | / |
| Equals | = | = |
| Clear | C | C |
| Numbers | 0-9 | 0-9 |

## 🚀 How to Use

1. **Online**: Visit [the live demo](http://binghuan.github.io/calculator/)
2. **Offline**: After first visit, the app will work without internet connection
3. **Mobile**: Add to home screen for app-like experience

### Calculator Instructions:
1. Tap number buttons to input values
2. Tap operation buttons (+, -, *, /) to perform calculations
3. Tap "=" to see the result
4. Tap "C" to clear and start over
5. Calculations are performed left-to-right as you input operations

## 📁 Project Structure

```
calculator/
├── index.html              # Main HTML file
├── calculator.js           # Calculator logic and event handlers
├── calculator.css          # Custom styles
├── calculator.appcache     # Offline cache manifest
├── jquery-1.10.1.min.js   # jQuery library
├── jquery.mobile-1.3.1.min.js    # jQuery Mobile JavaScript
├── jquery.mobile-1.3.1.min.css   # jQuery Mobile CSS
├── Icon.png                # App icon
├── README.md              # This file
├── icons/                 # Various app icon sizes
│   ├── Icon-16.png
│   ├── Icon-32.png
│   ├── Icon-48.png
│   └── ... (various sizes for different devices)
└── images/                # UI assets
    ├── ajax-loader.gif
    ├── calculator_icon.png
    └── ... (jQuery Mobile icons)
```

## 🔧 Installation & Development

### Local Development:
1. Clone the repository:
   ```bash
   git clone https://github.com/binghuan/calculator.git
   cd calculator
   ```

2. Open `index.html` in a web browser or serve it using a local web server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

### Deployment:
The app is configured for GitHub Pages deployment. Simply push to the `gh-pages` branch to update the live version.

## 🌐 Browser Compatibility

- **Mobile Browsers**: iOS Safari, Android Chrome, Mobile Firefox
- **Desktop Browsers**: Chrome, Firefox, Safari, Edge
- **Offline Support**: All modern browsers with Application Cache support

## 🎯 Key Implementation Details

- **State Management**: Uses JavaScript variables to track current value, last operator, and calculation state
- **Event Handling**: jQuery event listeners for all button interactions
- **Calculation Logic**: Handles operator precedence and chained calculations
- **Offline Cache**: Application Cache manifest ensures all resources are cached for offline use
- **Mobile Optimization**: Viewport meta tags and jQuery Mobile for touch-friendly interface

## 📝 Future Enhancements

- [ ] Add decimal point support
- [ ] Implement memory functions (M+, M-, MR, MC)
- [ ] Add scientific calculator functions
- [ ] Implement keyboard support
- [ ] Add calculation history
- [ ] Migrate from deprecated Application Cache to Service Workers

## 👨‍💻 About

This is my second web application, created to demonstrate offline web app capabilities and mobile-first design principles. The primary focus was on creating a functional calculator that works seamlessly without an internet connection.

**Powered by BH_Lin**

---

### 中文說明

這是我的第二個網頁應用程式。本程式的特性是，使用者可以在離線的環境下，依然可以使用本網頁應用程式。這個簡單的計算機應用程式支援基本的數學運算，並且針對行動裝置進行了最佳化。

