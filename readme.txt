
Heks is a simple hex editor and visualizer. It can be used for analyzing and editing binary files and formats. It is a single page serverless application. It is inspired by a Nodejs-based hex editor that I wrote earlier as part of a commercial project, in which all heavylifting was done on the backend. Heks, on the other hand, does everything on the frontend. It uses the File System Access API and other modern Chrome browser features.

Key points (in no particular order):
-- Support of popular binary formats.
-- Efficient handling of huge files.
-- Simple and easy to use UI.
-- Visualization of binary data and memory layout.
-- This is a tool for programmers. Its users are supposed to know programming and be ready to work with its source code.
-- Organic growth. New layers of abstractions are introduced gradually when they are need to solve a concrete problem.
-- Serve as a demonstration that vanilla JavaScript is the best tool for building complex UI from scratch.
-- Modular design. It should be possible to test parts of the program in isolation.
-- Codebase must remain simple, easy to read and audit.
-- No TypeScript. I do like certain features of TypeScript but I don't want to introduce a transpiling step to the project workflow.
-- No Webpack. We only use a simple text editor and Web API docs.
-- No external dependenies. If you want something done well, do it yourself.
-- Focus on good old procedural style of programming. Object-oriented programming is used for building the UI toolkit.
-- Readiness to experiment. We don't recreate an existing program. We build a completely new program.
-- True open source. All tests, alternative solutions, and notes are published.
-- Desktop first (which may change in the future).
-- Have fun with code. A samurai has no goal, only the path.

This program is intended to be used with Chrome
