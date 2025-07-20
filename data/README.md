# PatternTrading - Data Collection Guide

## 📁 Folder Structure
Each folder represents a different chart pattern class for training:

### 🟢 Bull Flag
- **Description**: Upward trending flag after strong price move
- **Target**: ~300 screenshots of clean bull flag patterns
- **Folder**: `bull_flag/`

### 🔴 Bear Flag  
- **Description**: Downward trending flag after strong price decline
- **Target**: ~300 screenshots of clean bear flag patterns
- **Folder**: `bear_flag/`

### ☕ Cup & Handle
- **Description**: Cup-shaped pattern followed by small handle/consolidation
- **Target**: ~300 screenshots of cup & handle patterns
- **Folder**: `cup_handle/`

### ⬆️ Double Top
- **Description**: Two peaks at similar price levels (resistance)
- **Target**: ~300 screenshots of double top patterns
- **Folder**: `double_top/`

### ⬇️ Double Bottom
- **Description**: Two troughs at similar price levels (support)
- **Target**: ~300 screenshots of double bottom patterns  
- **Folder**: `double_bottom/`

### 📈 Ascending Triangle
- **Description**: Flat top resistance with rising support line
- **Target**: ~300 screenshots of ascending triangle patterns
- **Folder**: `ascending_triangle/`

### 📉 Descending Triangle
- **Description**: Flat bottom support with declining resistance line
- **Target**: ~300 screenshots of descending triangle patterns
- **Folder**: `descending_triangle/`

### ❌ No Pattern
- **Description**: Random chart sections with no clear pattern
- **Target**: ~300 screenshots of random/unclear chart sections
- **Folder**: `no_pattern/`

## 📸 Phase 2 Collection Guidelines

### ✅ Consistency Requirements:
- **Same platform**: Use consistent chart platform (TradingView, ThinkorSwim, etc.)
- **Same theme**: Stick to one color scheme/theme
- **Same timeframe**: Use consistent timeframe (e.g., 5-minute charts)
- **Same layout**: Keep chart layout and indicators consistent
- **Same resolution**: Take screenshots at consistent size

### 🎯 Quality Standards:
- Clear, unobstructed pattern visibility
- Good contrast and readability
- Pattern should be centered in screenshot
- Avoid overlapping text/indicators when possible
- Save as PNG or JPG format

### 📊 Recommended Tools:
- **Windows**: Snipping Tool, Greenshot, or Windows+Shift+S
- **macOS**: Command+Shift+4 or Command+Shift+5
- **Linux**: GNOME Screenshot, Flameshot

### 💡 Pro Tips:
- Start with obvious, textbook examples
- Include some borderline cases for robustness
- Take screenshots during different market conditions
- Mix different stocks/ETFs (SPY, QQQ, individual stocks)
- Save originals - you can resize later during preprocessing

---
**Next Phase**: Once you have ~300 images per class, proceed to Phase 3 (Model Training)
