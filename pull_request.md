## Android To-Do List App

This PR adds a complete Android To-Do List app built with:
- **Kotlin** + **MVVM architecture**
- **Room Database** for persistent local storage
- **Material Design 3** UI
- **GitHub Actions** workflow to automatically build and upload a debug APK on every push to `main`

### Features
- ✅ Add / Edit / Delete tasks
- ✅ Mark tasks complete with checkbox
- ✅ Priority levels (Low / Medium / High) with color indicators
- ✅ Filter tasks: All / Active / Completed
- ✅ Search tasks
- ✅ Swipe to delete + Undo (Snackbar)
- ✅ Persistent Room database storage

### After merging
1. Go to the **Actions** tab
2. Watch the **Build APK** workflow run
3. Download the **`todo-app-debug`** artifact (contains `app-debug.apk`)