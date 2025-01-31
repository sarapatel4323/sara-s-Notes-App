﻿# sara's-Notes-App

This is an Android application implementing a `RecyclerView` for managing notes. Each note includes a name, description, priority, and date. Users can view, edit, delete notes, and set priority levels, all presented in a `CardView` layout.

## Features

- **RecyclerView with Grid Layout**: The app uses a `GridLayoutManager` with 2 columns for displaying notes in a grid format.
- **Note Properties**:
  - **Name**: The title of the note.
  - **Description**: A brief description of the note.
  - **Priority**: A checkbox to set the note as high or low priority.
  - **Date**: Displayed as a formatted string (e.g., "MM dd, yyyy").
- **Edit and Delete Functionality**: Each note can be individually edited or deleted.
- **Priority Listener**: When the priority checkbox is toggled, the priority status is updated, and a toast notification displays the priority change for the specific note.
  
## Technologies Used

- **Android Studio**: Developed in Android Studio with XML for layout and Java for logic.
- **RecyclerView and CardView**: Display notes in a responsive, card-based grid.
- **Java**: Logic for managing note data, RecyclerView, and item events.
- **SimpleDateFormat**: Formats dates for displaying note creation or modification dates.


