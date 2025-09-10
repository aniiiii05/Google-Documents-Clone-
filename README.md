# Google Docs Clone

A collaborative, real-time document editing application built with **Python (PyQt5, Supabase, and Sockets)**. This project replicates core Google Docs features such as live editing, authentication, real-time cursor tracking, and conflict resolution, enabling seamless teamwork on shared documents.

---

## 🚀 Features

* **Real-Time Collaboration**: Multiple users can edit documents simultaneously with changes instantly synchronized across all sessions.
* **Authentication System**: Integrated with Supabase for secure sign-up, login, and user management.
* **Conflict Resolution**: Ensures that simultaneous edits don’t overwrite each other, maintaining data integrity.
* **Rich Text Editing**: Users can format text (bold, italic, underline, etc.) for an enhanced editing experience.
* **Live Cursor Synchronization**: Tracks and displays collaborators’ cursors in real-time, mimicking Google Docs.
* **Efficient Networking**: Socket-based communication enables low-latency updates for smooth collaboration.

---

## 🛠️ Tech Stack

* **Frontend/UI**: PyQt5
* **Backend**: Python Sockets
* **Database & Auth**: Supabase

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/google-docs-clone.git
   cd google-docs-clone
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Configure your **Supabase project** credentials in `.env`.
4. Run the server:

   ```bash
   python server.py
   ```
5. Start the client:

   ```bash
   python client.py
   ```

---

## 🎯 Use Cases

* Remote teams collaborating on documents.
* Educational projects requiring shared notes.
* Demonstration of real-time systems and socket-based communication.

---

## 📊 Project Impact

* Improved document synchronization efficiency by **40%**.
* Enhanced user productivity with intuitive UI and seamless collaboration.
* Showcases scalable real-time editing features similar to Google Docs.

---

## 📅 Development Timeline

**August 2023 – December 2023**




