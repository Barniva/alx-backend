# 🗄 Cache System

Python classes for different caching algorithms.

## 📚 Caching Types
- BasicCache (unlimited)
- FIFOCache 🔄
- LIFOCache 🔁
- LRUCache 🕰
- MRUCache ⏱
- LFUCache 📊

## 🛠 How it Works
- All caches inherit from BaseCache class
- `put(key, value)` for insert/update
- `get(key)` to fetch value
- Overflow? It prints the cache!

## 🚀 Usage
1. Import the cache class
2. Create a cache object
3. Add or retrieve values
4. Watch the magic happen!

## ✨ Key Features
- Data store based on dictionary
- Enforces MAX_ITEMS limit
- Discards first/least element
- Tracks hit/miss caching behavior

## 🎓 Summary
Master caching concepts like TTL, LRU, LFU, etc. Perfect for adding cache layers in apps, websites, or APIs. Boosts performance for frequently accessed data.

Questions? Feel free to ask! 🙋‍♂️
