# Geoffrey Sisco
Android Debugging Specialist | Open Source Contributor

Fixing real-world bugs in Android apps — from crash to root cause to verified fix

![Android](https://img.shields.io/badge/Android-Developer-3DDC84?logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![MVVM](https://img.shields.io/badge/Architecture-MVVM-blue)
![Room](https://img.shields.io/badge/Database-Room-green)
![Retrofit](https://img.shields.io/badge/Networking-Retrofit-orange)
![Git](https://img.shields.io/badge/Version_Control-Git-F05032?logo=git&logoColor=white)

Android debugging specialist focused on complex issues in real-world apps.

I isolate root causes, reproduce edge cases, and deliver minimal, reliable fixes with low regression risk.

Experienced in:
- Lifecycle edge cases (rotation, process death, state restoration)
- RecyclerView inconsistencies and stale UI state bugs
- Storage permission and filesystem edge cases (scoped storage, MediaStore)

Creator of **FilmAtlas**, a movie discovery Android app built with Java, MVVM, Retrofit, and Room.  
Contributor to **Amaze File Manager** and **AntennaPod** — production Android apps with thousands of users.

📫 Available for Android bug fixing and debugging work — geoffrey.sisco.dev@gmail.com

---

## Featured Case Studies

- Fixed duplicate files and stale UI in drawer categories by correcting reload behavior and query filtering
- Resolved Sleep Timer crash caused by main-thread database access in playback state retrieval
- Eliminated false network failure on startup caused by out-of-range pagination logic

🔗 https://github.com/geoffreysisco/android-bug-fixes

---

## Open Source Contributions
Real-world bug fixes in active Android projects:

### Amaze File Manager
Material design file manager for Android

• Fixed crash when opening Recent Files without storage permission ([PR #4569](https://github.com/TeamAmaze/AmazeFileManager/pull/4569)) — merged

• Fixed storage permission browsing flow ([PR #4578](https://github.com/TeamAmaze/AmazeFileManager/pull/4578)) — merged

• Fixed FAB remaining hidden after returning Home from drawer views ([PR #4582](https://github.com/TeamAmaze/AmazeFileManager/pull/4582)) — open

• Fixed file rename in drawer views ([PR #4584](https://github.com/TeamAmaze/AmazeFileManager/pull/4584)) — open

• Fixed search not working in drawer category views ([PR #4586](https://github.com/TeamAmaze/AmazeFileManager/pull/4586)) — open

• Fixed drawer category views not refreshing after file operations ([PR #4589](https://github.com/TeamAmaze/AmazeFileManager/pull/4589)) — open


### AntennaPod
A podcast manager for Android

• Fixed Sleep Timer dialog crash caused by main-thread database access in playback state retrieval ([PR #8366](https://github.com/AntennaPod/AntennaPod/pull/8366)) — merged  
  - Reworked dialog to use asynchronously loaded media state during UI refresh, avoiding a main-thread DB access path
    
---

## Projects

### FilmAtlas
Portfolio project exploring Android architecture, UI state management, and debugging workflows.
- Android movie discovery app focused on recent U.S. theatrical releases.

**Explore the FilmAtlas source code:**

🔗 https://github.com/geoffreysisco/FilmAtlas

<p align="center">
  <img src="https://raw.githubusercontent.com/geoffreysisco/FilmAtlas/main/docs/screenshots/discover.png"
       alt="FilmAtlas Discover screen"
       width="40%" />
  <img src="https://raw.githubusercontent.com/geoffreysisco/FilmAtlas/main/docs/screenshots/movie-details.png"
       alt="FilmAtlas movie details screen"
       width="40%" />
</p>

**Features**
- Randomized discovery feed
- Favorites
- Search
- Popular and recent movies

**Tech stack**
- Java
- Android SDK
- MVVM architecture
- Room database
- Retrofit (TMDB API)
- Gson (JSON serialization)
- LiveData & ViewModel
- Material Design 3
- Glide

---

## Current Focus

- Continue contributing to open source Android projects
- Improve FilmAtlas through refactoring, testing, and UI polish

## Availability

- Available for paid Android bug fixing and debugging work
