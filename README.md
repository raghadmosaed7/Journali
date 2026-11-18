[README.md](https://github.com/user-attachments/files/35016238/README.md)
# Journali

> Your thoughts, your story.

Journali is a simple and elegant journaling app for iPhone, built with SwiftUI and SwiftData. It gives you a calm, dark space to write down your thoughts and experiences, and to find them again whenever you need them.

## Purpose

Writing things down helps us reflect, remember, and process our days. Journali keeps that experience simple: open the app, write an entry, and come back to it later. Everything is stored on your device, so your journal stays yours.

## Features

- **Splash screen** that welcomes you and moves to the main page automatically.
- **Create journal entries** with a title and text. The date is added for you.
- **Delete entries** by swiping on a card, with a confirmation alert to avoid deleting by mistake.
- **Bookmark entries** to mark your favorite or most important notes.
- **Search** your journals by any word in the title or the text.
- **Empty state** that guides new users to write their first entry.
- **No results state** when a search does not match any entry.
- **Discard confirmation** when closing an entry you were writing.
- **Local storage** with SwiftData, so your entries are still there after you close the app.
- **Sort menu** to order entries by date or by bookmark.

## Coming Soon

- [ ] Edit existing journal entries
- [ ] Sort by bookmark (the menu is in place, the ordering is in progress)
- [ ] Prevent saving an empty entry
- [ ] Journal card design polish

## Built With

- **Swift**
- **SwiftUI** for the interface, using native components such as `NavigationStack`, `List`, `.searchable`, `.swipeActions`, `Menu`, and `ContentUnavailableView`
- **SwiftData** for saving and loading entries

## Requirements

- Xcode 15 or later
- iOS 17 or later

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Journali.git
   ```
2. Open `Journali.xcodeproj` in Xcode.
3. Select an iPhone simulator.
4. Press `Cmd + R` to build and run.

## Project Structure

```
Journali
├── Models
│   ├── JournalEntry     // The journal entry model saved with SwiftData
│   └── SortOption       // The available sorting options
├── Views
│   ├── SplashScreen     // Launch screen
│   ├── MainPage         // List, search, sort, delete, and add
│   ├── EmptyState       // Shown when there are no entries
│   └── AddJournalView   // Create a new entry
└── Components
    └── JournalCard      // A single entry card with the bookmark button
```

## User Stories

- As a user, I want to create a new journal entry, so that I can write my thoughts and experiences.
- As a user, I want to edit an existing journal entry, so that I can update or correct my thoughts.
- As a user, I want to delete a journal entry, so that I can remove entries that I no longer want to keep.
- As a user, I want to search for specific words or phrases in my journal entries, so that I can quickly find relevant thoughts or memories.
- As a user, I want to bookmark specific journal entries, so that I can easily find my favorite or important entries later.
- As a user, I want to filter my journal entries to view only those that are bookmarked, so that I can quickly access my most important notes.


## Author

Made by **Raghad**.
