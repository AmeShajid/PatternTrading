# PatternTrading Project Structure

```
PatternTrading/
├── main.py                    # Main application entry point
├── data/                      # Training data for pattern recognition
│   ├── README.md             # Data collection guidelines
│   ├── bull_flag/            # Bull flag pattern screenshots
│   ├── bear_flag/            # Bear flag pattern screenshots  
│   ├── cup_handle/           # Cup & handle pattern screenshots
│   ├── double_top/           # Double top pattern screenshots
│   ├── double_bottom/        # Double bottom pattern screenshots
│   ├── ascending_triangle/   # Ascending triangle screenshots
│   ├── descending_triangle/  # Descending triangle screenshots
│   └── no_pattern/           # Non-pattern screenshots
├── models/                   # (Phase 3) Trained AI models
├── src/                      # (Phase 3+) Source code modules
│   ├── data_preprocessing.py # Data loading and preprocessing
│   ├── model_training.py     # CNN model training
│   ├── screen_capture.py     # Real-time screen capture
│   └── gui.py               # Confidence meter GUI
├── config/                   # (Phase 4+) Configuration files
│   └── monitor_config.json   # Screen capture region settings
└── requirements.txt          # Python dependencies

## Current Status: Phase 1 ✅ COMPLETE
- ✅ Defined 8 pattern classes
- ✅ Created folder structure  
- ✅ Added data collection guidelines

## Next Step: Phase 2 📸
Start collecting screenshots of chart patterns according to the guidelines in `data/README.md`
```
