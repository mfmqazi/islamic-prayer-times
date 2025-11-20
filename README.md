# Muslim Prayer Times Web App - IslamicHub

A beautiful, modern web application for displaying accurate Muslim prayer times with an elegant Islamic-themed design.

## 🎨 Features

### Core Functionality
- **Accurate Prayer Times**: Fetches real-time prayer data from the Aladhan API
- **Automatic Location Detection**: Uses browser geolocation to detect your current location
- **Manual Location Entry**: Option to manually enter city and country
- **Multiple Calculation Methods**: Supports 14+ calculation methods including:
  - Muslim World League (MWL) - Default
  - Islamic Society of North America (ISNA)
  - Umm Al-Qura University, Makkah
  - Egyptian General Authority of Survey
  - And many more...

### Prayer Categories
1. **Daily Prayers (5)**
   - Fajr 🌅
   - Sunrise 🌄
   - Dhuhr ☀️
   - Asr 🌤️
   - Maghrib 🌇
   - Isha 🌙

2. **Nafl Prayers (Voluntary)**
   - Ishraq (15 mins after sunrise until 10 mins before Dhuhr)
   - Chasht (Mid-morning prayer)
   - Zawal (10 mins before to 10 mins after Dhuhr)
   - Awwabin (After Maghrib until Isha)
   - Tahajjud (Last third of the night)

3. **Forbidden Times (Makrooh)**
   - Sunrise period (20 minutes)
   - Zawal (When sun is at zenith)
   - Sunset period

### User Interface
- **Premium Dark Theme**: Beautiful gradient backgrounds with Islamic gold accents
- **Smooth Animations**: Floating mosque icon, pulsing location marker, glowing effects
- **Current Prayer Highlighting**: Active prayer time is highlighted with golden accent
- **Responsive Design**: Works beautifully on desktop, tablet, and mobile
- **Hijri & Gregorian Dates**: Display of both Islamic and Western calendar dates
- **Time Format Options**: Switch between 12-hour and 24-hour formats

### Settings
- Change calculation method
- Toggle between 12/24 hour time formats
- Persistent settings (saved in browser)

## 🚀 How to Use

1. **Open the App**: Simply open `index.html` in any modern web browser
2. **Allow Location Access**: When prompted, allow location access for automatic detection
3. **View Prayer Times**: The app will automatically display prayer times for your location
4. **Change Location**: Click the "Change" button to manually enter a different city
5. **Adjust Settings**: Click the settings icon (⚙️) to change calculation method or time format

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup with Arabic font support
- **CSS3**: Modern styling with CSS variables, gradients, animations
- **Vanilla JavaScript**: No frameworks, pure ES6+ JavaScript
- **Aladhan API**: Free Islamic prayer times API

### API Endpoints Used
- Timings by Coordinates: `https://api.aladhan.com/v1/timings`
- Timings by City: `https://api.aladhan.com/v1/timingsByCity`

### Browser Compatibility
- Chrome/Edge (v90+)
- Firefox (v88+)
- Safari (v14+)
- Opera (v76+)

## 📱 Design Inspiration

The design takes inspiration from popular Islamic apps like Muslim Pro, featuring:
- Clean card-based layout
- Islamic geometric patterns in the background
- Gold and amber color scheme representing Islamic art
- Elegant typography combining Inter and Amiri fonts
- Smooth transitions and micro-animations

## 🎯 Key Design Principles

1. **Visual Excellence**: Premium UI with modern gradients and glassmorphism
2. **User Experience**: Intuitive navigation with clear visual hierarchy
3. **Accessibility**: High contrast text, large touch targets, semantic HTML
4. **Performance**: Lightweight, fast loading, minimal dependencies
5. **Responsiveness**: Adapts seamlessly to all screen sizes

## 📝 Notes

- Prayer times may vary slightly from local mosque times due to different calculation methods
- Internet connection required for fetching prayer times
- Location access improves accuracy but is optional
- Settings and preferences are saved locally in your browser

## 🤲 Credits

- Prayer Times API: [Aladhan](https://aladhan.com/)
- Fonts: Google Fonts (Inter, Amiri)
- Icons: Emoji-based for universal browser support

---

**Made with ❤️ for the Muslim community**
