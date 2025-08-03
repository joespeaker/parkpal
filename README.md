# 📱 ParkPal

**ParkPal** is a mobile-first application designed to help users discover and review public parks. Whether you're searching for a basketball court, a family-friendly playground, or simply a quiet spot with a picnic table, ParkPal helps you find the right park with confidence.

---

## 🚀 Features

- 📍 **Park Discovery**: Find parks by location or amenity.
- ⭐ **User Reviews**: Read and leave ratings and comments.
- 🏞️ **Photos**: Upload and browse park photos.
- 🛝 **Amenity Tracking**: Filter by courts, restrooms, shelters, playgrounds, picnic tables, water fountains, and more.
- 🧭 **Mobile-first Design**: Optimized for iOS with a native look and feel.

---

## 🛠 Tech Stack

- **Frontend**: [Framework you’re using—React Native, Flutter, etc.]
- **Backend**: [Supabase](https://supabase.com/)
- **Database**: PostgreSQL (via Supabase)
- **Auth**: Supabase Auth (Email/Password or OAuth)
- **Storage**: Supabase Bucket Storage for photos

---

## 🗂️ Database Schema Highlights

- `parks`: name, address, coordinates  
- `amenities`: court types, restrooms, etc.  
- `photos`: user-submitted park images  
- `reviews`: star rating, text, reviewer info

