# 🌟 LGL ModMenu with AutoUpdate

The **LGL ModMenu with AutoUpdate** is designed to simplify and future-proof your game modding experience. Whether you're a seasoned modder or just getting started, this system reduces the time you spend maintaining mods after game updates.

## 🚀 Key Advantages

1. ✅ **Hook classes instead of offsets**  
   No more digging through memory addresses — simply hook into class names and methods directly. It's faster, cleaner, and easier to maintain.

2. ✅ **No need to search for `Update()`**  
   Traditional mods often rely on locating the `Update()` method in Unity games. With AutoUpdate, that's a thing of the past. The system automatically connects to the required methods behind the scenes.

3. ✅ **Features survive game updates**  
   Since class names typically remain more stable than memory offsets, most mod features continue to work even when the game gets updated — significantly reducing downtime.

---

## 💡 Why It Matters

Game developers frequently update their apps, changing memory layouts and function addresses. This breaks traditional mods that rely on hardcoded offsets. By switching to a **class/method-based hooking system**, LGL ModMenu ensures your mods are:

- 🔄 **Resilient** – fewer updates needed after a game patch  
- 🧩 **Modular** – easier to debug and extend  
- ⚡ **Efficient** – faster to set up and maintain

---

## 🔧 Designed for Modders

LGL ModMenu is ideal for Unity-based games and supports both native C++/JNI hook-based logic and external UI overlays. The AutoUpdate feature is particularly useful for mobile platforms like Android, where patching offsets manually can be tedious.

---

> 💬 _"Mod once, play always."_  
> — The LGL philosophy

(yes, I have no imagination :p)
