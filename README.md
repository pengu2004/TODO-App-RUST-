ToDo CLI Application

Overview

This is a simple command-line ToDo application written in Rust. It allows users to manage tasks by adding, listing, marking as done, and deleting tasks. Tasks are stored in a text file for persistence, making it easy to keep track of your to-do items between sessions.

Features

	•	Add Tasks: Quickly add new tasks to your to-do list.
	•	List Tasks: View all pending tasks.
	•	Mark as Done: Mark tasks as complete once they are finished.
	•	Delete Tasks: Remove tasks from your list.
	•	Persistent Storage: Tasks are stored in a file, so your list is saved even after you close the application.

Installation

Prerequisites

	•	Rust programming language installed.

Clone the Repository
git clone https://github.com/yourusername/todo-cli.git
cd todo-cli
Build the Application
cargo build --release
Usage

The ToDo application can be used with the following commands:
todo add "Your task description"
