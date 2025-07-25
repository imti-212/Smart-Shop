#  Smart Shop

A modern Flutter-based eCommerce app with clean architecture, state management, REST API integration, and responsive UI. Built for Android, Web, and Desktop platforms.

![Smart Shop Banner](http://localhost:56373/)

---

##  Features

-  Product listing from [Fake Store API](https://fakestoreapi.com/)
-  Refreshable product grid
-  Add to favorites (state managed)
-  Add to cart with badge counter
-  Profile screen
-  Responsive layout for mobile/web/desktop
-  Drawer Navigation with route-based screen switching
-  Clean code with Provider state management

---

## 📸 Screenshots



##  Tech Stack

- **Flutter** (Stable)
- **Provider** (State management)
- **HTTP** (API calls)
- **Fake Store API** (Data source)
- **Material UI** (Theme & Widgets)

---

##  Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/smart-shop.git
cd smart-shop
2. Install Dependencies
bash
Copy
Edit
flutter pub get
3. Run the App
bash
Copy
Edit
flutter run -d chrome     # Web
flutter run -d android    # Android
flutter run -d windows    # Windows (enable Developer Mode)
**Project Structure**
bash
Copy
Edit
lib/
├── models/              # Data models (Product)
├── providers/           # Cart & Favorite Providers
├── screens/             # Splash, Login, Home, Cart, Favorite, Profile
├── widgets/             # ProductCard, NavigationDrawer
└── main.dart            # App entry point with theming and routing
 API Used
Fake Store API – https://fakestoreapi.com/

No authentication required. Fetches real-time mock data for products.


To Do / Improvements
Add Firebase login or secure auth
Integrate payment gateway
Add bottom navigation
Modularize widgets further
Category-wise filtering

 Author
Imtiyaz Shafin

GitHub: (https://github.com/imti-212)


