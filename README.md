# 📱 Portfolio App

Modern mobile portfolio application built with Flutter showcasing professional profile, skills, and contact information with smooth animations and elegant design.

## ✨ Features

- **Home Page**: Animated introduction with typewriter effect, gradient profile avatar, and skill showcase
- **About Page**: Comprehensive professional information including education, experience, and expertise
- **Contact Page**: Interactive contact form with real-time validation
- **Smooth Animations**: Fade, slide, and scale animations for engaging user experience
- **Gradient UI**: Modern gradient backgrounds and glowing effects
- **Responsive Design**: Optimized for various screen sizes

## 🏗️ Flutter Components Used

### Core Widgets
- `AppBar` with gradient flex space
- `Text` & `ShaderMask` for gradient text effects
- `Column`, `Row`, `Wrap` for responsive layouts
- `Navigator` for seamless page transitions
- `Container` with advanced decoration
- `SingleChildScrollView` for scrollable content
- `Form` & `TextFormField` with validation
- `AnimatedTextKit` for typewriter animations
- `FadeTransition` & `SlideTransition` for smooth animations
- `TweenAnimationBuilder` for custom animations

### State Management
- `StatefulWidget` for Home and Contact pages
- `StatelessWidget` for About page
- `AnimationController` with multiple animations
- Form state management with `GlobalKey`

## � Project Structure

```
lib/
├── main.dart              # App entry point & routing
└── pages/
    ├── home_page.dart     # Home page with animations
    ├── about_page.dart    # About page
    └── contact_page.dart  # Contact form page
```

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (>=3.0.0)
- Dart SDK
- Android Studio / VS Code with Flutter extension

### Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd portfolio_app

# Install dependencies
flutter pub get

# Run the app
flutter run

# Build for release
flutter build apk --release
```

## 📦 Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| `animated_text_kit` | ^4.2.2 | Typewriter text animations |
| `font_awesome_flutter` | ^10.7.0 | Social media icons |
| `url_launcher` | ^6.2.5 | Launch external URLs |

## 🎨 Design Features

- **Modern Dark Theme** with gradient overlays
- **Animated Components** using Flutter's animation framework
- **Gradient Backgrounds** for depth and visual appeal
- **Glow Effects** with custom shadows and borders
- **Professional Typography** with proper spacing
- **Smooth Transitions** between pages and states
- **Responsive Layout** for various screen sizes

## 🎯 Technical Highlights

- Clean architecture with organized structure
- Advanced animations (Fade, Slide, Scale, Tween)
- Form validation and state management
- Modern UI/UX design principles
- Gradient effects and custom styling
- Professional code organization

## 📝 Assignment Requirements

**Mobile Programming - Meeting 4**

✅ Implemented Components:
- AppBar with gradient design
- Text widgets with effects
- Column & Row layouts
- Navigator for page transitions
- Form with validation
- StatefulWidget & StatelessWidget
- Multiple animation types
- Custom styling and theming

---

**Built with ❤️ using Flutter**
