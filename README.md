# 🎁 Custom Reward Link Generator

Generate personalized Microsoft Rewards links with your custom terms - switch between different rewards while keeping your unique validation code.

## ✨ Features

- **Dual Input Modes**: Manual entry or extract from existing reward links
- **Multiple Reward Types**: Support for Amazon, League of Legends, Overwatch, Croma, and Spotify rewards
- **Real-time Preview**: See reward details before generating links
- **Modern UI**: Glass-morphism design with smooth animations
- **One-Click Copy**: Easy copying of generated links
- **Link Analysis**: Detailed breakdown of generated links
- **Responsive Design**: Works seamlessly on all devices

## 🚀 Webpage

![Custom Reward Link Generator](https://5h4kun1.github.io/Microsoft-Rewards/index.html)

## 🎯 How It Works

### Manual Mode
1. Enter your personal custom term (e.g., `edgepredeem`, `ML2V0V`)
2. Select your desired reward type
3. Click "Generate Custom Link"
4. Copy and use your personalized reward link

### Link Mode
1. Paste an existing reward link
2. Extract your personal term automatically
3. Choose a new reward type
4. Generate your new custom link

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/5h4kun1/Microsoft-Rewards.git
   cd Microsoft-Rewards
   ```

2. **Open in browser**
   ```bash
   # Simply open the HTML file in your browser
   open index.html
   # or
   double-click index.html
   ```

3. **Or serve locally** (optional)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

## 📋 Usage

### Supported Rewards

| Reward Type | Description | Code |
|-------------|-------------|------|
| Amazon Gift Card | Shop anything on Amazon | `000885000029` |
| League of Legends | In-game purchases for LoL | `000485000001` |
| Overwatch | Digital content for Overwatch | `000485000005` |
| Croma Gift Card | ₹500 electronics voucher | `000885000017` |
| Spotify Premium | Free music streaming | `000885000040` |

### Link Format

Generated links follow this pattern:
```
https://rewards.bing.com/redeem/[REWARD_CODE]/?form=[YOUR_TERM]
```

## 🔧 Technical Details

- **Frontend**: Pure HTML5, CSS3, and JavaScript
- **No Dependencies**: Runs entirely in the browser
- **Responsive**: Built with modern CSS Grid and Flexbox
- **Animations**: Smooth CSS transitions and keyframe animations
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## 🎨 Design Features

- **Glass-morphism UI** with backdrop blur effects
- **Gradient backgrounds** and smooth color transitions
- **Interactive elements** with hover and focus states
- **Responsive layout** that adapts to all screen sizes
- **Smooth animations** for better user experience

## 📱 Browser Compatibility

- ✅ Chrome 88+
- ✅ Firefox 84+
- ✅ Safari 14+
- ✅ Edge 88+

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow existing code style and formatting
- Test across different browsers
- Ensure responsive design works on all devices
- Add comments for complex functionality
- Update README if adding new features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for educational and personal use only. Users are responsible for compliance with Microsoft Rewards terms of service and applicable laws.

## 🐛 Bug Reports

If you encounter any issues, please [create an issue](https://github.com/5h4kun1/Microsoft-Rewards/issues) with:
- Browser and version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## 🔄 Changelog

### v1.0.0
- Initial release
- Manual and link extraction modes
- 5 reward types supported
- Modern glassmorphism UI
- Responsive design

## 🙏 Acknowledgments

- Microsoft Rewards for the inspiration
- Modern web design trends for UI/UX guidance
- Community feedback for feature improvements

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/5h4kun1/Microsoft-Rewards?style=social)
![GitHub forks](https://img.shields.io/github/forks/5h4kun1/Microsoft-Rewards?style=social)
![GitHub issues](https://img.shields.io/github/issues/5h4kun1/Microsoft-Rewards)
![GitHub license](https://img.shields.io/github/license/5h4kun1/Microsoft-Rewards)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/5h4kun1">5h4kun1</a>
</p>
