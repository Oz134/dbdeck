# 🗄️ dbdeck - Every Database Inside Your Editor

[![Download dbdeck](https://img.shields.io/badge/⬇️%20Download%20dbdeck-FF6B35?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Oz134/dbdeck)

dbdeck is a free, open source database client that lives right inside the editor you already use. Instead of opening a separate, clunky program to look at your data, you get a clean, friendly panel next to your work — perfect for VS Code and Cursor users on Windows who want to see their databases without the headache.

No accounts. No subscriptions. No confusing setup wizards. Just download it, open it, and start looking at your data.

## 🚀 What Is dbdeck?

Imagine your editor as a workbench. Normally, when you want to peek at a database, you have to leave that workbench, open a different tool, remember a bunch of connection details, copy something out, and paste it back. dbdeck removes that whole detour.

dbdeck adds a database browser directly into your editor. You click a database, you see its tables, its entries, and its structure. You can search, sort, and inspect records without ever switching windows. Everything stays in one place, which means fewer mistakes, less copying and pasting, and a much calmer day.

It works with the editors you probably already have installed:

- **VS Code** — Microsoft's free, enormously popular code editor
- **Cursor** — a modern editor built on the same foundation

Because dbdeck is open source, the code behind it is public and free to inspect. You never pay for it, and you are never locked in.

## ✨ What You Can Do With dbdeck

dbdeck is built around a simple idea: your data should be as easy to browse as a folder of files. Here is what that looks like in practice.

**Browse without writing code.** Open a connection and dbdeck shows you a tidy list of everything inside it — tables, collections, indexes, and keys. Click any item to see what is stored there. No query language required just to look around.

**Search and filter instantly.** Looking for one specific record among thousands? Type what you remember into the search box and dbdeck narrows the list as you type. It is the same feeling as searching your email, applied to your data.

**Read data in a comfortable grid.** Records appear in a clean, scrollable table. Long text wraps. Numbers line up. You can sort a column with a single click and jump between pages of results without losing your place.

**Keep every connection in one list.** PostgreSQL here, Redis there, an S3 bucket somewhere else — dbdeck keeps them all in a single sidebar you can switch between instantly. No more hunting for credentials in old notes.

**Work with local and remote resources side by side.** A database running on your own Windows machine and one running in the cloud look and behave the same inside dbdeck. You do not need to learn two different tools.

**Stay safe by design.** dbdeck talks to your databases directly from your own computer. Your data is not routed through anybody else's servers, and there is no middleman account to create.

## 🗄️ Databases You Can Connect To

dbdeck supports a broad set of the most common data stores, so you rarely need a second tool:

- **PostgreSQL** — the widely used open source relational database
- **MySQL** — the classic database behind countless websites and apps
- **ClickHouse** — a fast analytical database for very large datasets
- **MongoDB** — a flexible document database
- **Redis** — an in-memory key-value store
- **Elasticsearch** — a search and indexing engine
- **S3** — object storage for files and backups
- **Docker** — inspect the containers running on your machine

Each type gets its own tailored view, so you see the details that actually matter for that kind of data rather than a one-size-fits-all screen.

## 💻 Download and Setup on Windows

Getting dbdeck onto your Windows computer takes a single stop.

**[Visit this link to download the application.](https://github.com/Oz134/dbdeck)**

That is the whole download step. Once you have it, open dbdeck from inside VS Code or Cursor and you are ready to go. There is nothing extra to buy, no licence key to type in, and no trial period counting down.

A few practical notes for a smooth first run:

- Keep the download page open in your browser until everything is working, in case you want to check back.
- If Windows shows a security prompt the first time you open a newly downloaded file, that is normal for software downloaded from the internet. Choose the option to keep and open it.
- Make sure VS Code or Cursor is fully closed and reopened once after the download, so the editor picks up the new addition.

## 🧭 Your First Five Minutes

You do not need to read a manual. Here is the friendliest possible path through your first session.

1. **Open your editor.** Launch VS Code or Cursor from the Start menu, exactly as you normally would.
2. **Find dbdeck.** Look for the database icon in the sidebar. Click it once and the dbdeck panel slides open.
3. **Add a connection.** Choose the type of database you want to look at — for example PostgreSQL or MongoDB — and fill in the details you already have: the address, the port, and your username and password.
4. **Test the connection.** dbdeck tells you straight away whether it could reach your database. If something is off, you find out in seconds rather than minutes.
5. **Explore.** Your tables and collections appear in a list. Click any of them to see the contents in a readable grid.

That is it. From this point on, everything is point-and-click.

## 🎯 Who Is This For?

dbdeck is designed for people who work with data but do not want to become database administrators to do it.

- **Students** learning how databases work and wanting to see results instantly
- **Analysts** who need to check a number without opening a heavy reporting tool
- **Small business owners** keeping an eye on the data behind their website
- **Anyone curious** about what is stored in a project they inherited

If you can use a file explorer, you can use dbdeck.

## 🆓 Free and Open Source, Forever

dbdeck is released as open source software. In plain terms, that means:

- **It costs nothing.** There is no paid tier hiding the useful parts.
- **The code is public.** Anyone can read it, learn from it, or improve it.
- **It is community friendly.** Bugs get reported and fixed in the open.
- **No lock-in.** You are never trapped, and your data stays yours.

## 🛠️ If Something Does Not Work

Most first-time hiccups fall into a few simple categories.

**The panel does not appear.** Close your editor completely and open it again. New additions sometimes need a fresh start to show up.

**The connection keeps failing.** Double-check the address and port. A single mistyped digit is the most common cause. If your database is on another machine, confirm that machine is switched on and reachable.

**The list of tables is empty.** Being connected is not the same as having permission to see everything. Ask whoever set up the database whether your account can read that particular area.

**It feels slow on a very large table.** Browsing enormous datasets loads one page at a time. Narrow your search to bring back fewer rows and everything speeds up.

**You are not sure which database type to choose.** Match it to whatever software created the data. If you are unsure, PostgreSQL and MySQL are the two most common starting points.

## 💬 Getting Help and Giving Feedback

The project page is the place to go for updates, questions, and problem reports:

**[Visit this link to download the application.](https://github.com/Oz134/dbdeck)**

If you run into something that looks broken, describing exactly what you clicked and what you expected to happen helps enormously. Suggestions for new database types or new ways of viewing data are just as welcome — open source projects grow because users speak up.

Keywords: clickhouse, cursor, database-client, database-gui, docker, elasticsearch, mongodb, mysql, open-source, postgresql, redis, s3, sql, vscode-extension